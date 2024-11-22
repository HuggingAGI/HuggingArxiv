# 理解经由检索头实现的合成上下文扩展

发布时间：2024年10月29日

`LLM应用` `模型训练`

> Understanding Synthetic Context Extension via Retrieval Heads

# 摘要

> 长上下文的 LLMs 在诸如检索增强生成等应用中的需求与日俱增。为降低长上下文下预训练 LLMs 的成本，近来的研究采用了合成上下文扩展的办法：在训练后的阶段，用合成生成的长上下文数据对 LLMs 进行微调。然而，这种合成上下文扩展如何及为何赋予下游长上下文任务相应能力，尚不明确。本文针对三个需要检索和推理的长上下文任务，对合成数据上的微调展开研究。我们改变了待检索的“针”概念的真实性以及周边“草堆”上下文的多样性，从利用 LLMs 构建合成文档，到使用模板关系并创建符号数据集。我们发现，基于合成数据训练的模型不如基于真实数据的模型，但令人意外的是，这种差异能通过一组负责长上下文检索的特殊注意力头来解释甚至预测，即检索头（Wu 等人，2024）。在合成数据上学到的检索头大多是在真实数据上学到的检索头的子集，而且学到的头的召回率与模型的下游性能之间存在很强的相关性。此外，通过注意力剔除和激活修补，我们从机制上表明检索头是必要的，能解释模型性能，不过它们并非完全足够。我们的成果为如何解读合成数据微调性能以及如何为在长上下文中学习现实世界的能力创建更优数据提供了启示。

> Long-context LLMs are increasingly in demand for applications such as retrieval-augmented generation. To defray the cost of pretraining LLMs over long contexts, recent work takes an approach of synthetic context extension: fine-tuning LLMs with synthetically generated long-context data in a post-training stage. However, it remains unclear how and why this synthetic context extension imparts abilities for downstream long-context tasks. In this paper, we investigate fine-tuning on synthetic data for three long-context tasks that require retrieval and reasoning. We vary the realism of "needle" concepts to be retrieved and diversity of the surrounding "haystack" context, from using LLMs to construct synthetic documents to using templated relations and creating symbolic datasets. We find that models trained on synthetic data fall short of the real data, but surprisingly, the mismatch can be interpreted and even predicted in terms of a special set of attention heads that are responsible for retrieval over long context: retrieval heads (Wu et al., 2024). The retrieval heads learned on synthetic data are mostly subsets of the retrieval heads learned on real data, and there is a strong correlation between the recall of heads learned and the downstream performance of a model. Furthermore, with attention knockout and activation patching, we mechanistically show that retrieval heads are necessary and explain model performance, although they are not totally sufficient. Our results shed light on how to interpret synthetic data fine-tuning performance and how to approach creating better data for learning real-world capabilities over long contexts.

[Arxiv](https://arxiv.org/abs/2410.22316)