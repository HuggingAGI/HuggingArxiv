# Imagine-2-Drive：为自动驾驶汽车于 CARLA 中构建高保真世界模型

发布时间：2024年11月15日

`其他` `自动驾驶`

> Imagine-2-Drive: High-Fidelity World Modeling in CARLA for Autonomous Vehicles

# 摘要

> 在基于图像的状态空间的自动驾驶领域，精准预测未来事件以及为多样的行为模式建模，对于保障安全和做出有效决策至关重要。基于世界模型的强化学习（WMRL）方法，通过从当下状态和动作来模拟未来状态，提供了颇具前景的解决方案。然而，世界模型的效用往往受限于典型的 RL 策略，它们多局限于确定性或单高斯分布。由于无法涵盖所有可能的行动，这降低了其在复杂动态环境中的适应性。在本项工作中，我们推出了 Imagine-2-Drive 框架，它由两个部分构成，即 VISTAPlan——一个用于精准预测未来的高保真世界模型，以及 Diffusion Policy Actor（DPA）——一个基于扩散的策略，用于为轨迹预测构建多模态行为模型。我们利用 VISTAPlan 来模拟和评估来自 DPA 的轨迹，并运用去噪扩散策略优化（DDPO）训练 DPA，以在轨迹上实现奖励累积总和的最大化。我们依据标准驾驶指标在 CARLA 中剖析每个组件以及整个框架的优势。得益于我们的两项创新——VISTAPlan 和 DPA，我们在标准驾驶指标上，分别在路线完成率和成功率方面，显著超越了最先进（SOTA）的世界模型 15％和 20％。

> In autonomous driving with image based state space, accurate prediction of future events and modeling diverse behavioral modes are essential for safety and effective decision-making. World model-based Reinforcement Learning (WMRL) approaches offers a promising solution by simulating future states from current state and actions. However, utility of world models is often limited by typical RL policies being limited to deterministic or single gaussian distribution. By failing to capture the full spectrum of possible actions, reduces their adaptability in complex, dynamic environments. In this work, we introduce Imagine-2-Drive, a framework that consists of two components, VISTAPlan, a high-fidelity world model for accurate future prediction and Diffusion Policy Actor (DPA), a diffusion based policy to model multi-modal behaviors for trajectory prediction. We use VISTAPlan to simulate and evaluate trajectories from DPA and use Denoising Diffusion Policy Optimization (DDPO) to train DPA to maximize the cumulative sum of rewards over the trajectories. We analyze the benefits of each component and the framework as a whole in CARLA with standard driving metrics. As a consequence of our twin novelties- VISTAPlan and DPA, we significantly outperform the state of the art (SOTA) world models on standard driving metrics by 15% and 20% on Route Completion and Success Rate respectively.

[Arxiv](https://arxiv.org/abs/2411.10171)