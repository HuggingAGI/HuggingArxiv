# 利用大型语言模型驾驭工业自动化系统

发布时间：2024年09月26日

`LLM应用` `工业自动化` `人工智能`

> Control Industrial Automation System with Large Language Models

# 摘要

> 传统的工业自动化系统操作复杂，适应新流程需要专业知识和繁琐的重新编程。大型语言模型（LLM）的出现为解决这些问题提供了新思路，使其更灵活、更易用。然而，LLM在工业领域的应用仍处于探索阶段。本文提出了一种将LLM集成到工业自动化系统中的框架，实现端到端控制。该框架的核心包括一个专为工业任务设计的代理系统、结构化提示方法和事件驱动的信息建模机制，为LLM提供实时数据进行推理。通过该框架，LLM能够实时解读信息、生成生产计划并控制自动化系统操作。此外，框架还支持为LLM的下游应用创建结构化数据集进行微调。我们的研究成果包括系统设计、概念验证实现以及生成任务特定数据集的方法，使自动化系统更具适应性，能够应对突发事件，并通过自然语言实现更直观的人机交互，简化操作和配置。相关演示视频和详细数据已发布在GitHub：https://github.com/YuchenXia/LLM4IAS

> Traditional industrial automation systems require specialized expertise to operate and complex reprogramming to adapt to new processes. Large language models offer the intelligence to make them more flexible and easier to use. However, LLMs' application in industrial settings is underexplored. This paper introduces a framework for integrating LLMs to achieve end-to-end control of industrial automation systems. At the core of the framework are an agent system designed for industrial tasks, a structured prompting method, and an event-driven information modeling mechanism that provides real-time data for LLM inference. The framework supplies LLMs with real-time events on different context semantic levels, allowing them to interpret the information, generate production plans, and control operations on the automation system. It also supports structured dataset creation for fine-tuning on this downstream application of LLMs. Our contribution includes a formal system design, proof-of-concept implementation, and a method for generating task-specific datasets for LLM fine-tuning and testing. This approach enables a more adaptive automation system that can respond to spontaneous events, while allowing easier operation and configuration through natural language for more intuitive human-machine interaction. We provide demo videos and detailed data on GitHub: https://github.com/YuchenXia/LLM4IAS

[Arxiv](https://arxiv.org/abs/2409.18009)