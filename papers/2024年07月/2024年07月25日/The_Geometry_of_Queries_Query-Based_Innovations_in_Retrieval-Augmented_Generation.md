# 查询几何：检索增强生成中的基于查询创新

发布时间：2024年07月25日

`RAG` `数字健康`

> The Geometry of Queries: Query-Based Innovations in Retrieval-Augmented Generation

# 摘要

> 借助大型语言模型（LLM）的数字健康聊天机器人，有望通过提供便捷的按需健康指导和问答服务，大幅提升慢性病患者的个人健康管理。但这些聊天机器人可能因依赖互联网数据模式生成回复而提供不实信息。检索增强生成（RAG）技术通过依托可靠内容生成回复，有助于减少信息误差。然而，如何高效精准地从海量内容中筛选出与用户实时问题最匹配的信息，仍是一大难题。为此，我们创新性地提出了基于查询的检索增强生成（QB-RAG）方法，该方法利用LLM预先构建了一个包含潜在查询的数据库。当患者提问时，QB-RAG通过向量搜索迅速匹配预生成数据库，优化问题与答案的契合度。我们不仅为QB-RAG奠定了理论基础，还对比分析了现有RAG系统的检索增强技术。实证研究显示，QB-RAG在健康问答准确性上取得了显著提升，为数字健康领域中LLM的稳健可靠应用开辟了新路径。

> Digital health chatbots powered by Large Language Models (LLMs) have the potential to significantly improve personal health management for chronic conditions by providing accessible and on-demand health coaching and question-answering. However, these chatbots risk providing unverified and inaccurate information because LLMs generate responses based on patterns learned from diverse internet data. Retrieval Augmented Generation (RAG) can help mitigate hallucinations and inaccuracies in LLM responses by grounding it on reliable content. However, efficiently and accurately retrieving most relevant set of content for real-time user questions remains a challenge. In this work, we introduce Query-Based Retrieval Augmented Generation (QB-RAG), a novel approach that pre-computes a database of potential queries from a content base using LLMs. For an incoming patient question, QB-RAG efficiently matches it against this pre-generated query database using vector search, improving alignment between user questions and the content. We establish a theoretical foundation for QB-RAG and provide a comparative analysis of existing retrieval enhancement techniques for RAG systems. Finally, our empirical evaluation demonstrates that QB-RAG significantly improves the accuracy of healthcare question answering, paving the way for robust and trustworthy LLM applications in digital health.

![查询几何：检索增强生成中的基于查询创新](../../../paper_images/2407.18044/cc-summary.png)

[Arxiv](https://arxiv.org/abs/2407.18044)