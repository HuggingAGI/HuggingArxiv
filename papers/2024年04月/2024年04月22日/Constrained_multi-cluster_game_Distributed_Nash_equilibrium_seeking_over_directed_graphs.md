# 受限多集群博弈：在有向图上寻找分布式纳什均衡

发布时间：2024年04月22日

`Agent` `能源管理` `分布式算法`

> Constrained multi-cluster game: Distributed Nash equilibrium seeking over directed graphs

# 摘要

> 受网络化代理系统中的合作与竞争互动的复杂性启发，多集群博弈为模拟自利代理集群的互联目标提供了建模框架。然而，现有研究在提供全面考虑约束集和有向通信网络的梯度基解决方案方面存在不足，这两者对于实际应用极为关键。为填补这一空白，本文提出了一种分布式纳什均衡搜索算法，该算法融合了基于共识的方法与梯度追踪技术，其中集群间的通信采用行随机权重矩阵，集群内的通信则使用列随机权重矩阵。为应对约束挑战，引入了一种平均化过程，有效解决了投影相关的复杂问题。我们的算法展示了线性收敛性，重点分析了最优性差距的收缩特性。通过微电网能源管理的应用案例，验证了所提算法的高效性。

> Motivated by the complex dynamics of cooperative and competitive interactions within networked agent systems, multi-cluster games provide a framework for modeling the interconnected goals of self-interested clusters of agents. For this setup, the existing literature lacks comprehensive gradient-based solutions that simultaneously consider constraint sets and directed communication networks, both of which are crucial for many practical applications. To address this gap, this paper proposes a distributed Nash equilibrium seeking algorithm that integrates consensus-based methods and gradient-tracking techniques, where inter-cluster and intra-cluster communications only use row- and column-stochastic weight matrices, respectively. To handle constraints, we introduce an averaging procedure, which can effectively address the complications associated with projections. In turn, we can show linear convergence of our algorithm, focusing on the contraction property of the optimality gap. We demonstrate the efficacy of the proposed algorithm through a microgrid energy management application.

[Arxiv](https://arxiv.org/abs/2404.14554)