# 多房间环境下物体重新排列的任务规划

发布时间：2024年06月01日

`Agent

这篇论文主要关注的是在多房间环境中，通过分层任务规划器来优化代理（Agent）的移动距离和简化步骤，以实现物体重新排列的目标。论文中提到的技术包括利用大型语言模型的常识知识、交叉熵方法、有向空间图和深度强化学习等，这些都是为了构建一个高效的规划器，以帮助代理在未知环境中发现物体并进行整理。因此，这篇论文更符合Agent分类，因为它主要探讨了如何通过智能规划和学习来增强代理在特定任务中的表现。` `家居自动化` `机器人技术`

> Task Planning for Object Rearrangement in Multi-room Environments

# 摘要

> 在多房间环境中，物体重新排列需要一个既能减少代理移动距离又能简化步骤的合理计划。然而，现有技术因依赖于显式探索未知物体和启发式规划动作序列而未能达成此目标。本文创新性地提出了一种分层任务规划器，它通过一系列高效动作，既能发现未知物体，又能整理杂乱家居至理想状态。该方法包含多项创新技术：利用大型语言模型的常识知识发现未知物体、采用交叉熵方法解决碰撞并预测缓冲、构建有向空间图以增强状态空间的可扩展性，以及运用深度强化学习生成高效规划器。规划器巧妙地结合了发现与重新排列过程，以最小化步骤和移动距离。此外，本文还引入了新的评估指标和名为MoPOR的基准数据集，以验证多房间重新排列规划的效果。实验证明，该方法在解决多房间重新排列问题上表现出色。

> Object rearrangement in a multi-room setup should produce a reasonable plan that reduces the agent's overall travel and the number of steps. Recent state-of-the-art methods fail to produce such plans because they rely on explicit exploration for discovering unseen objects due to partial observability and a heuristic planner to sequence the actions for rearrangement. This paper proposes a novel hierarchical task planner to efficiently plan a sequence of actions to discover unseen objects and rearrange misplaced objects within an untidy house to achieve a desired tidy state. The proposed method introduces several novel techniques, including (i) a method for discovering unseen objects using commonsense knowledge from large language models, (ii) a collision resolution and buffer prediction method based on Cross-Entropy Method to handle blocked goal and swap cases, (iii) a directed spatial graph-based state space for scalability, and (iv) deep reinforcement learning (RL) for producing an efficient planner. The planner interleaves the discovery of unseen objects and rearrangement to minimize the number of steps taken and overall traversal of the agent. The paper also presents new metrics and a benchmark dataset called MoPOR to evaluate the effectiveness of the rearrangement planning in a multi-room setting. The experimental results demonstrate that the proposed method effectively addresses the multi-room rearrangement problem.

![多房间环境下物体重新排列的任务规划](../../../paper_images/2406.00451/graph.png)

![多房间环境下物体重新排列的任务规划](../../../paper_images/2406.00451/x1.png)

![多房间环境下物体重新排列的任务规划](../../../paper_images/2406.00451/x2.png)

[Arxiv](https://arxiv.org/abs/2406.00451)