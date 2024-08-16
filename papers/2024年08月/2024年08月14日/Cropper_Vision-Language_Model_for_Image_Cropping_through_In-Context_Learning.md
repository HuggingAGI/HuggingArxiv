# Cropper：一种利用上下文学习技术进行图像裁剪的视觉-语言模型

发布时间：2024年08月14日

`LLM应用` `图像处理` `视觉设计`

> Cropper: Vision-Language Model for Image Cropping through In-Context Learning

# 摘要

> 图像裁剪旨在从图像中挑选出视觉上吸引人的部分。传统方法受限于特定数据集训练的专用架构，难以适应新需求。随着大型视觉-语言模型（VLM）的进步，视觉上下文学习无需显式训练成为可能。然而，如何有效利用VLM进行视觉下游任务仍待深入探索。本文提出一种新方法，通过VLM优化图像裁剪。首先，我们设计了一种高效的提示检索机制，自动选取上下文示例。接着，采用迭代细化策略，逐步提升裁剪质量。名为Cropper的框架，广泛适用于各类裁剪任务，如自由形式、主题感知及宽高比感知裁剪。实验与用户研究显示，Cropper在多个基准测试中大幅超越现有技术。

> The goal of image cropping is to identify visually appealing crops within an image. Conventional methods rely on specialized architectures trained on specific datasets, which struggle to be adapted to new requirements. Recent breakthroughs in large vision-language models (VLMs) have enabled visual in-context learning without explicit training. However, effective strategies for vision downstream tasks with VLMs remain largely unclear and underexplored. In this paper, we propose an effective approach to leverage VLMs for better image cropping. First, we propose an efficient prompt retrieval mechanism for image cropping to automate the selection of in-context examples. Second, we introduce an iterative refinement strategy to iteratively enhance the predicted crops. The proposed framework, named Cropper, is applicable to a wide range of cropping tasks, including free-form cropping, subject-aware cropping, and aspect ratio-aware cropping. Extensive experiments and a user study demonstrate that Cropper significantly outperforms state-of-the-art methods across several benchmarks.

[Arxiv](https://arxiv.org/abs/2408.07790)