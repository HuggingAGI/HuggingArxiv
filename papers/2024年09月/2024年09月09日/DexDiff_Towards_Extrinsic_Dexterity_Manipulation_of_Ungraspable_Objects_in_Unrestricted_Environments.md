# DexDiff：探索在无限制环境中对不可抓取物体的灵巧操控

发布时间：2024年09月09日

`Agent` `机器人` `制造业`

> DexDiff: Towards Extrinsic Dexterity Manipulation of Ungraspable Objects in Unrestricted Environments

# 摘要

> 抓取大型扁平物体（如书或平底锅）常被视为难题，因抓取姿势难以实现。以往方法依赖墙壁或桌边等外部灵巧性，但仅限于特定任务，缺乏预抓取条件规划，难以适应多样环境。为此，我们推出 DexDiff，一种结合外部灵巧性的长期规划机器人操作方法。通过视觉语言模型感知环境并生成高级任务计划，再由目标条件动作扩散模型预测低级动作序列。该模型以高级规划引导的累积奖励为条件，从离线数据中学习低级策略，提升动作预测。实验显示，DexDiff 不仅高效完成不可抓取任务，还能泛化至新物体，模拟中成功率提升 47%，并优化现实场景中的部署与操作。

> Grasping large and flat objects (e.g. a book or a pan) is often regarded as an ungraspable task, which poses significant challenges due to the unreachable grasping poses. Previous works leverage Extrinsic Dexterity like walls or table edges to grasp such objects. However, they are limited to task-specific policies and lack task planning to find pre-grasp conditions. This makes it difficult to adapt to various environments and extrinsic dexterity constraints. Therefore, we present DexDiff, a robust robotic manipulation method for long-horizon planning with extrinsic dexterity. Specifically, we utilize a vision-language model (VLM) to perceive the environmental state and generate high-level task plans, followed by a goal-conditioned action diffusion (GCAD) model to predict the sequence of low-level actions. This model learns the low-level policy from offline data with the cumulative reward guided by high-level planning as the goal condition, which allows for improved prediction of robot actions. Experimental results demonstrate that our method not only effectively performs ungraspable tasks but also generalizes to previously unseen objects. It outperforms baselines by a 47% higher success rate in simulation and facilitates efficient deployment and manipulation in real-world scenarios.

[Arxiv](https://arxiv.org/abs/2409.05493)