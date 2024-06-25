# 庞大的词汇量显著增强了大型语言模型的能力。

发布时间：2024年06月24日

`LLM理论

理由：这篇论文主要探讨了子词词汇量与大型语言模型（LLMs）性能之间的关系，并提出了一种优化词汇量的方法。这涉及到对LLMs内部机制的理解和改进，属于理论层面的研究。虽然实验部分涉及到了实际的模型训练和性能测试，但其核心关注点在于理论上的优化和改进，因此更适合归类为LLM理论。` `机器学习`

> Large Vocabulary Size Improves Large Language Models

# 摘要

> 本文通过实证研究揭示了子词词汇量与LLMs性能的关联，并探讨了如何优化词汇量设定。实验发现，扩大词汇量可提升模型性能。同时，我们探讨了在预训练模型上针对新语言进行持续训练的情境，并提出了一种替换预定义词汇的简便方法。实证表明，采用新词汇的模型在性能上超越了使用预训练词汇的模型。

> This paper empirically investigates the relationship between subword vocabulary size and the performance of large language models (LLMs) to provide insights on how to define the vocabulary size. Experimental results show that larger vocabulary sizes lead to better performance in LLMs. Moreover, we consider a continual training scenario where a pre-trained language model is trained on a different target language. We introduce a simple method to use a new vocabulary instead of the pre-defined one. We show that using the new vocabulary outperforms the model with the vocabulary used in pre-training.

[Arxiv](https://arxiv.org/abs/2406.16508)