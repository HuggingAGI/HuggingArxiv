# LLM-PySC2：用于大型语言模型的星际争霸 II 学习环境

发布时间：2024年11月08日

`LLM应用` `人工智能`

> LLM-PySC2: Starcraft II learning environment for Large Language Models

# 摘要

> 这篇论文介绍了一个新的环境 LLM-PySC2（大型语言模型星际争霸 II 学习环境），这是一个源自 DeepMind 的星际争霸 II 学习环境的平台，用于开发基于大型语言模型（LLM）的决策方法。这个环境首次提供了完整的星际争霸 II 动作空间、多模态观察接口和结构化的游戏知识数据库，它们与各种 LLM 无缝连接，以促进基于 LLM 的决策研究。为了进一步支持多智能体研究，我们开发了一个 LLM 协作框架，支持多智能体并发查询和多智能体通信。在我们的实验中，LLM-PySC2 环境被调整为与星际争霸多智能体挑战（SMAC）任务组兼容，并提供了八个侧重于宏观决策能力的新场景。我们在实验中评估了九个主流的 LLM，结果表明，LLM 做出决策需要足够的参数，但提高推理能力并不直接导致更好的决策结果。我们的发现进一步表明，通过参数训练或无训练学习技术使大型模型在部署环境中自主学习的重要性。最终，我们期望 LLM-PySC2 环境能够促进对 LLM 学习方法的研究，帮助基于 LLM 的方法更好地适应任务场景。

> This paper introduces a new environment LLM-PySC2 (the Large Language Model StarCraft II Learning Environment), a platform derived from DeepMind's StarCraft II Learning Environment that serves to develop Large Language Models (LLMs) based decision-making methodologies. This environment is the first to offer the complete StarCraft II action space, multi-modal observation interfaces, and a structured game knowledge database, which are seamlessly connected with various LLMs to facilitate the research of LLMs-based decision-making. To further support multi-agent research, we developed an LLM collaborative framework that supports multi-agent concurrent queries and multi-agent communication. In our experiments, the LLM-PySC2 environment is adapted to be compatible with the StarCraft Multi-Agent Challenge (SMAC) task group and provided eight new scenarios focused on macro-decision abilities. We evaluated nine mainstream LLMs in the experiments, and results show that sufficient parameters are necessary for LLMs to make decisions, but improving reasoning ability does not directly lead to better decision-making outcomes. Our findings further indicate the importance of enabling large models to learn autonomously in the deployment environment through parameter training or train-free learning techniques. Ultimately, we expect that the LLM-PySC2 environment can promote research on learning methods for LLMs, helping LLM-based methods better adapt to task scenarios.

[Arxiv](https://arxiv.org/abs/2411.05348)