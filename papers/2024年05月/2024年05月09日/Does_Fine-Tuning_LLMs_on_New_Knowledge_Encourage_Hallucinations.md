# 微调 LLMs 以吸收新知，是否会催生幻觉？

发布时间：2024年05月09日

`LLM理论

这篇论文探讨了大型语言模型（LLM）在监督式微调过程中引入新知识对其产生事实错误（幻觉）的影响。研究通过闭卷问答的实验来分析微调过程中新知识的学习速度以及其对模型产生幻觉倾向的影响。这涉及到LLM的知识获取和应用机制，因此属于LLM理论的范畴。研究结果强调了微调中新知识引入的风险，并指出LLM主要通过预训练获取事实知识，而微调则影响其运用这些知识的方式。这与LLM应用不同，因为它更侧重于模型内部的工作原理和知识处理机制，而不是直接的应用场景或安全性问题。` `机器学习`

> Does Fine-Tuning LLMs on New Knowledge Encourage Hallucinations?

# 摘要

> 大型语言模型在监督式微调过程中可能会接触到预训练之外的新事实，这可能导致模型产生事实错误的幻觉。我们通过闭卷问答的受控实验，探究了微调中引入新知识对模型利用先前知识能力的影响。实验表明，大型语言模型在微调中学习新事实的速度较慢，但一旦学会，却会线性增加产生幻觉的倾向。我们的研究强调了微调中新知识引入的风险，并指出大型语言模型主要通过预训练获取事实知识，而微调则使其更高效地运用这些知识。

> When large language models are aligned via supervised fine-tuning, they may encounter new factual information that was not acquired through pre-training. It is often conjectured that this can teach the model the behavior of hallucinating factually incorrect responses, as the model is trained to generate facts that are not grounded in its pre-existing knowledge. In this work, we study the impact of such exposure to new knowledge on the capability of the fine-tuned model to utilize its pre-existing knowledge. To this end, we design a controlled setup, focused on closed-book QA, where we vary the proportion of the fine-tuning examples that introduce new knowledge. We demonstrate that large language models struggle to acquire new factual knowledge through fine-tuning, as fine-tuning examples that introduce new knowledge are learned significantly slower than those consistent with the model's knowledge. However, we also find that as the examples with new knowledge are eventually learned, they linearly increase the model's tendency to hallucinate. Taken together, our results highlight the risk in introducing new factual knowledge through fine-tuning, and support the view that large language models mostly acquire factual knowledge through pre-training, whereas fine-tuning teaches them to use it more efficiently.

[Arxiv](https://arxiv.org/abs/2405.05904)