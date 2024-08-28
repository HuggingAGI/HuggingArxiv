# Inverse-Q*：一种无需偏好数据即可对齐大型语言模型的令牌级强化学习方法

发布时间：2024年08月27日

`LLM理论` `人工智能` `机器学习`

> Inverse-Q*: Token Level Reinforcement Learning for Aligning Large Language Models Without Preference Data

# 摘要

> 人类反馈强化学习（RLHF）虽有效，但常依赖复杂的PPO方法，需大量超参数调整，且在样本效率和稳定性上存挑战。本文引入创新框架Inverse-Q*，通过优化令牌级强化学习，无需额外奖励或价值模型，超越传统RL方法。Inverse-Q*利用直接偏好优化技术，直接从模型响应中估算条件最优策略，实现更细粒度、灵活的策略塑造，减少对外部监督和人类标注的依赖，特别适合资源有限环境。实验显示，Inverse-Q*在收敛速度和模型响应与人类偏好对齐方面，不仅与PPO相当，甚至可能超越。这为传统RLHF方法提供了实用、稳健的替代方案，推动了更高效、适应性强的模型训练方法的发展。

> Reinforcement Learning from Human Feedback (RLHF) has proven effective in aligning large language models with human intentions, yet it often relies on complex methodologies like Proximal Policy Optimization (PPO) that require extensive hyper-parameter tuning and present challenges in sample efficiency and stability. In this paper, we introduce Inverse-Q*, an innovative framework that transcends traditional RL methods by optimizing token-level reinforcement learning without the need for additional reward or value models. Inverse-Q* leverages direct preference optimization techniques but extends them by estimating the conditionally optimal policy directly from the model's responses, facilitating more granular and flexible policy shaping. Our approach reduces reliance on human annotation and external supervision, making it especially suitable for low-resource settings. We present extensive experimental results demonstrating that Inverse-Q* not only matches but potentially exceeds the effectiveness of PPO in terms of convergence speed and the alignment of model responses with human preferences. Our findings suggest that Inverse-Q* offers a practical and robust alternative to conventional RLHF approaches, paving the way for more efficient and adaptable model training approaches.

[Arxiv](https://arxiv.org/abs/2408.14874)