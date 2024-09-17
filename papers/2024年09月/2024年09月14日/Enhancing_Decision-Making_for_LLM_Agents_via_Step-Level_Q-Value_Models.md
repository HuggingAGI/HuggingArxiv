# 提升 LLM 代理的决策能力：基于步骤级 Q-值模型

发布时间：2024年09月14日

`Agent` `人工智能` `决策系统`

> Enhancing Decision-Making for LLM Agents via Step-Level Q-Value Models

# 摘要

> 代理通过感知环境、决策和行动，显著提升了独立 LLM 的能力。然而，在多步骤决策任务中，LLM 代理仍面临挑战。本文提出利用任务相关的 Q 值模型指导行动选择。首先，通过蒙特卡洛树搜索收集带 Q 值注释的决策轨迹，构建偏好数据。接着，用另一 LLM 通过步骤级直接策略优化拟合这些偏好，形成 Q 值模型。推理时，LLM 代理在每一步选择最高 Q 值的行动。实验表明，Q 值模型显著提升代理性能，如 Phi-3-mini-4k-instruct 在 WebShop 和 HotPotQA 上分别提升 103% 和 75%，甚至超越 GPT-4o-mini。此外，Q 值模型具有泛化性和与现有提示策略的无缝集成优势。

> Agents significantly enhance the capabilities of standalone Large Language Models (LLMs) by perceiving environments, making decisions, and executing actions. However, LLM agents still face challenges in tasks that require multiple decision-making steps. Estimating the value of actions in specific tasks is difficult when intermediate actions are neither appropriately rewarded nor penalized. In this paper, we propose leveraging a task-relevant Q-value model to guide action selection. Specifically, we first collect decision-making trajectories annotated with step-level Q values via Monte Carlo Tree Search (MCTS) and construct preference data. We then use another LLM to fit these preferences through step-level Direct Policy Optimization (DPO), which serves as the Q-value model. During inference, at each decision-making step, LLM agents select the action with the highest Q value before interacting with the environment. We apply our method to various open-source and API-based LLM agents, demonstrating that Q-value models significantly improve their performance. Notably, the performance of the agent built with Phi-3-mini-4k-instruct improved by 103% on WebShop and 75% on HotPotQA when enhanced with Q-value models, even surpassing GPT-4o-mini. Additionally, Q-value models offer several advantages, such as generalization to different LLM agents and seamless integration with existing prompting strategies.

[Arxiv](https://arxiv.org/abs/2409.09345)