# Tiny-Align：于边缘处架起自动语音识别与大型语言模型之间的桥梁

发布时间：2024年11月20日

`LLM应用` `边缘计算` `语音交互`

> Tiny-Align: Bridging Automatic Speech Recognition and Large Language Model on the Edge

# 摘要

> 大型语言模型（LLM）与自动语音识别（ASR）相结合，部署在边缘设备上（称为边缘 ASR-LLM）时，能充当强大的个性化助手，为用户实现基于音频的交互。相较于基于文本的交互，边缘 ASR-LLM 支持可访问且自然的音频交互。然而，现有的 ASR-LLM 模型主要在高性能计算环境中训练，产生的模型权重庞大，难以部署在边缘设备上。更关键的是，为更好满足用户个性化需求，鉴于音频输入常含高度个性化特征，需要进行个性化的设备端训练，所以 ASR-LLM 必须能从每个不同用户处学习。由于单独对 ASR 或 LLM 进行微调常因模态特定限制导致效果不佳，端到端训练能确保音频特征与语言理解无缝集成（跨模态对齐），最终在边缘设备上实现更个性化和高效的适配。但因现有方法训练要求复杂、计算量巨大，在边缘设备上实现 ASR 音频与 LLM 的跨模态对齐颇具挑战。在本研究中，我们提出了一种资源高效的跨模态对齐框架，用于在边缘设备上连接 ASR 和 LLM 以处理个性化音频输入。我们的框架能在资源受限的设备（如 NVIDIA Jetson Orin（8GB RAM））上实现高效的 ASR-LLM 对齐，训练时间提速 50 倍，同时对齐质量提升 50%以上。据我们所知，这是首个针对资源受限边缘设备上高效 ASR-LLM 对齐的研究工作。

> The combination of Large Language Models (LLM) and Automatic Speech Recognition (ASR), when deployed on edge devices (called edge ASR-LLM), can serve as a powerful personalized assistant to enable audio-based interaction for users. Compared to text-based interaction, edge ASR-LLM allows accessible and natural audio interactions. Unfortunately, existing ASR-LLM models are mainly trained in high-performance computing environments and produce substantial model weights, making them difficult to deploy on edge devices. More importantly, to better serve users' personalized needs, the ASR-LLM must be able to learn from each distinct user, given that audio input often contains highly personalized characteristics that necessitate personalized on-device training. Since individually fine-tuning the ASR or LLM often leads to suboptimal results due to modality-specific limitations, end-to-end training ensures seamless integration of audio features and language understanding (cross-modal alignment), ultimately enabling a more personalized and efficient adaptation on edge devices. However, due to the complex training requirements and substantial computational demands of existing approaches, cross-modal alignment between ASR audio and LLM can be challenging on edge devices. In this work, we propose a resource-efficient cross-modal alignment framework that bridges ASR and LLMs on edge devices to handle personalized audio input. Our framework enables efficient ASR-LLM alignment on resource-constrained devices like NVIDIA Jetson Orin (8GB RAM), achieving 50x training time speedup while improving the alignment quality by more than 50\%. To the best of our knowledge, this is the first work to study efficient ASR-LLM alignment on resource-constrained edge devices.

[Arxiv](https://arxiv.org/abs/2411.13766)