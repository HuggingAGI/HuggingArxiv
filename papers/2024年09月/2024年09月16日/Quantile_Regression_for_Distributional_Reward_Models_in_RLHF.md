# RLHF 中分布式奖励模型的分位数回归

发布时间：2024年09月16日

`LLM理论` `人工智能`

> Quantile Regression for Distributional Reward Models in RLHF

# 摘要

> 通过奖励模型，从人类反馈中进行强化学习 (RLHF) 已成为使大型语言模型 (LLM) 与人类偏好对齐的关键方法。然而，传统奖励模型生成的点估计过于简化人类价值观和偏好的多样性。为此，我们提出了分位数奖励模型 (QRMs)，通过学习奖励的分布而非单一值，更细致地捕捉偏好。实验表明，QRM 在 RewardBench 上表现优异，并能在下游应用中提供额外价值，如减少风险感知的强化学习中的极端负面响应。相关代码和模型已发布在 https://github.com/Nicolinho/QRM。

> Reinforcement learning from human feedback (RLHF) has become a key method for aligning large language models (LLMs) with human preferences through the use of reward models. However, traditional reward models typically generate point estimates, which oversimplify the diversity and complexity of human values and preferences. In this paper, we introduce Quantile Reward Models (QRMs), a novel approach to reward modeling that learns a distribution over rewards instead of a single scalar value. Our method uses quantile regression to estimate a full, potentially multimodal distribution over preferences, providing a more powerful and nuanced representation of preferences. This distributional approach can better capture the diversity of human values, addresses label noise, and accommodates conflicting preferences by modeling them as distinct modes in the distribution. Our experimental results show that QRM outperforms comparable traditional point-estimate models on RewardBench. Furthermore, we demonstrate that the additional information provided by the distributional estimates can be utilized in downstream applications, such as risk-aware reinforcement learning, resulting in LLM policies that generate fewer extremely negative responses. Our code and model are released at https://github.com/Nicolinho/QRM.

[Arxiv](https://arxiv.org/abs/2409.10164)