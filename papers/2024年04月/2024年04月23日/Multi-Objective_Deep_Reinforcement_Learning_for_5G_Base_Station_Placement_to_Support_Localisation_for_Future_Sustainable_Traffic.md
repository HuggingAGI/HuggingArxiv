# 采用多目标深度强化学习方法，优化5G基站布局，以支持未来交通的可持续发展和精确定位。

发布时间：2024年04月23日

`Agent` `交通系统` `通信技术`

> Multi-Objective Deep Reinforcement Learning for 5G Base Station Placement to Support Localisation for Future Sustainable Traffic

# 摘要

> 毫米波通信技术在推动未来交通系统的发展中扮演着至关重要的角色。但在城市场景中，它极易受到遮挡和阴影效应的影响。因此，精心规划基站的布局，以满足覆盖需求并辅助定位功能，成为了基础设施设计中的一个关键环节。本研究在已有基站的基础上，探讨了如何利用深度强化学习方法，进一步部署一个新的基站以提升城市环境中的定位精度和信号覆盖。研究提出了一种三层网格状态表示法，作为深度强化学习模型的输入，使其能够灵活应对无线环境的变化。同时，设计了一个合适的奖励函数，以解决多目标优化问题。通过数值分析，证实了所提出的深度Q网络模型能够有效适应复杂多变的无线电环境，并与穷举搜索方法相比，提供了同样高效或类似的解决方案。此外，研究还发现，单纯追求覆盖率的优化并不能提升定位精度，从而揭示了两者之间存在的权衡关系。

> Millimeter-wave (mmWave) is a key enabler for next-generation transportation systems. However, in an urban city scenario, mmWave is highly susceptible to blockages and shadowing. Therefore, base station (BS) placement is a crucial task in the infrastructure design where coverage requirements need to be met while simultaneously supporting localisation. This work assumes a pre-deployed BS and another BS is required to be added to support both localisation accuracy and coverage rate in an urban city scenario. To solve this complex multi-objective optimisation problem, we utilise deep reinforcement learning (DRL). Concretely, this work proposes: 1) a three-layered grid for state representation as the input of the DRL, which enables it to adapt to the changes in the wireless environment represented by changing the position of the pre-deployed BS, and 2) the design of a suitable reward function for the DRL agent to solve the multi-objective problem. Numerical analysis shows that the proposed deep Q-network (DQN) model can learn/adapt from the complex radio environment represented by the terrain map and provides the same/similar solution to the exhaustive search, which is used as a benchmark. In addition, we show that an exclusive optimisation of coverage rate does not result in improved localisation accuracy, and thus there is a trade-off between the two solutions.

[Arxiv](https://arxiv.org/abs/2404.14954)