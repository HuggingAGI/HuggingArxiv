# 知识赋能，高效问答：医疗领域的问题生成新策略

发布时间：2024年05月23日

`LLM应用

这篇论文主要探讨了如何提升小型语言模型在医学领域的性能，通过微调和使用大型语言模型GPT-4生成的数据来优化小型模型。此外，还介绍了一个新的医学问答数据集ECN-QA。这些内容主要集中在应用层面，即如何改进和应用语言模型来解决特定的医学知识表示问题，因此属于LLM应用分类。`

> Efficient Medical Question Answering with Knowledge-Augmented Question Generation

# 摘要

> 随着语言模型应用领域的扩展，医学知识表示因其专业性而成为一个显著挑战。尽管如GPT-4这样的大型语言模型在医学问答上表现尚可，小型模型却相形见绌。为此，我们提出了一种双管齐下的策略，旨在提升小型语言模型在医学领域的性能。首先，我们对模型进行基于医学教科书语料库的微调；其次，借助GPT-4生成基于教科书知识的类似下游任务问题，以此进一步优化模型。此外，我们还推出了ECN-QA，一个包含“渐进式问题”的医学问答数据集，展示了我们训练策略的成效。研究揭示，经过精心微调，小型语言模型在医学领域同样潜力巨大。相关代码和模型权重已公开于https://github.com/raidium-med/MQG。

> In the expanding field of language model applications, medical knowledge representation remains a significant challenge due to the specialized nature of the domain. Large language models, such as GPT-4, obtain reasonable scores on medical question answering tasks, but smaller models are far behind. In this work, we introduce a method to improve the proficiency of a small language model in the medical domain by employing a two-fold approach. We first fine-tune the model on a corpus of medical textbooks. Then, we use GPT-4 to generate questions similar to the downstream task, prompted with textbook knowledge, and use them to fine-tune the model. Additionally, we introduce ECN-QA, a novel medical question answering dataset containing ``progressive questions'' composed of related sequential questions. We show the benefits of our training strategy on this dataset. The study's findings highlight the potential of small language models in the medical domain when appropriately fine-tuned. The code and weights are available at https://github.com/raidium-med/MQG.

[Arxiv](https://arxiv.org/abs/2405.14654)