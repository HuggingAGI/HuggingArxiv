# $α$-DPO：自适应奖励边际，正是直接偏好优化所需的关键。

发布时间：2024年10月14日

`LLM理论` `人工智能` `机器学习`

> $α$-DPO: Adaptive Reward Margin is What Direct Preference Optimization Needs

# 摘要

> 将大型语言模型 (LLM) 与人类价值观和意图对齐，对于确保其效用、诚实性和安全性至关重要。尽管从人类反馈中进行强化学习 (RLHF) 是实现这一目标的常用方法，但其计算效率和训练稳定性仍面临挑战。最近，直接偏好优化 (DPO) 和简单偏好优化 (SimPO) 提出了 RLHF 的离线替代方案，通过重新参数化奖励函数简化了过程。然而，DPO 依赖于可能次优的参考模型，而 SimPO 对固定目标奖励边际的假设可能在多样化的数据设置中导致次优决策。为此，我们提出了 $α$-DPO，一种自适应偏好优化算法，通过引入动态奖励边际来解决这些限制。$α$-DPO 采用自适应偏好分布，平衡策略模型和参考模型，以实现个性化的奖励边际。我们为 $α$-DPO 提供了理论保证，证明其作为替代优化目标的有效性，并通过 KL 散度控制实现对齐和多样性的平衡。实证评估显示，$α$-DPO 在各种模型设置下始终优于 DPO 和 SimPO，成为微调 LLM 的稳健方法。我们的方法在胜率上实现了显著提升，展现了其在 LLM 对齐中的强大潜力。代码已开源，详见 https://github.com/junkangwu/alpha-DPO。

> Aligning large language models (LLMs) with human values and intentions is crucial for their utility, honesty, and safety. Reinforcement learning from human feedback (RLHF) is a popular approach to achieve this alignment, but it faces challenges in computational efficiency and training stability. Recent methods like Direct Preference Optimization (DPO) and Simple Preference Optimization (SimPO) have proposed offline alternatives to RLHF, simplifying the process by reparameterizing the reward function. However, DPO depends on a potentially suboptimal reference model, and SimPO's assumption of a fixed target reward margin may lead to suboptimal decisions in diverse data settings. In this work, we propose $α$-DPO, an adaptive preference optimization algorithm designed to address these limitations by introducing a dynamic reward margin. Specifically, $α$-DPO employs an adaptive preference distribution, balancing the policy model and the reference model to achieve personalized reward margins. We provide theoretical guarantees for $α$-DPO, demonstrating its effectiveness as a surrogate optimization objective and its ability to balance alignment and diversity through KL divergence control. Empirical evaluations on AlpacaEval 2 and Arena-Hard show that $α$-DPO consistently outperforms DPO and SimPO across various model settings, establishing it as a robust approach for fine-tuning LLMs. Our method achieves significant improvements in win rates, highlighting its potential as a powerful tool for LLM alignment. The code is available at https://github.com/junkangwu/alpha-DPO

[Arxiv](https://arxiv.org/abs/2410.10148)