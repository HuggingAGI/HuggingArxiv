# CLIP赋能的TASS：一种专为视听问答设计的目标感知单流网络，它巧妙地融合了视觉和听觉信息，以精准解答跨模态问题。

发布时间：2024年05月12日

`RAG

这篇论文聚焦于视觉-语言预训练模型（VLMs）在视听问答（AVQA）领域的应用，特别是在细粒度的视听推理方面。它提出了一个创新的基于CLIP的目标感知单流（TASS）网络，旨在通过自然的视听匹配特性，将预训练模型的图像-文本匹配知识应用于AVQA。该网络包含两个核心模块，即目标感知空间定位（TSG+）和单流联合时间定位（JTG），这些模块旨在更好地融合视觉和音频信息，并利用预训练的知识进行跨模态匹配。因此，这篇论文更偏向于RAG（Retrieval-Augmented Generation）的范畴，因为它涉及到了预训练模型的知识检索和增强生成过程，特别是在多模态任务中的应用。` `视听问答` `多模态学习`

> CLIP-Powered TASS: Target-Aware Single-Stream Network for Audio-Visual Question Answering

# 摘要

> 视觉-语言预训练模型（VLMs）虽在多模态任务中大放异彩，但在细粒度的视听推理，尤其是视听问答（AVQA）领域，其潜力尚未充分挖掘。AVQA对VLMs提出了新挑战，要求它们在区域级视觉理解和音频模态融合上展现卓越能力。以往的AVQA方法虽采用CLIP作为特征编码器，却未能充分发挥其潜力，且在双流框架中将音频与视频视为孤立个体。本文创新性地提出了基于CLIP的目标感知单流（TASS）网络，旨在通过自然的视听匹配特性，将预训练模型的图像-文本匹配知识应用于AVQA。该网络包含两大核心模块：目标感知空间定位（TSG+）和单流联合时间定位（JTG）。TSG+模块巧妙地将CLIP的图像-文本匹配知识迁移至区域-文本匹配，无需真实标签的辅助。而JTG模块则在单一架构中融合了视听信息与问题感知时间定位，将音频与视频视为一体，通过跨模态同步（CMS）损失保持时间相关性，进一步拓展了预训练的图像-文本知识至音频-文本匹配。在MUSIC-AVQA基准上的实验充分证明了我们方法的优越性，超越了现有的顶尖技术。

> While vision-language pretrained models (VLMs) excel in various multimodal understanding tasks, their potential in fine-grained audio-visual reasoning, particularly for audio-visual question answering (AVQA), remains largely unexplored. AVQA presents specific challenges for VLMs due to the requirement of visual understanding at the region level and seamless integration with audio modality. Previous VLM-based AVQA methods merely used CLIP as a feature encoder but underutilized its knowledge, and mistreated audio and video as separate entities in a dual-stream framework as most AVQA methods. This paper proposes a new CLIP-powered target-aware single-stream (TASS) network for AVQA using the image-text matching knowledge of the pretrained model through the audio-visual matching characteristic of nature. It consists of two key components: the target-aware spatial grounding module (TSG+) and the single-stream joint temporal grounding module (JTG). Specifically, we propose a TSG+ module to transfer the image-text matching knowledge from CLIP models to our region-text matching process without corresponding ground-truth labels. Moreover, unlike previous separate dual-stream networks that still required an additional audio-visual fusion module, JTG unifies audio-visual fusion and question-aware temporal grounding in a simplified single-stream architecture. It treats audio and video as a cohesive entity and further extends the pretrained image-text knowledge to audio-text matching by preserving their temporal correlation with our proposed cross-modal synchrony (CMS) loss. Extensive experiments conducted on the MUSIC-AVQA benchmark verified the effectiveness of our proposed method over existing state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2405.07451)