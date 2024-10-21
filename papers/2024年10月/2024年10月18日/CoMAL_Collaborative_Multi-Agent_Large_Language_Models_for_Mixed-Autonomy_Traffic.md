# CoMAL：混合自主交通中的协作多智能体大型语言模型

发布时间：2024年10月18日

`Agent` `自动驾驶`

> CoMAL: Collaborative Multi-Agent Large Language Models for Mixed-Autonomy Traffic

# 摘要

> 自主车辆融入城市交通，有望通过减少拥堵和系统优化交通流量，大幅提升效率。本文介绍的 CoMAL（协作多智能体 LLM）框架，正是为解决混合自主交通问题而生。CoMAL 依托大型语言模型，在交互式交通模拟环境中运作，通过感知模块观察环境，记忆模块存储策略。其核心流程包括协作模块，促进车辆间策略讨论与角色分配；推理引擎，根据角色确定最佳行为；执行模块，结合规则模型控制车辆动作。实验显示，CoMAL 在 Flow 基准测试中表现卓越。我们还评估了不同语言模型的影响，并与强化学习方法对比，凸显了 LLM 智能体的强大协作能力，为混合自主交通挑战提供了有前景的解决方案。代码已公开，详见 https://github.com/Hyan-Yao/CoMAL。

> The integration of autonomous vehicles into urban traffic has great potential to improve efficiency by reducing congestion and optimizing traffic flow systematically. In this paper, we introduce CoMAL (Collaborative Multi-Agent LLMs), a framework designed to address the mixed-autonomy traffic problem by collaboration among autonomous vehicles to optimize traffic flow. CoMAL is built upon large language models, operating in an interactive traffic simulation environment. It utilizes a Perception Module to observe surrounding agents and a Memory Module to store strategies for each agent. The overall workflow includes a Collaboration Module that encourages autonomous vehicles to discuss the effective strategy and allocate roles, a reasoning engine to determine optimal behaviors based on assigned roles, and an Execution Module that controls vehicle actions using a hybrid approach combining rule-based models. Experimental results demonstrate that CoMAL achieves superior performance on the Flow benchmark. Additionally, we evaluate the impact of different language models and compare our framework with reinforcement learning approaches. It highlights the strong cooperative capability of LLM agents and presents a promising solution to the mixed-autonomy traffic challenge. The code is available at https://github.com/Hyan-Yao/CoMAL.

[Arxiv](https://arxiv.org/abs/2410.14368)