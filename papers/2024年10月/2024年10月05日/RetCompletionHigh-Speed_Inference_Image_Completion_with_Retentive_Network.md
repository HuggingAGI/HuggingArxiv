# RetCompletion：借助 Retentive Network 实现高速图像补全

发布时间：2024年10月05日

`LLM应用` `计算机视觉` `图像处理`

> RetCompletion:High-Speed Inference Image Completion with Retentive Network

# 摘要

> 时间成本是高质量多样化图像补全的一大难题。RetNet 在 NLP 中的低成本推理能力为此提供了新思路。我们借鉴这一思路，将 RetNet 应用于计算机视觉的图像补全任务，并提出了 RetCompletion 两阶段框架。第一阶段，Bi-RetNet 双向融合图像上下文信息，推理时采用单向逐像素更新策略，快速恢复高质量图像结构。第二阶段，CNN 低分辨率上采样增强纹理细节。实验显示，RetCompletion 的推理速度比 ICT 快 10 倍，比 RePaint 快 15 倍，尤其在掩码覆盖大面积图像时表现突出。

> Time cost is a major challenge in achieving high-quality pluralistic image completion. Recently, the Retentive Network (RetNet) in natural language processing offers a novel approach to this problem with its low-cost inference capabilities. Inspired by this, we apply RetNet to the pluralistic image completion task in computer vision. We present RetCompletion, a two-stage framework. In the first stage, we introduce Bi-RetNet, a bidirectional sequence information fusion model that integrates contextual information from images. During inference, we employ a unidirectional pixel-wise update strategy to restore consistent image structures, achieving both high reconstruction quality and fast inference speed. In the second stage, we use a CNN for low-resolution upsampling to enhance texture details. Experiments on ImageNet and CelebA-HQ demonstrate that our inference speed is 10$\times$ faster than ICT and 15$\times$ faster than RePaint. The proposed RetCompletion significantly improves inference speed and delivers strong performance, especially when masks cover large areas of the image.

[Arxiv](https://arxiv.org/abs/2410.04056)