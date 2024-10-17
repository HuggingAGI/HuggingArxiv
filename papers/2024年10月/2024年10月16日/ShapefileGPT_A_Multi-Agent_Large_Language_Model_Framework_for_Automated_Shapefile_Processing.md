# ShapefileGPT：一款专为自动化 Shapefile 处理设计的多智能体大型语言模型框架

发布时间：2024年10月16日

`Agent` `地理信息系统` `人工智能`

> ShapefileGPT: A Multi-Agent Large Language Model Framework for Automated Shapefile Processing

# 摘要

> 矢量数据是 GIS 的核心，对于精准存储和展现地理信息至关重要。Shapefile 作为最常用的矢量格式，已成为 GIS 行业的标准。然而，处理 Shapefile 通常需要专业 GIS 技能，这为非 GIS 领域的研究者设置了障碍，阻碍了空间数据分析的跨学科合作。尽管 LLM 在 NLP 和任务自动化方面取得了显著进展，但在处理 GIS 矢量数据的复杂空间关系上仍显不足。为此，我们推出了 ShapefileGPT，一个由 LLM 驱动的创新框架，专为自动化 Shapefile 任务设计。ShapefileGPT 采用多代理架构，规划代理负责任务分解与监督，工作代理执行具体任务。我们开发了专门的 Shapefile 处理功能库，并提供详尽的 API 文档，使工作代理能高效操作 Shapefile。通过基于权威教科书的基准数据集评估，ShapefileGPT 在几何操作和空间查询等任务上表现优异，成功率达到 95.24%，超越了 GPT 系列模型。相比传统 LLM，ShapefileGPT 在处理复杂矢量数据分析任务上更具优势，为 GIS 领域的自动化和智能化开辟了新路径，在跨学科数据分析和应用中展现出巨大潜力。

> Vector data is one of the two core data structures in geographic information science (GIS), essential for accurately storing and representing geospatial information. Shapefile, the most widely used vector data format, has become the industry standard supported by all major geographic information systems. However, processing this data typically requires specialized GIS knowledge and skills, creating a barrier for researchers from other fields and impeding interdisciplinary research in spatial data analysis. Moreover, while large language models (LLMs) have made significant advancements in natural language processing and task automation, they still face challenges in handling the complex spatial and topological relationships inherent in GIS vector data. To address these challenges, we propose ShapefileGPT, an innovative framework powered by LLMs, specifically designed to automate Shapefile tasks. ShapefileGPT utilizes a multi-agent architecture, in which the planner agent is responsible for task decomposition and supervision, while the worker agent executes the tasks. We developed a specialized function library for handling Shapefiles and provided comprehensive API documentation, enabling the worker agent to operate Shapefiles efficiently through function calling. For evaluation, we developed a benchmark dataset based on authoritative textbooks, encompassing tasks in categories such as geometric operations and spatial queries. ShapefileGPT achieved a task success rate of 95.24%, outperforming the GPT series models. In comparison to traditional LLMs, ShapefileGPT effectively handles complex vector data analysis tasks, overcoming the limitations of traditional LLMs in spatial analysis. This breakthrough opens new pathways for advancing automation and intelligence in the GIS field, with significant potential in interdisciplinary data analysis and application contexts.

[Arxiv](https://arxiv.org/abs/2410.12376)