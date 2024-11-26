# 从法律到动机：借由基于法律的推理与奖励引导探索

发布时间：2024年11月24日

`Agent` `智能体`

> From Laws to Motivation: Guiding Exploration through Law-Based Reasoning and Rewards

# 摘要

> 大型语言模型（LLMs）和强化学习（RL）是构建自主智能体的两大有力手段。然而，由于对游戏环境的认知有限，智能体往往会进行低效的探索和不断试错，难以制定出长期策略或做出明智决策。我们提出了一种从交互记录里提取经验以对游戏环境的潜在规律进行建模的办法，将这些经验当作内部动力来引导智能体。这些用语言表述的经验极具灵活性，既能直接辅助智能体推理，也能转化为奖励来指导训练。我们在 Crafter 中的评估结果显示，RL 和 LLM 智能体均从这些经验中获益，使得整体性能得以提升。

> Large Language Models (LLMs) and Reinforcement Learning (RL) are two powerful approaches for building autonomous agents. However, due to limited understanding of the game environment, agents often resort to inefficient exploration and trial-and-error, struggling to develop long-term strategies or make decisions. We propose a method that extracts experience from interaction records to model the underlying laws of the game environment, using these experience as internal motivation to guide agents. These experience, expressed in language, are highly flexible and can either assist agents in reasoning directly or be transformed into rewards for guiding training. Our evaluation results in Crafter demonstrate that both RL and LLM agents benefit from these experience, leading to improved overall performance.

[Arxiv](https://arxiv.org/abs/2411.15891)