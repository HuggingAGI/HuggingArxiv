# 利用多实例视觉提示生成器，提升多模态大型语言模型的视觉表示能力

发布时间：2024年06月05日

`RAG

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）中的视觉适配器问题，并提出了一种新的组件——多实例视觉提示生成器（MIVPG），以改进视觉信息的融合和处理。这种研究更偏向于模型架构的改进和优化，特别是在多模态信息处理方面，这与RAG（Retrieval-Augmented Generation）分类中的模型增强和信息检索增强的概念相吻合。虽然涉及到了大型语言模型（LLMs），但重点在于模型的应用和改进，而非理论研究，因此不属于LLM理论。同时，文中并未特别强调代理（Agent）的行为或决策过程，因此也不归类于Agent。` `视觉语言` `多模态学习`

> Enhancing Multimodal Large Language Models with Multi-instance Visual Prompt Generator for Visual Representation Enrichment

# 摘要

> 多模态大型语言模型（MLLMs）通过融合视觉表示与大型语言模型（LLMs），借助视觉适配器在多种视觉语言任务中取得了顶尖成绩。本文首先指出，使用基于查询的Transformer（如Q-former）的适配器是一种简化的多实例学习方法，忽略了实例间的异质性与相关性。随后，我们提出了一种创新组件——多实例视觉提示生成器（MIVPG），它利用同一样本内图像或补丁间的实例相关性，将更丰富的视觉信息融入LLMs。对三个不同场景下的公共视觉语言（VL）数据集进行的定量评估显示，MIVPG在关键VL任务上显著提升了Q-former的性能。

> Multimodal Large Language Models (MLLMs) have achieved SOTA performance in various visual language tasks by fusing the visual representations with LLMs leveraging some visual adapters. In this paper, we first establish that adapters using query-based Transformers such as Q-former is a simplified Multi-instance Learning method without considering instance heterogeneity/correlation. We then propose a general component termed Multi-instance Visual Prompt Generator (MIVPG) to incorporate enriched visual representations into LLMs by taking advantage of instance correlation between images or patches for the same sample. Quantatitive evaluation on three public vision-language (VL) datasets from different scenarios shows that the proposed MIVPG improves Q-former in main VL tasks.

![利用多实例视觉提示生成器，提升多模态大型语言模型的视觉表示能力](../../../paper_images/2406.02987/x1.png)

![利用多实例视觉提示生成器，提升多模态大型语言模型的视觉表示能力](../../../paper_images/2406.02987/x2.png)

![利用多实例视觉提示生成器，提升多模态大型语言模型的视觉表示能力](../../../paper_images/2406.02987/x3.png)

![利用多实例视觉提示生成器，提升多模态大型语言模型的视觉表示能力](../../../paper_images/2406.02987/x4.png)

![利用多实例视觉提示生成器，提升多模态大型语言模型的视觉表示能力](../../../paper_images/2406.02987/x5.png)

![利用多实例视觉提示生成器，提升多模态大型语言模型的视觉表示能力](../../../paper_images/2406.02987/x6.png)

![利用多实例视觉提示生成器，提升多模态大型语言模型的视觉表示能力](../../../paper_images/2406.02987/x7.png)

![利用多实例视觉提示生成器，提升多模态大型语言模型的视觉表示能力](../../../paper_images/2406.02987/x8.png)

![利用多实例视觉提示生成器，提升多模态大型语言模型的视觉表示能力](../../../paper_images/2406.02987/x9.png)

![利用多实例视觉提示生成器，提升多模态大型语言模型的视觉表示能力](../../../paper_images/2406.02987/x10.png)

[Arxiv](https://arxiv.org/abs/2406.02987)