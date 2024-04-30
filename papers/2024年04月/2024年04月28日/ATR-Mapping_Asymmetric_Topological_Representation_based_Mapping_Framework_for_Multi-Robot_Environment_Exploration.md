# ATR-Mapping：一种创新的非对称拓扑表示映射框架，专为多机器人环境探索而设计。

发布时间：2024年04月28日

`Agent` `机器人学` `自动驾驶`

> ATR-Mapping: Asymmetric Topological Representation based Mapping Framework for Multi-Robot Environment Exploration

# 摘要

> 近期，多机器人系统在电力巡查、自动驾驶车队等众多领域的广泛应用，让其成为机器人学界的研究焦点。本研究着眼于多机器人在未知环境中的协作探索问题，提出了一种基于多智能体强化学习的训练框架与决策策略。我们创新性地设计了一种非对称拓扑表示映射框架（ATR-Mapping），它融合了原始网格图方法与拓扑方法的优势，通过从原始网格图中抽取结构信息，并结合基于几何距离构建的拓扑图，以辅助决策制定。依托这一拓扑图表示，我们构建了一个基于拓扑图匹配的决策网络，为每个机器人指定了边界点作为长期决策目标。通过在 Gazebo 和 Gibson 仿真环境中对现实世界场景的测试与应用，证实了我们的方法相较于现有技术在性能上实现了显著提升。

> In recent years, the widespread application of multi-robot systems in areas such as power inspection, autonomous vehicle fleets has made multi-robot technology a research hotspot in the field of robotics. This paper investigates multi-robot cooperative exploration in unknown environments, proposing a training framework and decision strategy based on multi-agent reinforcement learning. Specifically we propose a Asymmetric Topological Representation based mapping framework (ATR-Mapping), combining the advantages of methods based on raw grid maps and methods based on topology, the structural information from the raw grid maps is extracted and combined with a topological graph constructed based on geometric distance information for decision-making. Leveraging this topological graph representation, we employs a decision network based on topological graph matching to assign corresponding boundary points to each robot as long-term target points for decision-making. We conducts testing and application of the proposed algorithms in real world scenarios using the Gazebo and Gibson simulation environments. It validates that the proposed method, when compared to existing methods, achieves a certain degree of performance improvement.

[Arxiv](https://arxiv.org/abs/2404.18089)