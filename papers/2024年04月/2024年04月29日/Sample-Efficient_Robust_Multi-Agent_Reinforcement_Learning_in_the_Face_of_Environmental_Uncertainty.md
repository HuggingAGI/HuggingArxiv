# 面对环境的不确定性，本研究提出了一种样本高效且鲁棒的多智能体强化学习方法。

发布时间：2024年04月29日

`分类：Agent` `多智能体系统`

> Sample-Efficient Robust Multi-Agent Reinforcement Learning in the Face of Environmental Uncertainty

# 摘要

> 为了弥合强化学习中的仿真与现实之间的鸿沟，所学习到的策略必须对环境的不确定性具有鲁棒性。尽管在单一智能体情境下，鲁棒性强化学习已受到广泛关注，但在多智能体情境中，这一问题尚未得到充分研究，尤其是在环境不确定性因策略互动而加剧的情况下。本研究着眼于分布鲁棒马尔可夫博弈（RMGs）的学习，这是一种鲁棒性增强的马尔可夫博弈，每个智能体都旨在学习一种策略，以确保在部署环境在其预设的不确定性范围内发生偏离时，自身的最坏情况性能达到最大化。这将形成一套与经典博弈论均衡理念相符的鲁棒均衡策略。在假设生成模型采用非自适应抽样机制的前提下，我们提出了一种样本高效的基于模型算法（DRNVI），并为学习不同博弈论均衡概念的鲁棒变体提供了有限样本复杂度的保证。此外，我们还建立了解决RMGs的信息论下界，证实了DRNVI在样本复杂度上接近最优，这与问题依赖因素（如状态空间大小、目标精度和时间范围）有关。

> To overcome the sim-to-real gap in reinforcement learning (RL), learned policies must maintain robustness against environmental uncertainties. While robust RL has been widely studied in single-agent regimes, in multi-agent environments, the problem remains understudied -- despite the fact that the problems posed by environmental uncertainties are often exacerbated by strategic interactions. This work focuses on learning in distributionally robust Markov games (RMGs), a robust variant of standard Markov games, wherein each agent aims to learn a policy that maximizes its own worst-case performance when the deployed environment deviates within its own prescribed uncertainty set. This results in a set of robust equilibrium strategies for all agents that align with classic notions of game-theoretic equilibria. Assuming a non-adaptive sampling mechanism from a generative model, we propose a sample-efficient model-based algorithm (DRNVI) with finite-sample complexity guarantees for learning robust variants of various notions of game-theoretic equilibria. We also establish an information-theoretic lower bound for solving RMGs, which confirms the near-optimal sample complexity of DRNVI with respect to problem-dependent factors such as the size of the state space, the target accuracy, and the horizon length.

[Arxiv](https://arxiv.org/abs/2404.18909)