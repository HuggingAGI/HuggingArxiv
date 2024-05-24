# 探索检索增强架构在图像描述生成中的应用

发布时间：2024年05月21日

`RAG

理由：这篇论文主要探讨了如何通过引入外部kNN记忆来优化图像字幕生成模型，这是一种结合了检索（Retrieval）和生成（Generation）的方法，特别是在多模态环境中优化语言模型的性能。这种方法与RAG（Retrieval-Augmented Generation）框架的理念相符，即通过检索外部知识来增强生成模型的性能。因此，将其归类为RAG是合适的。` `图像字幕生成` `计算机视觉`

> Towards Retrieval-Augmented Architectures for Image Captioning

# 摘要

> 图像字幕生成模型的目标是通过生成准确反映图像内容的自然语言描述，来弥合视觉与语言之间的鸿沟。近年来，借助深度学习技术，研究者在提取视觉特征和构建多模态连接方面取得了显著进展。本研究提出了一种创新方法，利用外部kNN记忆来优化图像字幕的生成过程。我们设计了两种模型变体，它们包含基于视觉相似性的知识检索器、可微分图像编码器以及基于上下文和外部记忆文本的kNN增强语言模型。实验结果显示，在COCO和nocaps数据集上，引入外部记忆显著提升了字幕质量，尤其是在大规模检索语料库中。这项研究不仅深化了我们对检索增强型字幕模型的理解，也为大规模图像字幕生成的改进指明了新方向。

> The objective of image captioning models is to bridge the gap between the visual and linguistic modalities by generating natural language descriptions that accurately reflect the content of input images. In recent years, researchers have leveraged deep learning-based models and made advances in the extraction of visual features and the design of multimodal connections to tackle this task. This work presents a novel approach towards developing image captioning models that utilize an external kNN memory to improve the generation process. Specifically, we propose two model variants that incorporate a knowledge retriever component that is based on visual similarities, a differentiable encoder to represent input images, and a kNN-augmented language model to predict tokens based on contextual cues and text retrieved from the external memory. We experimentally validate our approach on COCO and nocaps datasets and demonstrate that incorporating an explicit external memory can significantly enhance the quality of captions, especially with a larger retrieval corpus. This work provides valuable insights into retrieval-augmented captioning models and opens up new avenues for improving image captioning at a larger scale.

[Arxiv](https://arxiv.org/abs/2405.13127)