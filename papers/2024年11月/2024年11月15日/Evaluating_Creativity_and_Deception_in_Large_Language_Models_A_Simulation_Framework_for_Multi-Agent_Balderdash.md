# 评估大型语言模型的创造力与欺骗性：多智能体 Balderdash 的模拟框架

发布时间：2024年11月15日

`LLM应用` `语言模型`

> Evaluating Creativity and Deception in Large Language Models: A Simulation Framework for Multi-Agent Balderdash

# 摘要

> 大型语言模型（LLMs）在复杂任务和交互场景中展现出了非凡的能力，但其创造力尚未被充分挖掘。本文引入了借助游戏 Balderdash 来评估 LLMs 创造力与逻辑推理能力的模拟框架。在 Balderdash 游戏里，玩家为生僻术语创造虚构定义以欺骗他人，同时也要识别正确定义。我们的框架能让多个 LLM 代理参与该游戏，评估它们生成合理定义以及依据游戏规则和历史进行策略规划的能力。我们构建了一个集中式游戏引擎，有各类 LLM 充当参与者，还有一个裁判 LLM 用于评估语义等价性。通过一系列实验，我们剖析了不同 LLMs 的表现，考查了真实定义比率、欺骗比率和正确猜测比率等指标。这些结果为 LLMs 的创新与欺骗能力提供了洞见，凸显出其长处和有待改进之处。具体来说，研究发现，LLMs 输入中罕见的词汇会致使其对游戏规则和历史背景的推理欠佳（https://github.com/ParsaHejabi/Simulation-Framework-for-Multi-Agent-Balderdash）。

> Large Language Models (LLMs) have shown impressive capabilities in complex tasks and interactive environments, yet their creativity remains underexplored. This paper introduces a simulation framework utilizing the game Balderdash to evaluate both the creativity and logical reasoning of LLMs. In Balderdash, players generate fictitious definitions for obscure terms to deceive others while identifying correct definitions. Our framework enables multiple LLM agents to participate in this game, assessing their ability to produce plausible definitions and strategize based on game rules and history. We implemented a centralized game engine featuring various LLMs as participants and a judge LLM to evaluate semantic equivalence. Through a series of experiments, we analyzed the performance of different LLMs, examining metrics such as True Definition Ratio, Deception Ratio, and Correct Guess Ratio. The results provide insights into the creative and deceptive capabilities of LLMs, highlighting their strengths and areas for improvement. Specifically, the study reveals that infrequent vocabulary in LLMs' input leads to poor reasoning on game rules and historical context (https://github.com/ParsaHejabi/Simulation-Framework-for-Multi-Agent-Balderdash).

[Arxiv](https://arxiv.org/abs/2411.10422)