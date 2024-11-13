# 用 ImageRAG 增强超高分辨率遥感图像分析

发布时间：2024年11月12日

`RAG` `图像处理`

> Enhancing Ultra High Resolution Remote Sensing Imagery Analysis with ImageRAG

# 摘要

> 超高清分辨率（UHR）遥感图像（RSI）（例如 100,000×100,000 像素或更多）对当前的遥感多模态大型语言模型（RSMLLMs）构成了重大挑战。如果选择将 UHR 图像调整为标准输入图像大小，UHR 图像所包含的大量空间和上下文信息将被忽略。否则，这些图像的原始大小通常会超过标准 RSMLLMs 的令牌限制，使得难以处理整个图像并捕获基于丰富视觉上下文回答查询的远程依赖关系。在本文中，我们为 RS 引入了 ImageRAG，这是一个无需训练的框架，用于解决分析 UHR 遥感图像的复杂性。通过将 UHR 遥感图像分析任务转换为图像的长上下文选择任务，我们基于检索增强生成（RAG）技术设计了一种创新的图像上下文检索机制，称为 ImageRAG。ImageRAG 的核心创新在于其能够有选择地检索并关注与给定查询相关的 UHR 图像中最相关的部分作为视觉上下文。在这个框架中提出了快速路径和慢速路径，以高效有效地处理此任务。ImageRAG 允许 RSMLLMs 管理来自 UHR RSI 的大量上下文和空间信息，确保分析既准确又高效。

> Ultra High Resolution (UHR) remote sensing imagery (RSI) (e.g. 100,000 $\times$ 100,000 pixels or more) poses a significant challenge for current Remote Sensing Multimodal Large Language Models (RSMLLMs). If choose to resize the UHR image to standard input image size, the extensive spatial and contextual information that UHR images contain will be neglected. Otherwise, the original size of these images often exceeds the token limits of standard RSMLLMs, making it difficult to process the entire image and capture long-range dependencies to answer the query based on the abundant visual context. In this paper, we introduce ImageRAG for RS, a training-free framework to address the complexities of analyzing UHR remote sensing imagery. By transforming UHR remote sensing image analysis task to image's long context selection task, we design an innovative image contextual retrieval mechanism based on the Retrieval-Augmented Generation (RAG) technique, denoted as ImageRAG. ImageRAG's core innovation lies in its ability to selectively retrieve and focus on the most relevant portions of the UHR image as visual contexts that pertain to a given query. Fast path and slow path are proposed in this framework to handle this task efficiently and effectively. ImageRAG allows RSMLLMs to manage extensive context and spatial information from UHR RSI, ensuring the analysis is both accurate and efficient.

[Arxiv](https://arxiv.org/abs/2411.07688)