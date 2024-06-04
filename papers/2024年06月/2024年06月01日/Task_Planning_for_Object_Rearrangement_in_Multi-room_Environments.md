# 多房间环境下物体重新排列的任务规划

发布时间：2024年06月01日

`Agent

这篇论文主要关注的是在多房间环境中进行物体重新排列的代理规划问题。它提出了一种新的分层任务规划器，该规划器利用大型语言模型的常识知识来发现未见物体，并通过交叉熵方法解决碰撞和预测缓冲，同时采用有向空间图和深度强化学习来优化规划。这种方法旨在减少代理的移动距离和步骤数，并通过新的评估指标和MoPOR数据集来验证其效果。因此，这篇论文更符合Agent分类，因为它主要探讨的是如何通过智能代理来优化任务规划和执行。` `机器人技术` `智能家居`

> Task Planning for Object Rearrangement in Multi-room Environments

# 摘要

> 在多房间环境中进行物体重新排列时，理想的计划应能减少代理的移动距离和步骤数。然而，现有技术因依赖显式探索和启发式规划而未能达成此目标。本文提出了一种创新的分层任务规划器，它利用大型语言模型的常识知识来发现未见物体，并通过交叉熵方法解决碰撞和预测缓冲，同时采用有向空间图和深度强化学习来优化规划。该规划器通过交替发现未见物体和重新排列，有效减少了步骤和移动距离。此外，本文还引入了新的评估指标和MoPOR数据集，以验证在多房间环境中重新排列规划的效果。实验证明，这一方法能有效解决多房间的重新排列问题。

> Object rearrangement in a multi-room setup should produce a reasonable plan that reduces the agent's overall travel and the number of steps. Recent state-of-the-art methods fail to produce such plans because they rely on explicit exploration for discovering unseen objects due to partial observability and a heuristic planner to sequence the actions for rearrangement. This paper proposes a novel hierarchical task planner to efficiently plan a sequence of actions to discover unseen objects and rearrange misplaced objects within an untidy house to achieve a desired tidy state. The proposed method introduces several novel techniques, including (i) a method for discovering unseen objects using commonsense knowledge from large language models, (ii) a collision resolution and buffer prediction method based on Cross-Entropy Method to handle blocked goal and swap cases, (iii) a directed spatial graph-based state space for scalability, and (iv) deep reinforcement learning (RL) for producing an efficient planner. The planner interleaves the discovery of unseen objects and rearrangement to minimize the number of steps taken and overall traversal of the agent. The paper also presents new metrics and a benchmark dataset called MoPOR to evaluate the effectiveness of the rearrangement planning in a multi-room setting. The experimental results demonstrate that the proposed method effectively addresses the multi-room rearrangement problem.

![多房间环境下物体重新排列的任务规划](../../../paper_images/2406.00451/graph.png)

![多房间环境下物体重新排列的任务规划](../../../paper_images/2406.00451/x1.png)

![多房间环境下物体重新排列的任务规划](../../../paper_images/2406.00451/x2.png)

[Arxiv](https://arxiv.org/abs/2406.00451)