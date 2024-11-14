# 用 LLM 评估世界模型以进行决策

发布时间：2024年11月13日

`LLM应用` `世界模型`

> Evaluating World Models with LLM for Decision Making

# 摘要

> 世界模型在决策中成为一个关键模块，其中 MuZero 和 Dreamer 在复杂任务中取得了显著的成功。最近的工作利用大型语言模型（LLM）作为通用的世界模拟器，由于它们的通用性来模拟世界的动态。LLM 还在通过规划推理（RAP）和思维树（ToT）中作为审议推理的世界模型。然而，世界模型要么被评估为通用的世界模拟器，要么作为代理的功能模块，即预测转换以协助规划。在这项工作中，我们从决策的角度提出了对带有 LLM 的世界模型的综合评估。具体来说，我们利用了（Wang 等人，2023; 2024）中的 31 个不同环境，并为每个环境策划了基于规则的策略以进行多样化的评估。然后，我们设计了三个主要任务，即策略验证、行动建议和策略规划，其中世界模型可以单独用于决策。最后，我们在各种设置下对先进的 LLM（即 GPT-4o 和 GPT-4o-mini）在这些环境中的三个主要任务进行了综合评估。关键观察结果包括：i）GPT-4o 在三个主要任务上明显优于 GPT-4o-mini，特别是对于需要领域知识的任务，ii）带有 LLM 的世界模型在长期决策任务中的性能会下降，iii）世界模型不同功能的组合会带来额外的性能不稳定。

> World model emerges as a key module in decision making, where MuZero and Dreamer achieve remarkable successes in complex tasks. Recent work leverages Large Language Models (LLMs) as general world simulators to simulate the dynamics of the world due to their generalizability. LLMs also serve as the world model for deliberative reasoning in Reasoning via Planning (RAP) and Tree of Thought (ToT). However, the world models are either evaluated as a general world simulator, or as a functional module of the agent, i.e., predicting the transitions to assist the planning. In this work, we propose a comprehensive evaluation of the world models with LLMs from the decision making perspective. Specifically, we leverage the 31 diverse environments from (Wang et al., 2023;2024) and curate the rule-based policy of each environment for the diverse evaluation. Then, we design three main tasks, i.e., policy verification, action proposal, and policy planning, where the world models can be used for decision making solely. Finally, we conduct the comprehensive evaluation of the advanced LLMs, i.e., GPT-4o and GPT-4o-mini, on the environments for the three main tasks under various settings. The key observations include: i) GPT-4o significantly outperforms GPT-4o-mini on the three main tasks, especially for the tasks which require the domain knowledge, ii) the performance of the world model with LLM will be decreased for long-term decision-making tasks, and iii) the combination of different functionalities of the world model will brings additional unstabilities of the performance.

[Arxiv](https://arxiv.org/abs/2411.08794)