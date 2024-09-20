# RAG-Modulo：借助经验、评论家和语言模型，解决复杂的顺序任务。

发布时间：2024年09月18日

`Agent` `机器人` `人工智能`

> RAG-Modulo: Solving Sequential Tasks using Experience, Critics, and Language Models

# 摘要

> 大型语言模型 (LLM) 已成为解决复杂机器人任务的有力工具，即使在动作和观察存在不确定性的情况下。最新的基于 LLM 的决策方法（即 LLM 代理），结合适当的评估机制，已展现出在少量交互中解决长期复杂任务的潜力。然而，现有的大多数 LLM 代理缺乏从过往经验中学习和保留的能力，这是学习型机器人系统的关键特征。为此，我们提出了 RAG-Modulo 框架，该框架为 LLM 代理配备了记忆功能，并引入了批评者来评估其决策。记忆模块使代理能够自动提取并整合过往相关经验，提供更具洞察力的决策反馈。随着记忆的不断更新，代理的性能逐步提升，展现出学习能力。实验结果表明，RAG-Modulo 在 BabyAI 和 AlfWorld 等复杂领域中，显著提高了任务成功率和效率，超越了当前最先进的技术水平。

> Large language models (LLMs) have recently emerged as promising tools for solving challenging robotic tasks, even in the presence of action and observation uncertainties. Recent LLM-based decision-making methods (also referred to as LLM-based agents), when paired with appropriate critics, have demonstrated potential in solving complex, long-horizon tasks with relatively few interactions. However, most existing LLM-based agents lack the ability to retain and learn from past interactions - an essential trait of learning-based robotic systems. We propose RAG-Modulo, a framework that enhances LLM-based agents with a memory of past interactions and incorporates critics to evaluate the agents' decisions. The memory component allows the agent to automatically retrieve and incorporate relevant past experiences as in-context examples, providing context-aware feedback for more informed decision-making. Further by updating its memory, the agent improves its performance over time, thereby exhibiting learning. Through experiments in the challenging BabyAI and AlfWorld domains, we demonstrate significant improvements in task success rates and efficiency, showing that the proposed RAG-Modulo framework outperforms state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2409.12294)