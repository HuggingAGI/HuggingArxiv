# 探索最优与有界次优的多智能体任意角度路径规划

发布时间：2024年04月25日

`Agent` `机器人技术` `路径规划`

> Optimal and Bounded Suboptimal Any-Angle Multi-agent Pathfinding

# 摘要

> 多智能体路径规划（MAPF）旨在为一群智能体规划出互不冲突的路径集合。在这一问题中，智能体的行动通常限制在预设的、包含可能位置和它们之间允许转换的图上，例如4邻接网格。本研究探讨了在智能体能够在任意两个可能位置间移动而不与障碍物发生碰撞的情况下，如何进行MAPF问题的求解，这被称作任意角度路径规划。我们首次提出了一个最优的任意角度多智能体路径规划算法，该算法基于连续冲突搜索（CCBS）算法和安全间隔路径规划（TO-AA-SIPP）的最优任意角度变种。然而，这两种算法的直接结合在扩展性上表现不佳，因为任意角度路径规划会导致搜索树的分支因子极大。为了解决这个问题，我们从传统MAPF中借鉴了两种技术，并将其适配到任意角度路径规划中，分别是不相交分割和多约束技术。实验结果显示，这些技术的结合使用能够比CCBS和TO-AA-SIPP的标准组合多解决超过30%的问题。此外，我们还提出了算法的一个有界次优变体，它允许在运行时间和解决方案成本之间进行可控的权衡。

> Multi-agent pathfinding (MAPF) is the problem of finding a set of conflict-free paths for a set of agents. Typically, the agents' moves are limited to a pre-defined graph of possible locations and allowed transitions between them, e.g. a 4-neighborhood grid. We explore how to solve MAPF problems when each agent can move between any pair of possible locations as long as traversing the line segment connecting them does not lead to the collision with the obstacles. This is known as any-angle pathfinding. We present the first optimal any-angle multi-agent pathfinding algorithm. Our planner is based on the Continuous Conflict-based Search (CCBS) algorithm and an optimal any-angle variant of the Safe Interval Path Planning (TO-AA-SIPP). The straightforward combination of those, however, scales poorly since any-angle path finding induces search trees with a very large branching factor. To mitigate this, we adapt two techniques from classical MAPF to the any-angle setting, namely Disjoint Splitting and Multi-Constraints. Experimental results on different combinations of these techniques show they enable solving over 30% more problems than the vanilla combination of CCBS and TO-AA-SIPP. In addition, we present a bounded-suboptimal variant of our algorithm, that enables trading runtime for solution cost in a controlled manner.

[Arxiv](https://arxiv.org/abs/2404.16379)