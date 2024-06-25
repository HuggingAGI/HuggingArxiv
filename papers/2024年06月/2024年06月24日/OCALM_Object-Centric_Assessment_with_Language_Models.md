# OCALM：语言模型驱动的对象中心评估方法

发布时间：2024年06月24日

`Agent

理由：这篇论文主要关注的是为强化学习（RL）代理设计高效的奖励信号，并提出了一种名为OCALM的新方法，该方法利用大型语言模型（LLMs）的知识来提取可解释的奖励函数，以帮助RL代理理解任务并制定策略。这个研究的重点在于如何改进代理的行为和决策过程，因此属于Agent分类。`

> OCALM: Object-Centric Assessment with Language Models

# 摘要

> 为RL代理设计一个高效的奖励信号颇具挑战，尤其是在复杂环境中，需要专家精心设计目标函数。从人类反馈或LLMs中获取奖励是新兴的解决方案，让非专家也能设定代理目标。但黑盒奖励模型难以调试。为此，我们提出了一种名为OCALM的新方法，它利用LLMs的世界知识和对象中心特性，从自然语言描述中提取可解释的奖励函数，帮助RL代理理解任务并制定策略。

> Properly defining a reward signal to efficiently train a reinforcement learning (RL) agent is a challenging task. Designing balanced objective functions from which a desired behavior can emerge requires expert knowledge, especially for complex environments. Learning rewards from human feedback or using large language models (LLMs) to directly provide rewards are promising alternatives, allowing non-experts to specify goals for the agent. However, black-box reward models make it difficult to debug the reward. In this work, we propose Object-Centric Assessment with Language Models (OCALM) to derive inherently interpretable reward functions for RL agents from natural language task descriptions. OCALM uses the extensive world-knowledge of LLMs while leveraging the object-centric nature common to many environments to derive reward functions focused on relational concepts, providing RL agents with the ability to derive policies from task descriptions.

[Arxiv](https://arxiv.org/abs/2406.16748)