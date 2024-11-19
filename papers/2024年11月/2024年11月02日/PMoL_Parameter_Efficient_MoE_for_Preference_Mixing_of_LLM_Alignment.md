# PMoL：用于 LLM 对齐偏好混合的高效参数 MoE

发布时间：2024年11月02日

`LLM应用` `语言模型`

> PMoL: Parameter Efficient MoE for Preference Mixing of LLM Alignment

# 摘要

> 强化学习从人类反馈（RLHF）已被证实是大型语言模型（LLMs）偏好对齐的有效手段，在LLMs的后训练流程中广泛应用。但RLHF在应对多个相互竞争的偏好时颇为棘手，致使LLMs与人类偏好的对齐程度降低。为化解此难题，我们从模型架构视角提出了LoRAs的偏好混合（PMoL），它能够适应任意数量的偏好进行融合。PMoL融合了专家混合（MoE）和低秩适配器（LoRA）。此架构创新地应用于偏好对齐的研究，且实现了显著的性能提升。通过采用专家组软损失，赋予了MoE混合偏好的能力。经由奖励模型和GPT-4o的全面评估，实验结果显示，相较于基线方法，PMoL具备更出色的偏好混合能力，且以更低的训练成本达成了更优的偏好对齐。

> Reinforcement Learning from Human Feedback (RLHF) has been proven to be an effective method for preference alignment of large language models (LLMs) and is widely used in the post-training process of LLMs. However, RLHF struggles with handling multiple competing preferences. This leads to a decrease in the alignment of LLMs with human preferences. To address this issue, we propose Preference Mixture of LoRAs (PMoL) from the perspective of model architecture, which can adapt to any number of preferences to mix. PMoL combines Mixture of Experts (MoE) and Low Rank Adaptor (LoRA). This architecture is innovatively applied to the research of preference alignment and has achieved significant performance improvement. The expert group soft loss is used to enable MoE with the ability to mix preferences. Through comprehensive evaluation by the reward model and GPT-4o, the experiment results show that PMoL has superior preference mixing capabilities compared to baseline methods. PMoL achieves better preference alignment with lower training costs.

[Arxiv](https://arxiv.org/abs/2411.01245)