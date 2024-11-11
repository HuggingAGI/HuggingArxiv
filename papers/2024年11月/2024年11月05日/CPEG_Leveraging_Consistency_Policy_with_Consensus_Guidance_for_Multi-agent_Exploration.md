# CPEG：利用具有共识指导的一致性策略进行多智能体探索

发布时间：2024年11月05日

`Agent` `多智能体`

> CPEG: Leveraging Consistency Policy with Consensus Guidance for Multi-agent Exploration

# 摘要

> 在合作多智能体强化学习（MARL）中，高效探索至关重要，尤其是在稀疏奖励设置中。然而，由于依赖单峰策略，现有方法容易陷入局部最优，阻碍了对更好策略的有效探索。此外，在复杂环境中处理多智能体任务需要在探索过程中进行合作，这给 MARL 方法带来了巨大挑战。为了解决这些问题，我们提出了一种具有共识指导的一致性策略（CPEG），它有两个主要组成部分：（a）引入多模态策略以增强探索能力，（b）在智能体之间共享共识以促进智能体合作。对于组件（a），CPEG 将一致性模型作为策略，利用其多模态性质和随机特征来促进探索。关于组件（b），CPEG 引入了一个共识学习者，从局部观察中推断出对全局状态的共识。然后，这个共识作为一致性策略的指导，促进智能体之间的合作。所提出的方法在多智能体粒子环境（MPE）和多智能体 MuJoCo（MAMuJoCo）中进行了评估，实证结果表明，CPEG 不仅在稀疏奖励设置中实现了改进，而且在密集奖励环境中也达到了基线的性能。

> Efficient exploration is crucial in cooperative multi-agent reinforcement learning (MARL), especially in sparse-reward settings. However, due to the reliance on the unimodal policy, existing methods are prone to falling into the local optima, hindering the effective exploration of better policies. Furthermore, tackling multi-agent tasks in complex environments requires cooperation during exploration, posing substantial challenges for MARL methods. To address these issues, we propose a Consistency Policy with consEnsus Guidance (CPEG), with two primary components: (a) introducing a multimodal policy to enhance exploration capabilities, and (b) sharing the consensus among agents to foster agent cooperation. For component (a), CPEG incorporates a Consistency model as the policy, leveraging its multimodal nature and stochastic characteristics to facilitate exploration. Regarding component (b), CPEG introduces a Consensus Learner to deduce the consensus on the global state from local observations. This consensus then serves as a guidance for the Consistency Policy, promoting cooperation among agents. The proposed method is evaluated in multi-agent particle environments (MPE) and multi-agent MuJoCo (MAMuJoCo), and empirical results indicate that CPEG not only achieves improvements in sparse-reward settings but also matches the performance of baselines in dense-reward environments.

[Arxiv](https://arxiv.org/abs/2411.03603)