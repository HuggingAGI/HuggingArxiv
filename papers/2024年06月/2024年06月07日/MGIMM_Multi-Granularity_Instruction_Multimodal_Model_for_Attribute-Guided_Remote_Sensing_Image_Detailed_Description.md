# MGIMM：一种多粒度指令驱动的多模态模型，专为属性引导下的遥感图像详细描述而设计。

发布时间：2024年06月07日

`Agent

理由：这篇论文介绍了一个名为“多粒度指令多模态模型（MGIMM）”的模型，该模型专门设计用于遥感领域的视觉与文本信息的处理。它通过区域级指令调优，使模型能够理解和匹配视觉区域与文本属性。这种模型可以被视为一个智能Agent，因为它能够响应用户需求，处理特定的任务（即遥感图像的详细描述），并在特定领域（遥感）中执行任务。此外，该模型利用了大型语言模型来增强其功能，但主要关注点是作为一个Agent在遥感领域的应用，而不是对LLM的理论探讨或RAG（Retrieval-Augmented Generation）的应用。因此，将其归类为Agent是合适的。` `多模态学习`

> MGIMM: Multi-Granularity Instruction Multimodal Model for Attribute-Guided Remote Sensing Image Detailed Description

# 摘要

> 近期，大型多模态模型虽已打通视觉与文本信息的通道，但在遥感领域表现欠佳。这主要源于遥感图像中物体分布的复杂性和目标间巨大的尺度差异，导致视觉信息模糊且描述不足。加之，缺乏针对遥感的多模态微调数据，使得模型难以精准响应用户需求。为此，本文推出了\textbf{多粒度指令多模态模型（MGIMM）}，旨在通过区域级指令调优，让模型学会视觉区域与文本属性（如物体名称、颜色、形状）的匹配。MGIMM利用多粒度视觉特征，不仅捕捉区域细节，还把握全局图像信息，借助大型语言模型，为遥感图像提供详尽描述。我们创建了一个包含38,320个区域-属性对和23,463个图像-详细描述对的数据集，填补了这一领域的空白。实验证明，MGIMM的区域-属性引导学习策略卓有成效。相关代码已公开于https://github.com/yangcong356/MGIMM.git。

> Recently, large multimodal models have built a bridge from visual to textual information, but they tend to underperform in remote sensing scenarios. This underperformance is due to the complex distribution of objects and the significant scale differences among targets in remote sensing images, leading to visual ambiguities and insufficient descriptions by these multimodal models. Moreover, the lack of multimodal fine-tuning data specific to the remote sensing field makes it challenging for the model's behavior to align with user queries. To address these issues, this paper proposes an attribute-guided \textbf{Multi-Granularity Instruction Multimodal Model (MGIMM)} for remote sensing image detailed description. MGIMM guides the multimodal model to learn the consistency between visual regions and corresponding text attributes (such as object names, colors, and shapes) through region-level instruction tuning. Then, with the multimodal model aligned on region-attribute, guided by multi-grain visual features, MGIMM fully perceives both region-level and global image information, utilizing large language models for comprehensive descriptions of remote sensing images. Due to the lack of a standard benchmark for generating detailed descriptions of remote sensing images, we construct a dataset featuring 38,320 region-attribute pairs and 23,463 image-detailed description pairs. Compared with various advanced methods on this dataset, the results demonstrate the effectiveness of MGIMM's region-attribute guided learning approach. Code can be available at https://github.com/yangcong356/MGIMM.git

[Arxiv](https://arxiv.org/abs/2406.04716)