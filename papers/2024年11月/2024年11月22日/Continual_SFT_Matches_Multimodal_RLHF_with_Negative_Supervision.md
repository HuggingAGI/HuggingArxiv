# 持续的 SFT 与带有负监督的多模态 RLHF 相契合

发布时间：2024年11月22日

`LLM应用` `视觉语言模型` `多模态`

> Continual SFT Matches Multimodal RLHF with Negative Supervision

# 摘要

> 多模态 RLHF 通常在有监督微调（SFT）阶段之后出现，旨在持续提升视觉语言模型（VLMs）的理解水平。传统看法认为，在偏好对齐阶段，它比持续的 SFT 更出色。在本文中，我们发现多模态 RLHF 的核心价值在于其负监督，也就是被拒绝响应的对数几率。于是，我们提出了一种全新的负监督微调（nSFT）方法，充分挖掘了其中蕴含的信息。我们的 nSFT 在 RLHF 范式中化解了这种负监督，并通过简单的 SFT 损失持续让 VLMs 对齐。这比多模态 RLHF 更节省内存，因为多模态 RLHF 严格需要 2 个（如 DPO）或 4 个（如 PPO）大型 VLMs。通过在不同的数据集来源、基础 VLMs 和评估指标上与各类多模态 RLHF 方法进行对比，有力地证明了 nSFT 的有效性。此外，还提供了大量的消融实验来支撑我们的假设。我们期望本文能够推动关于正确对齐大型视觉语言模型的进一步研究。

> Multimodal RLHF usually happens after supervised finetuning (SFT) stage to continually improve vision-language models' (VLMs) comprehension. Conventional wisdom holds its superiority over continual SFT during this preference alignment stage. In this paper, we observe that the inherent value of multimodal RLHF lies in its negative supervision, the logit of the rejected responses. We thus propose a novel negative supervised finetuning (nSFT) approach that fully excavates these information resided. Our nSFT disentangles this negative supervision in RLHF paradigm, and continually aligns VLMs with a simple SFT loss. This is more memory efficient than multimodal RLHF where 2 (e.g., DPO) or 4 (e.g., PPO) large VLMs are strictly required. The effectiveness of nSFT is rigorously proved by comparing it with various multimodal RLHF approaches, across different dataset sources, base VLMs and evaluation metrics. Besides, fruitful of ablations are provided to support our hypothesis. We hope this paper will stimulate further research to properly align large vision language models.

[Arxiv](https://arxiv.org/abs/2411.14797)