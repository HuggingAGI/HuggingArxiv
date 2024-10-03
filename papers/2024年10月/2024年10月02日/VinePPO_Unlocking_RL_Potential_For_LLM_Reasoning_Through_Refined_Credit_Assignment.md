# VinePPO：通过精细的信用分配，释放 LLM 推理中的强化学习潜力。

发布时间：2024年10月02日

`LLM应用` `人工智能`

> VinePPO: Unlocking RL Potential For LLM Reasoning Through Refined Credit Assignment

# 摘要

> 大型语言模型 (LLM) 在复杂推理任务中的应用日益增多，这些任务需要执行多个复杂步骤才能获得奖励。正确分配这些步骤的信用对于提升模型性能至关重要。Proximal Policy Optimization (PPO) 是一种先进的强化学习算法，用于 LLM 微调，它通过价值网络来解决信用分配问题。然而，价值网络在复杂推理任务中预测预期累积奖励时面临挑战，常导致高方差更新和次优性能。我们系统评估了价值网络的有效性，发现它们在推理密集型 LLM 任务中表现不佳，几乎无法超越随机基线。为此，我们提出了 VinePPO，一种利用语言环境灵活性计算无偏蒙特卡罗估计的方法，无需大型价值网络。在 MATH 和 GSM8K 数据集上，VinePPO 持续优于 PPO 和其他无 RL 基线，使用更少的梯度更新和实际时间。这些结果凸显了准确信用分配在 LLM 的 RL 微调中的重要性，并展示了 VinePPO 的优越潜力。

> Large language models (LLMs) are increasingly applied to complex reasoning tasks that require executing several complex steps before receiving any reward. Properly assigning credit to these steps is essential for enhancing model performance. Proximal Policy Optimization (PPO), a state-of-the-art reinforcement learning (RL) algorithm used for LLM finetuning, employs value networks to tackle credit assignment. However, value networks face challenges in predicting the expected cumulative rewards accurately in complex reasoning tasks, often leading to high-variance updates and suboptimal performance. In this work, we systematically evaluate the efficacy of value networks and reveal their significant shortcomings in reasoning-heavy LLM tasks, showing that they barely outperform a random baseline when comparing alternative steps. To address this, we propose VinePPO, a straightforward approach that leverages the flexibility of language environments to compute unbiased Monte Carlo-based estimates, bypassing the need for large value networks. Our method consistently outperforms PPO and other RL-free baselines across MATH and GSM8K datasets with fewer gradient updates (up to 9x), less wall-clock time (up to 3.0x). These results emphasize the importance of accurate credit assignment in RL finetuning of LLM and demonstrate VinePPO's potential as a superior alternative.

[Arxiv](https://arxiv.org/abs/2410.01679)