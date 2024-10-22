# 探索 SMAC 任务新解法：借助大型语言模型生成决策树代码

发布时间：2024年10月21日

`Agent` `人工智能`

> A New Approach to Solving SMAC Task: Generating Decision Tree Code from Large Language Models

# 摘要

> StarCraft Multi-Agent Challenge (SMAC) 是多智能体强化学习 (MARL) 中广泛使用的实验环境，任务是控制盟军单位击败敌方。传统 MARL 算法需与环境交互百万步，生成的策略难以解释且转移性差。本文提出 LLM-SMAC 方法，智能体利用大型语言模型 (LLM) 生成决策树代码，并通过环境反馈自我反思。实验表明，该方法能生成高质量、可解释的决策树，且仅需少量环境探索。这些模型还表现出强大的转移性，无需修改即可应用于类似环境。我们相信，这种方法为未来决策任务的解决提供了新思路。

> StarCraft Multi-Agent Challenge (SMAC) is one of the most commonly used experimental environments in multi-agent reinforcement learning (MARL), where the specific task is to control a set number of allied units to defeat enemy forces. Traditional MARL algorithms often require interacting with the environment for up to 1 million steps to train a model, and the resulting policies are typically non-interpretable with weak transferability. In this paper, we propose a novel approach to solving SMAC tasks called LLM-SMAC. In our framework, agents leverage large language models (LLMs) to generate decision tree code by providing task descriptions. The model is further self-reflection using feedback from the rewards provided by the environment. We conduct experiments in the SMAC and demonstrate that our method can produce high-quality, interpretable decision trees with minimal environmental exploration. Moreover, these models exhibit strong transferability, successfully applying to similar SMAC environments without modification. We believe this approach offers a new direction for solving decision-making tasks in the future.

[Arxiv](https://arxiv.org/abs/2410.16024)