# 探索将终身多智能体路径规划技术应用于更贴近现实场景的可能性：面临的研究挑战与机遇并存。

发布时间：2024年04月24日

`Agent` `机器人技术` `智能交通系统`

> Scaling Lifelong Multi-Agent Path Finding to More Realistic Settings: Research Challenges and Opportunities

# 摘要

> 多智能体路径规划（MAPF）旨在解决多个智能体从起点到终点的无碰撞移动问题。终身MAPF（LMAPF）进一步发展，通过不断为智能体设定新目标。本文介绍了我们在2023年机器人跑者联盟LMAPF竞赛中的获胜策略，该策略引发了若干研究挑战和未来研究的新方向。我们首先指出了三大研究难题：第一，如何在有限的规划时间内（如每秒一步）为成千上万的智能体或极高密度的智能体群体（如密度达97.7%）寻找优质的LMAPF解决方案；第二，如何缓解LMAPF算法中的拥堵问题及短视行为的影响；第三，如何缩小文献中的LMAPF模型与现实世界应用之间的差异。针对这些挑战，我们提出了未来研究的方向，包括开发更具竞争力的基于规则和即时MAPF算法，实现现有MAPF算法的并行化，制定动态引导和交通规则以减少拥堵，整合预测未来和实时搜索的技术，以及确定最优智能体数量。同时，我们还考虑了如何处理更真实的运动学模型、执行不确定性和动态系统等问题。

> Multi-Agent Path Finding (MAPF) is the problem of moving multiple agents from starts to goals without collisions. Lifelong MAPF (LMAPF) extends MAPF by continuously assigning new goals to agents. We present our winning approach to the 2023 League of Robot Runners LMAPF competition, which leads us to several interesting research challenges and future directions. In this paper, we outline three main research challenges. The first challenge is to search for high-quality LMAPF solutions within a limited planning time (e.g., 1s per step) for a large number of agents (e.g., 10,000) or extremely high agent density (e.g., 97.7%). We present future directions such as developing more competitive rule-based and anytime MAPF algorithms and parallelizing state-of-the-art MAPF algorithms. The second challenge is to alleviate congestion and the effect of myopic behaviors in LMAPF algorithms. We present future directions, such as developing moving guidance and traffic rules to reduce congestion, incorporating future prediction and real-time search, and determining the optimal agent number. The third challenge is to bridge the gaps between the LMAPF models used in the literature and real-world applications. We present future directions, such as dealing with more realistic kinodynamic models, execution uncertainty, and evolving systems.

[Arxiv](https://arxiv.org/abs/2404.16162)