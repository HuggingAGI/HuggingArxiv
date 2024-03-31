# MagicLens：借助开放式指令实现自监督图像搜索

发布时间：2024年03月28日

`LLM应用` `计算机视觉` `图像检索`

> MagicLens: Self-Supervised Image Retrieval with Open-Ended Instructions

# 摘要

> 图像检索任务中，我们通常面临的挑战是如何捕捉到用户复杂的搜索意图，这不仅仅依赖于图像本身的视觉信息。最新研究通过文本指令，让用户能够更自由地描述他们想要找到的图像。不同于以往研究集中于视觉相似性或少数预设关系的图像对，我们认为文本指令能够揭示更深层次的图像关系。为此，我们推出了MagicLens，这是一款新型的自监督图像检索模型，它能够理解开放式的文本指令。MagicLens的核心发现是：同一页上的图像对往往隐含着多种关系，如“内部视图”等，而这些关系可以通过大型多模态和语言模型来显式化。该模型使用从网络中挖掘的3670万个包含丰富语义关系的三元组进行训练，在多个图像检索任务的基准测试中，MagicLens达到了甚至超越了当前最先进的水平。尤其值得注意的是，在多个测试中，MagicLens以仅五十分之一的模型规模，实现了超越。此外，对140万张未见过的图像进行的人类分析进一步证实了MagicLens能够支持的搜索意图的广泛性。

> Image retrieval, i.e., finding desired images given a reference image, inherently encompasses rich, multi-faceted search intents that are difficult to capture solely using image-based measures. Recent work leverages text instructions to allow users to more freely express their search intents. However, existing work primarily focuses on image pairs that are visually similar and/or can be characterized by a small set of pre-defined relations. The core thesis of this paper is that text instructions can enable retrieving images with richer relations beyond visual similarity. To show this, we introduce MagicLens, a series of self-supervised image retrieval models that support open-ended instructions. MagicLens is built on a key novel insight: image pairs that naturally occur on the same web pages contain a wide range of implicit relations (e.g., inside view of), and we can bring those implicit relations explicit by synthesizing instructions via large multimodal models (LMMs) and large language models (LLMs). Trained on 36.7M (query image, instruction, target image) triplets with rich semantic relations mined from the web, MagicLens achieves comparable or better results on eight benchmarks of various image retrieval tasks than prior state-of-the-art (SOTA) methods. Remarkably, it outperforms previous SOTA but with a 50X smaller model size on multiple benchmarks. Additional human analyses on a 1.4M-image unseen corpus further demonstrate the diversity of search intents supported by MagicLens.

[Arxiv](https://arxiv.org/abs/2403.19651)