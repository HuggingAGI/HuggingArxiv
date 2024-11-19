# 借助渐进式概念瓶颈驱动的对齐手段来提升视觉语言模型的安全性

发布时间：2024年11月18日

`LLM应用` `计算机视觉` `网络安全`

> Enhancing Vision-Language Model Safety through Progressive Concept-Bottleneck-Driven Alignment

# 摘要

> 得益于大型语言模型（LLMs）的强大功能，与 LLMs 相连接的预训练视觉编码器模型构成了视觉语言模型（VLMs）。然而，近期研究显示，VLMs 中的视觉模态极为脆弱，攻击者能借由视觉传输的内容绕过 LLMs 的安全对齐，发动有害攻击。为应对此挑战，我们提出了一种渐进式基于概念的对齐策略 PSA-VLM，将安全模块作为概念瓶颈，以增强视觉模态的安全对齐。通过使模型预测与特定安全概念对齐，我们增强了对危险图像的防御能力，提高了可解释性和可控性，同时对整体性能的影响极小。我们的方法通过两阶段训练获得。第一阶段计算成本低，带来了极为有效的性能提升，第二阶段对语言模型的微调进一步提高了安全性能。我们的方法在热门的 VLM 安全基准测试中取得了领先的成果。

> Benefiting from the powerful capabilities of Large Language Models (LLMs), pre-trained visual encoder models connected to LLMs form Vision Language Models (VLMs). However, recent research shows that the visual modality in VLMs is highly vulnerable, allowing attackers to bypass safety alignment in LLMs through visually transmitted content, launching harmful attacks. To address this challenge, we propose a progressive concept-based alignment strategy, PSA-VLM, which incorporates safety modules as concept bottlenecks to enhance visual modality safety alignment. By aligning model predictions with specific safety concepts, we improve defenses against risky images, enhancing explainability and controllability while minimally impacting general performance. Our method is obtained through two-stage training. The low computational cost of the first stage brings very effective performance improvement, and the fine-tuning of the language model in the second stage further improves the safety performance. Our method achieves state-of-the-art results on popular VLM safety benchmark.

[Arxiv](https://arxiv.org/abs/2411.11543)