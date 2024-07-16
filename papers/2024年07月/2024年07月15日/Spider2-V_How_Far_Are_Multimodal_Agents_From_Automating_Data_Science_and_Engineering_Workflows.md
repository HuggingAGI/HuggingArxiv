# Spider2-V 探讨了多模态代理在自动化数据科学和工程流程方面的进展，以及它们与实现这一目标的距离。

发布时间：2024年07月15日

`Agent` `数据科学` `软件工程`

> Spider2-V: How Far Are Multimodal Agents From Automating Data Science and Engineering Workflows?

# 摘要

> 数据科学与工程的工作流程通常涉及多个环节，从数据仓储到流程编排，借助BigQuery、dbt和Airbyte等工具实现。随着视觉语言模型（VLMs）在多模态理解与代码生成方面的进步，基于VLM的智能代理有望通过自动生成SQL查询、Python代码及GUI操作，实现这些流程的自动化。这不仅能提升专家的工作效率，还能让大规模数据分析更加普及。本文介绍的Spider2-V，是首个聚焦于专业数据科学和工程流程的多模态智能代理基准，涵盖494个真实场景任务，涉及20个企业级专业应用，在真实计算机环境中进行。这些任务源自实际案例，旨在评估智能代理通过编程与GUI管理执行数据任务的能力。为确保评估的现实性与简洁性，我们精心设计了任务自动配置与评估指标。此外，我们还为智能代理提供了详尽的企业数据软件系统文档。实证研究表明，当前顶尖的基于LLM/VLM的智能代理在自动化完整数据流程方面表现不佳（成功率14.0%），即便在详细指导下，其在精细复杂的GUI操作（16.2%）及远程云工作区任务（10.6%）中仍显不足。我们期待Spider2-V能引领自主多模态智能代理革新数据科学和工程流程的自动化。相关代码与数据已公开，详见https://spider2-v.github.io。

> Data science and engineering workflows often span multiple stages, from warehousing to orchestration, using tools like BigQuery, dbt, and Airbyte. As vision language models (VLMs) advance in multimodal understanding and code generation, VLM-based agents could potentially automate these workflows by generating SQL queries, Python code, and GUI operations. This automation can improve the productivity of experts while democratizing access to large-scale data analysis. In this paper, we introduce Spider2-V, the first multimodal agent benchmark focusing on professional data science and engineering workflows, featuring 494 real-world tasks in authentic computer environments and incorporating 20 enterprise-level professional applications. These tasks, derived from real-world use cases, evaluate the ability of a multimodal agent to perform data-related tasks by writing code and managing the GUI in enterprise data software systems. To balance realistic simulation with evaluation simplicity, we devote significant effort to developing automatic configurations for task setup and carefully crafting evaluation metrics for each task. Furthermore, we supplement multimodal agents with comprehensive documents of these enterprise data software systems. Our empirical evaluation reveals that existing state-of-the-art LLM/VLM-based agents do not reliably automate full data workflows (14.0% success). Even with step-by-step guidance, these agents still underperform in tasks that require fine-grained, knowledge-intensive GUI actions (16.2%) and involve remote cloud-hosted workspaces (10.6%). We hope that Spider2-V paves the way for autonomous multimodal agents to transform the automation of data science and engineering workflow. Our code and data are available at https://spider2-v.github.io.

[Arxiv](https://arxiv.org/abs/2407.10956)