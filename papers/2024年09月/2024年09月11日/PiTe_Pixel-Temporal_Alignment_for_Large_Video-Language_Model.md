# PiTe：为大型视频-语言模型实现像素与时间的精准对齐

发布时间：2024年09月11日

`LLM应用` `视频处理` `人工智能`

> PiTe: Pixel-Temporal Alignment for Large Video-Language Model

# 摘要

> 随着大型语言模型 (LLM) 的兴起，大型视觉-语言模型 (LVLMs) 应运而生，成为连接图像与文本的关键桥梁。然而，视频的复杂性使得 LVLMs 在处理时空数据时面临挑战。最新的大型视频-语言模型 (LVidLMs) 通过多模态任务，将图像等静态视觉数据与语言特征紧密结合。本文中，我们提出了一种通过对象轨迹进行细粒度对齐的新方法 PiTe，该方法在空间和时间维度上同时进行对齐，展现出强大的适用性。为实现这一目标，我们创建了包含像素级轨迹的预训练数据集 PiTe-143k，并通过自动标注技术确保数据的精确性。实验证明，PiTe 在多项视频多模态任务中显著超越了现有技术水平。

> Fueled by the Large Language Models (LLMs) wave, Large Visual-Language Models (LVLMs) have emerged as a pivotal advancement, bridging the gap between image and text. However, video making it challenging for LVLMs to perform adequately due to the complexity of the relationship between language and spatial-temporal data structure. Recent Large Video-Language Models (LVidLMs) align feature of static visual data like image into latent space of language feature, by general multi-modal tasks to leverage abilities of LLMs sufficiently. In this paper, we explore fine-grained alignment approach via object trajectory for different modalities across both spatial and temporal dimensions simultaneously. Thus, we propose a novel LVidLM by trajectory-guided Pixel-Temporal Alignment, dubbed PiTe, that exhibits promising applicable model property. To achieve fine-grained video-language alignment, we curate a multi-modal pre-training dataset PiTe-143k, the dataset provision of moving trajectories in pixel level for all individual objects, that appear and mention in the video and caption both, by our automatic annotation pipeline. Meanwhile, PiTe demonstrates astounding capabilities on myriad video-related multi-modal tasks through beat the state-of-the-art methods by a large margin.

[Arxiv](https://arxiv.org/abs/2409.07239)