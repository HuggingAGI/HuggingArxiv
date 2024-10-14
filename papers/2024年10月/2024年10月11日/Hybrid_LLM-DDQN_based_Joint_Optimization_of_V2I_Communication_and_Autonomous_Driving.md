# 混合 LLM-DDQN 技术助力 V2I 通信与自动驾驶的协同优化

发布时间：2024年10月11日

`LLM应用`

> Hybrid LLM-DDQN based Joint Optimization of V2I Communication and Autonomous Driving

# 摘要

> 大型语言模型 (LLM) 因其卓越的推理和理解能力，近期备受关注。本研究探索将 LLM 应用于车载网络，旨在联合优化车辆与基础设施 (V2I) 通信和自动驾驶 (AD) 策略。我们利用 LLM 进行 AD 决策，以提升交通流量并确保道路安全，同时采用双深度 Q 学习算法 (DDQN) 优化 V2I 通信，提高数据接收速率并减少频繁切换。特别地，对于 LLM 驱动的 AD，我们通过欧几里得距离识别过往的 AD 经验，使 LLM 能从过去的决策中学习并改进。随后，LLM 的 AD 决策融入 V2I 问题的状态中，DDQN 据此优化 V2I 决策。通过迭代优化，直至收敛，这种方法有效探索了 LLM 与传统强化学习技术的互动，展现了 LLM 在网络优化与管理中的潜力。仿真结果显示，我们提出的 LLM-DDQN 混合方法在收敛速度和平均奖励方面均优于传统 DDQN 算法。

> Large language models (LLMs) have received considerable interest recently due to their outstanding reasoning and comprehension capabilities. This work explores applying LLMs to vehicular networks, aiming to jointly optimize vehicle-to-infrastructure (V2I) communications and autonomous driving (AD) policies. We deploy LLMs for AD decision-making to maximize traffic flow and avoid collisions for road safety, and a double deep Q-learning algorithm (DDQN) is used for V2I optimization to maximize the received data rate and reduce frequent handovers. In particular, for LLM-enabled AD, we employ the Euclidean distance to identify previously explored AD experiences, and then LLMs can learn from past good and bad decisions for further improvement. Then, LLM-based AD decisions will become part of states in V2I problems, and DDQN will optimize the V2I decisions accordingly. After that, the AD and V2I decisions are iteratively optimized until convergence. Such an iterative optimization approach can better explore the interactions between LLMs and conventional reinforcement learning techniques, revealing the potential of using LLMs for network optimization and management. Finally, the simulations demonstrate that our proposed hybrid LLM-DDQN approach outperforms the conventional DDQN algorithm, showing faster convergence and higher average rewards.

[Arxiv](https://arxiv.org/abs/2410.08854)