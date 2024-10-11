# StepTool：为 LLM 中的工具学习量身定制的步骤级强化学习框架

发布时间：2024年10月10日

`LLM应用` `人工智能` `软件开发`

> StepTool: A Step-grained Reinforcement Learning Framework for Tool Learning in LLMs

# 摘要

> 尽管 LLM 具备强大的推理能力，但在解决复杂任务时仍需借助外部工具获取实时信息或专业知识，这就是工具学习。现有方法主要依赖专家轨迹进行调整，专注于语言层面的令牌序列学习。然而，这些方法存在局限：1) 模仿静态轨迹限制了其泛化能力；2) 专家轨迹未必最优，可能存在更佳路径。为此，我们提出了 StepTool，一种创新的步骤级强化学习框架，旨在提升 LLM 的工具学习能力。该框架包含两个核心组件：步骤级奖励塑造和步骤级优化，分别通过动态奖励分配和策略梯度方法优化模型。实验证明，StepTool 在多步骤工具任务中表现卓越，为复杂任务环境提供了坚实解决方案。代码已公开，详见 https://github.com/yuyq18/StepTool。

> Despite having powerful reasoning and inference capabilities, Large Language Models (LLMs) still need external tools to acquire real-time information retrieval or domain-specific expertise to solve complex tasks, which is referred to as tool learning. Existing tool learning methods primarily rely on tuning with expert trajectories, focusing on token-sequence learning from a linguistic perspective. However, there are several challenges: 1) imitating static trajectories limits their ability to generalize to new tasks. 2) even expert trajectories can be suboptimal, and better solution paths may exist. In this work, we introduce StepTool, a novel step-grained reinforcement learning framework to improve tool learning in LLMs. It consists of two components: Step-grained Reward Shaping, which assigns rewards at each tool interaction based on tool invocation success and its contribution to the task, and Step-grained Optimization, which uses policy gradient methods to optimize the model in a multi-step manner. Experimental results demonstrate that StepTool significantly outperforms existing methods in multi-step, tool-based tasks, providing a robust solution for complex task environments. Codes are available at https://github.com/yuyq18/StepTool.

[Arxiv](https://arxiv.org/abs/2410.07745)