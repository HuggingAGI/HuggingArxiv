# 从新手到专家：通过逐步强化学习实现 LLM 代理策略优化

发布时间：2024年11月06日

`Agent` `自主代理系统`

> From Novice to Expert: LLM Agent Policy Optimization via Step-wise Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）的出色能力使它们成为各种自主代理系统中的关键组成部分。虽然传统方法依赖于 LLMs 的固有知识而无需微调，但最近的方法已转向强化学习策略，以进一步增强代理解决与环境和工具的复杂交互任务的能力。然而，以前的方法受到稀疏奖励问题的限制，现有的数据集仅为每个多步推理链提供最终的标量奖励，这可能导致策略学习的无效和低效。在本文中，我们引入了 StepAgent，它利用逐步奖励来优化代理的强化学习过程。秉承从新手到专家的理论精神，我们首先比较专家和代理的动作，自动生成中间奖励以进行细粒度优化。此外，我们提出了隐式奖励和逆强化学习技术，以促进代理反思和策略调整。进一步的理论分析表明，代理的动作分布在多个训练周期内可以收敛到专家动作分布。各种数据集的实验结果表明，StepAgent 优于现有的基线方法。

> The outstanding capabilities of large language models (LLMs) render them a crucial component in various autonomous agent systems. While traditional methods depend on the inherent knowledge of LLMs without fine-tuning, more recent approaches have shifted toward the reinforcement learning strategy to further enhance agents' ability to solve complex interactive tasks with environments and tools. However, previous approaches are constrained by the sparse reward issue, where existing datasets solely provide a final scalar reward for each multi-step reasoning chain, potentially leading to ineffectiveness and inefficiency in policy learning. In this paper, we introduce StepAgent, which utilizes step-wise reward to optimize the agent's reinforcement learning process. Inheriting the spirit of novice-to-expert theory, we first compare the actions of the expert and the agent to automatically generate intermediate rewards for fine-grained optimization. Additionally, we propose implicit-reward and inverse reinforcement learning techniques to facilitate agent reflection and policy adjustment. Further theoretical analysis demonstrates that the action distribution of the agent can converge toward the expert action distribution over multiple training cycles. Experimental results across various datasets indicate that StepAgent outperforms existing baseline methods.

[Arxiv](https://arxiv.org/abs/2411.03817)