# 本文提出了一种分布式矩阵铅笔公式，用于解决多智能体系统（MASs）在未知传感器灵敏度条件下，实现预定时间领导者-跟随者共识的问题。

发布时间：2024年04月25日

`分类：Agent` `机器人技术` `控制系统`

> Distributed Matrix Pencil Formulations for Prescribed-Time Leader-Following Consensus of MASs with Unknown Sensor Sensitivity

# 摘要

> 本文探讨了在未知传感器灵敏度条件下，异构多智能体系统（MASs）实现预定时间领导者-跟随者共识的问题。我们提出了一个时变双观测器/控制器设计框架，该框架在无向连接拓扑下，通过常规局部和不完全反馈实现预定时间内的共识追踪。这一框架特别适用于装备了不同灵敏度传感器的MASs。设计上的创新包括基于最坏情况传感器构建分布式矩阵铅笔公式，以获得既足够鲁棒又不太保守的控制参数。控制增益的构建也是一个亮点，它由矩阵铅笔公式得到的比例系数与一个趋向无穷大的经典时变函数或一个新颖的有界时变函数相乘而成。此外，通过引入有界时变增益技术，我们可以在不损失最终控制精度的前提下，将预定时间分布式协议扩展到无限时间域，技术证明也十分全面。通过5个单连杆机器人操纵器的实验，验证了该方法的有效性。

> In this paper, we address the problem of prescribed-time leader-following consensus of heterogeneous multi-agent systems (MASs) in the presence of unknown sensor sensitivity. Under a connected undirected topology, we propose a time-varying dual observer/controller design framework that makes use of regular local and inaccurate feedback to achieve consensus tracking within a prescribed time. In particular, the developed analysis framework is applicable to MASs equipped with sensors of different sensitivities. One of the design innovations involves constructing a distributed matrix pencil formulation based on worst-case sensors, yielding control parameters with sufficient robustness yet relatively low conservatism. Another novelty is the construction of the control gains, which consists of the product of a proportional coefficient obtained from the matrix pencil formulation and a classic time-varying function that grows to infinity or a novel bounded time-varying function. Furthermore, it is possible to extend the prescribed-time distributed protocol to infinite time domain by introducing the bounded time-varying gain technique without sacrificing the ultimate control accuracy, and the corresponding technical proof is comprehensive. The effectiveness of the method is demonstrated through a group of 5 single-link robot manipulators.

[Arxiv](https://arxiv.org/abs/2404.16412)