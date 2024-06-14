# 步步为营，由简入繁：利用零-shot数据增强策略，循序渐进地提升低资源环境下的对话状态跟踪能力。

发布时间：2024年06月13日

`Agent

理由：这篇论文主要介绍了一种新的数据增强框架（EDZ-DA），该框架利用大型语言模型来解析领域间的关联，并实现零-shot数据增强，以提升对话状态跟踪模型的性能。这种方法涉及到构建和优化对话系统中的智能代理（Agent），以更好地理解和处理对话内容。因此，它更符合Agent分类，而不是RAG、LLM应用或LLM理论。RAG通常指的是检索-增强生成模型，而这里并没有明确提到这种模型。LLM应用虽然涉及到大型语言模型的应用，但重点在于Agent的构建和优化，而非仅仅是LLM的应用。LLM理论则更多关注语言模型的理论研究，而本文的重点在于实际应用和方法的改进。` `对话系统`

> Plan, Generate and Complicate: Improving Low-resource Dialogue State Tracking via Easy-to-Difficult Zero-shot Data Augmentation

# 摘要

> 数据增强方法为提升低资源环境下对话状态跟踪模型的性能开辟了新途径。但传统方法过于依赖预设的用户目标，忽略了数据复杂性在此任务中的关键作用。本文提出的EDZ-DA框架，通过大型语言模型自动解析各领域间的关联，实现了从简单到复杂的零-shot数据增强。我们不仅深化了对话内容的领域关联，以强化模型处理共指槽的能力，还通过槽值的置换，有效避免了输出顺序的偏差和值生成不完整的问题。实验证明，EDZ-DA在MultiWOZ数据集上显著优于以往的数据增强方法。

> Data augmentation methods have been a promising direction to improve the performance of small models for low-resource dialogue state tracking. However, traditional methods rely on pre-defined user goals and neglect the importance of data complexity in this task. In this paper, we propose EDZ-DA, an Easy-to-Difficult Zero-shot Data Augmentation framework for low-resource dialogue state tracking that utilizes large language models to automatically catch the relationships of different domains and then generate the dialogue data. We also complicate the dialogues based on the domain relation to enhance the model's capability for co-reference slot tracking. Furthermore, we permute slot values to mitigate the influence of output orders and the problem of incomplete value generation. Experimental results illustrate the superiority of our proposed method compared to previous strong data augmentation baselines on MultiWOZ.

![步步为营，由简入繁：利用零-shot数据增强策略，循序渐进地提升低资源环境下的对话状态跟踪能力。](../../../paper_images/2406.08860/x1.png)

![步步为营，由简入繁：利用零-shot数据增强策略，循序渐进地提升低资源环境下的对话状态跟踪能力。](../../../paper_images/2406.08860/x2.png)

[Arxiv](https://arxiv.org/abs/2406.08860)