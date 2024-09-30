# Embodied-RAG：一种通用的非参数化具身记忆，专为检索与生成任务设计。

发布时间：2024年09月26日

`Agent` `机器人` `人工智能`

> Embodied-RAG: General non-parametric Embodied Memory for Retrieval and Generation

# 摘要

> 机器人探索与学习无止境，但知识需可搜索、可操作。语言研究中，RAG 成为大规模非参数知识的核心，但现有技术难以直接应用于多模态、数据高度相关的具身领域。为此，我们推出 Embodied-RAG，通过非参数记忆系统，增强具身代理的导航与语言生成能力。该系统处理各类环境与查询，从特定对象到整体氛围，核心记忆结构为语义森林，存储多层次语言描述，确保跨平台高效输出。实验证明，Embodied-RAG 成功连接 RAG 与机器人领域，处理超 200 个查询，展现其作为具身代理通用非参数系统的巨大潜力。

> There is no limit to how much a robot might explore and learn, but all of that knowledge needs to be searchable and actionable. Within language research, retrieval augmented generation (RAG) has become the workhouse of large-scale non-parametric knowledge, however existing techniques do not directly transfer to the embodied domain, which is multimodal, data is highly correlated, and perception requires abstraction.
  To address these challenges, we introduce Embodied-RAG, a framework that enhances the foundational model of an embodied agent with a non-parametric memory system capable of autonomously constructing hierarchical knowledge for both navigation and language generation. Embodied-RAG handles a full range of spatial and semantic resolutions across diverse environments and query types, whether for a specific object or a holistic description of ambiance. At its core, Embodied-RAG's memory is structured as a semantic forest, storing language descriptions at varying levels of detail. This hierarchical organization allows the system to efficiently generate context-sensitive outputs across different robotic platforms. We demonstrate that Embodied-RAG effectively bridges RAG to the robotics domain, successfully handling over 200 explanation and navigation queries across 19 environments, highlighting its promise for general-purpose non-parametric system for embodied agents.

[Arxiv](https://arxiv.org/abs/2409.18313)