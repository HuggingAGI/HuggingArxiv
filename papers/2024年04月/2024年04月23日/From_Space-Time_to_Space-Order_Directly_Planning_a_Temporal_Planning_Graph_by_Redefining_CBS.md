# 由时空转至时序：重新定义 CBS 以直接构建时间规划图。

发布时间：2024年04月23日

`Agent` `机器人技术` `人工智能`

> From Space-Time to Space-Order: Directly Planning a Temporal Planning Graph by Redefining CBS

# 摘要

> 多智能体路径规划（MAPF）的主流方法旨在计算出避免碰撞的空间-时间路径，规定智能体需在特定时间点位于特定位置。但这些路径直接应用于机器人系统并不现实，因为实时执行中的各种差异（如延迟）可能引发碰撞。为解决这一问题，现有技术将这些路径转化为时间规划图（TPG），智能体只需遵循它们通过交叉点的顺序。不过，这种先将路径规划出来再转换成TPG的做法，并未能简化智能体间的协调需求。针对这一点，我们提出了一种创新算法——Space-Order CBS，它能够直接规划出TPG，并且有效减少所需的协调。我们的创新之处在于重新定义了TPG，将其视为一系列空间访问顺序路径，智能体根据相对顺序而非固定时间点来访问位置。我们为适应空间顺序规划重新定义了冲突和约束。实验结果表明，Space-Order CBS能够生成TPG，显著降低智能体间的协调需求，减少通信量，并提高对执行过程中延迟的适应性。

> The majority of multi-agent path finding (MAPF) methods compute collision-free space-time paths which require agents to be at a specific location at a specific discretized timestep. However, executing these space-time paths directly on robotic systems is infeasible due to real-time execution differences (e.g. delays) which can lead to collisions. To combat this, current methods translate the space-time paths into a temporal plan graph (TPG) that only requires that agents observe the order in which they navigate through locations where their paths cross. However, planning space-time paths and then post-processing them into a TPG does not reduce the required agent-to-agent coordination, which is fixed once the space-time paths are computed. To that end, we propose a novel algorithm Space-Order CBS that can directly plan a TPG and explicitly minimize coordination. Our main theoretical insight is our novel perspective on viewing a TPG as a set of space-visitation order paths where agents visit locations in relative orders (e.g. 1st vs 2nd) as opposed to specific timesteps. We redefine unique conflicts and constraints for adapting CBS for space-order planning. We experimentally validate how Space-Order CBS can return TPGs which significantly reduce coordination, thus subsequently reducing the amount of agent-agent communication and leading to more robustness to delays during execution.

[Arxiv](https://arxiv.org/abs/2404.15137)