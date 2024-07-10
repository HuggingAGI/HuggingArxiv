# 假设心灵：借助大型语言模型，为多智能体任务构建心灵理论的支撑框架

发布时间：2024年07月09日

`Agent` `人工智能`

> Hypothetical Minds: Scaffolding Theory of Mind for Multi-Agent Tasks with Large Language Models

# 摘要

> 多智能体强化学习 (MARL) 在处理系统非平稳性时遇到挑战，且难以与新智能体在线适应学习。我们利用大型语言模型 (LLM) 开发了自主智能体“假设思维”，其受认知启发的架构包含感知、记忆及双层抽象规划模块。引入的“心智理论”模块通过自然语言生成其他智能体策略假设，评估并优化这些假设，以强化正确预测。在 Melting Pot 基准测试中，假设思维在竞争、混合动机及协作领域显著超越以往 LLM-智能体和 RL 基线。对比分析显示，假设评估与优化对复杂场景成功至关重要。

> Multi-agent reinforcement learning (MARL) methods struggle with the non-stationarity of multi-agent systems and fail to adaptively learn online when tested with novel agents. Here, we leverage large language models (LLMs) to create an autonomous agent that can handle these challenges. Our agent, Hypothetical Minds, consists of a cognitively-inspired architecture, featuring modular components for perception, memory, and hierarchical planning over two levels of abstraction. We introduce the Theory of Mind module that scaffolds the high-level planning process by generating hypotheses about other agents' strategies in natural language. It then evaluates and iteratively refines these hypotheses by reinforcing hypotheses that make correct predictions about the other agents' behavior. Hypothetical Minds significantly improves performance over previous LLM-agent and RL baselines on a range of competitive, mixed motive, and collaborative domains in the Melting Pot benchmark, including both dyadic and population-based environments. Additionally, comparisons against LLM-agent baselines and ablations reveal the importance of hypothesis evaluation and refinement for succeeding on complex scenarios.

[Arxiv](https://arxiv.org/abs/2407.07086)