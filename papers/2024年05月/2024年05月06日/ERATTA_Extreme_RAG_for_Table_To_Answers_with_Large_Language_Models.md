# ERATTA：大型语言模型在表格解析中的极致检索增强生成技术，专为精准答案生成而设计。

发布时间：2024年05月06日

`LLM应用

这篇论文介绍了一种创新的LLM系统，该系统能够处理数据认证、查询路由、数据检索和从复杂多变的表格数据中提取答案，专为企业级数据设计，并能在短时间内提供实时信息。它通过一系列提示实现用户认证、数据路由和定制响应生成，并开发了一个评分系统来检测LLM输出中的幻觉。这些特性表明该论文讨论的是LLM在实际应用中的使用，特别是在企业级数据处理方面的应用，因此属于LLM应用分类。` `企业数据管理` `人工智能应用`

> ERATTA: Extreme RAG for Table To Answers with Large Language Models

# 摘要

> RAG与LLMs结合的解决方案在生成式AI领域表现卓越，但它们的使用案例要么过于通用，要么过于专业化，这引发了对其可扩展性和泛化性的质疑。我们提出了一种创新的LLM系统，能够调用多个模型来处理数据认证、查询路由、数据检索和从复杂多变的表格数据中提取答案。该系统专为企业级数据设计，能在10秒内提供实时信息。它通过一系列提示实现用户认证、数据路由和定制响应生成。此外，我们还开发了一个五指标评分系统，用于检测LLM输出中的幻觉，并在多个领域实现了超过90%的置信度。这一系统的扩展潜力巨大，能够支持使用LLMs进行异构数据源的查询。

> Large language models (LLMs) with residual augmented-generation (RAG) have been the optimal choice for scalable generative AI solutions in the recent past. However, the choice of use-cases that incorporate RAG with LLMs have been either generic or extremely domain specific, thereby questioning the scalability and generalizability of RAG-LLM approaches. In this work, we propose a unique LLM-based system where multiple LLMs can be invoked to enable data authentication, user query routing, data retrieval and custom prompting for question answering capabilities from data tables that are highly varying and large in size. Our system is tuned to extract information from Enterprise-level data products and furnish real time responses under 10 seconds. One prompt manages user-to-data authentication followed by three prompts to route, fetch data and generate a customizable prompt natural language responses. Additionally, we propose a five metric scoring module that detects and reports hallucinations in the LLM responses. Our proposed system and scoring metrics achieve >90% confidence scores across hundreds of user queries in the sustainability, financial health and social media domains. Extensions to the proposed extreme RAG architectures can enable heterogeneous source querying using LLMs.

![ERATTA：大型语言模型在表格解析中的极致检索增强生成技术，专为精准答案生成而设计。](../../../paper_images/2405.03963/sys.png)

![ERATTA：大型语言模型在表格解析中的极致检索增强生成技术，专为精准答案生成而设计。](../../../paper_images/2405.03963/p2.png)

![ERATTA：大型语言模型在表格解析中的极致检索增强生成技术，专为精准答案生成而设计。](../../../paper_images/2405.03963/res.png)

![ERATTA：大型语言模型在表格解析中的极致检索增强生成技术，专为精准答案生成而设计。](../../../paper_images/2405.03963/p3.png)

![ERATTA：大型语言模型在表格解析中的极致检索增强生成技术，专为精准答案生成而设计。](../../../paper_images/2405.03963/p4.png)

[Arxiv](https://arxiv.org/abs/2405.03963)