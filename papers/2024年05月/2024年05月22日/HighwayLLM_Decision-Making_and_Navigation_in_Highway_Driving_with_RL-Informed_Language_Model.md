# HighwayLLM：借助强化学习启发的语言模型，实现高速公路驾驶中的智能决策与导航

发布时间：2024年05月22日

`Agent

理由：这篇论文主要描述了一个名为 HighwayLLM 的方法，该方法结合了大型语言模型（LLMs）、强化学习（RL）和 PID 控制器来优化自动驾驶车辆的决策和控制过程。这种方法特别强调了使用 LLMs 来预测车辆的未来导航航点，并利用 RL 模型进行高级策略规划。因此，这个方法可以被视为一个智能代理（Agent），它能够根据实时状态信息做出决策并控制车辆的行为。虽然这种方法涉及到了 LLM 的应用，但其核心在于构建一个能够自主决策和执行的系统，因此更适合归类为Agent。` `自动驾驶` `交通管理`

> HighwayLLM: Decision-Making and Navigation in Highway Driving with RL-Informed Language Model

# 摘要

> 自动驾驶技术复杂，需精妙算法支撑决策与控制。理解自动驾驶车辆决策的逻辑，对确保其在高速公路上的安全与效率至关重要。本研究创新性地提出了 HighwayLLM 方法，该方法借助大型语言模型（LLMs）的强大推理能力，精准预测自车的未来导航航点。同时，我们采用预训练的强化学习（RL）模型作为高级策略规划，决策元级动作。HighwayLLM 将 RL 模型的策略与实时状态信息融合，确保下一状态的预测既安全又无碰撞，且易于解释，从而为自车绘制出一条精准轨迹。接着，基于 PID 的控制器将车辆引导至 LLM 代理预测的航点。此方法将 LLM、RL 与 PID 巧妙结合，不仅优化了决策流程，更为高速公路自动驾驶带来了透明度与可解释性。

> Autonomous driving is a complex task which requires advanced decision making and control algorithms. Understanding the rationale behind the autonomous vehicles' decision is crucial to ensure their safe and effective operation on highway driving. This study presents a novel approach, HighwayLLM, which harnesses the reasoning capabilities of large language models (LLMs) to predict the future waypoints for ego-vehicle's navigation. Our approach also utilizes a pre-trained Reinforcement Learning (RL) model to serve as a high-level planner, making decisions on appropriate meta-level actions. The HighwayLLM combines the output from the RL model and the current state information to make safe, collision-free, and explainable predictions for the next states, thereby constructing a trajectory for the ego-vehicle. Subsequently, a PID-based controller guides the vehicle to the waypoints predicted by the LLM agent. This integration of LLM with RL and PID enhances the decision-making process and provides interpretability for highway autonomous driving.

[Arxiv](https://arxiv.org/abs/2405.13547)