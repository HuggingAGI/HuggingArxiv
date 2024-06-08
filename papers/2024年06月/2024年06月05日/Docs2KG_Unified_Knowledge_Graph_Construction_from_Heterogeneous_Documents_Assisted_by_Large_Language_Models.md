# Docs2KG：利用大型语言模型，从多样文档中精炼出统一的知识图谱

发布时间：2024年06月05日

`Agent

理由：这篇论文介绍的 Docs2KG 框架是一个能够从多种异构文档中提取信息并构建知识图谱的系统。这个系统可以被视为一个智能代理（Agent），因为它能够自主地处理和整合数据，提供高效查询和探索功能，适应不同的文档结构和内容，并支持多样化的下游任务。这种能力符合Agent的定义，即一个能够感知环境并采取行动以达到目标的系统。因此，将这篇论文归类为Agent是合适的。` `数据管理` `知识图谱`

> Docs2KG: Unified Knowledge Graph Construction from Heterogeneous Documents Assisted by Large Language Models

# 摘要

> 即便保守估计，企业数据的80%都存储在容纳异构格式的非结构化文件中。传统搜索引擎已难以满足深入探索和洞察形成的需求，尤其是在缺乏明确搜索关键词的情况下。知识图谱因其视觉吸引力强、认知负担轻，成为异构数据整合与知识表达的首选。本文推出的 Docs2KG 框架，能从电子邮件、网页、PDF 及 Excel 等异构文档中提取多模态信息，并动态构建统一的知识图谱，便于高效查询与探索。不同于以往局限于特定领域或预设模式的方法，Docs2KG 灵活可扩展，适应各类文档结构与内容。该框架整合数据处理，提升领域解释性，支持多样下游任务。Docs2KG 已开放访问，演示视频亦可观看。

> Even for a conservative estimate, 80% of enterprise data reside in unstructured files, stored in data lakes that accommodate heterogeneous formats. Classical search engines can no longer meet information seeking needs, especially when the task is to browse and explore for insight formulation. In other words, there are no obvious search keywords to use. Knowledge graphs, due to their natural visual appeals that reduce the human cognitive load, become the winning candidate for heterogeneous data integration and knowledge representation.
  In this paper, we introduce Docs2KG, a novel framework designed to extract multimodal information from diverse and heterogeneous unstructured documents, including emails, web pages, PDF files, and Excel files. Dynamically generates a unified knowledge graph that represents the extracted key information, Docs2KG enables efficient querying and exploration of document data lakes. Unlike existing approaches that focus on domain-specific data sources or pre-designed schemas, Docs2KG offers a flexible and extensible solution that can adapt to various document structures and content types. The proposed framework unifies data processing supporting a multitude of downstream tasks with improved domain interpretability. Docs2KG is publicly accessible at https://docs2kg.ai4wa.com, and a demonstration video is available at https://docs2kg.ai4wa.com/Video.

![Docs2KG：利用大型语言模型，从多样文档中精炼出统一的知识图谱](../../../paper_images/2406.02962/x1.png)

![Docs2KG：利用大型语言模型，从多样文档中精炼出统一的知识图谱](../../../paper_images/2406.02962/demo_query.png)

![Docs2KG：利用大型语言模型，从多样文档中精炼出统一的知识图谱](../../../paper_images/2406.02962/query.png)

![Docs2KG：利用大型语言模型，从多样文档中精炼出统一的知识图谱](../../../paper_images/2406.02962/RAG_DEMO.png)

[Arxiv](https://arxiv.org/abs/2406.02962)