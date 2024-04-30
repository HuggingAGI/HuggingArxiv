# Bi-CL：一种采用双层优化策略的强化学习框架，旨在提升机器人间的协调能力。

发布时间：2024年04月22日

`Agent` `机器人技术` `多智能体系统`

> Bi-CL: A Reinforcement Learning Framework for Robots Coordination Through Bi-level Optimization

# 摘要

> 在多机器人系统中，协调任务的实现因行为的相互依赖和机器人缺少全局信息而面临重大挑战。为应对这些难题，本研究提出了一种创新的双层次协调学习（Bi-CL）方法，该方法采用集中式训练与分布式执行的双重优化架构。我们的双重层次重构策略将原始问题拆分为简化动作空间的强化学习层和从全局优化器获取示范的模仿学习层，两者共同提升了学习效率和系统的可扩展性。我们指出，由于机器人信息的不完整性，学习模型的两个层次之间存在差异。为此，Bi-CL引入了对齐惩罚机制，以减少层次间差异，同时保持训练效率。我们通过一个运行实例来阐释问题设定，并将Bi-CL应用于该实例的两种情形：基于路径和基于图的场景。模拟结果显示，Bi-CL不仅学习效率更高，而且在多机器人协调任务中与传统的多智能体强化学习方法相比，性能毫不逊色。

> In multi-robot systems, achieving coordinated missions remains a significant challenge due to the coupled nature of coordination behaviors and the lack of global information for individual robots. To mitigate these challenges, this paper introduces a novel approach, Bi-level Coordination Learning (Bi-CL), that leverages a bi-level optimization structure within a centralized training and decentralized execution paradigm. Our bi-level reformulation decomposes the original problem into a reinforcement learning level with reduced action space, and an imitation learning level that gains demonstrations from a global optimizer. Both levels contribute to improved learning efficiency and scalability. We note that robots' incomplete information leads to mismatches between the two levels of learning models. To address this, Bi-CL further integrates an alignment penalty mechanism, aiming to minimize the discrepancy between the two levels without degrading their training efficiency. We introduce a running example to conceptualize the problem formulation and apply Bi-CL to two variations of this example: route-based and graph-based scenarios. Simulation results demonstrate that Bi-CL can learn more efficiently and achieve comparable performance with traditional multi-agent reinforcement learning baselines for multi-robot coordination.

[Arxiv](https://arxiv.org/abs/2404.14649)