# G-RAG：材料科学领域的知识拓展

发布时间：2024年11月21日

`RAG` `材料科学` `信息检索`

> G-RAG: Knowledge Expansion in Material Science

# 摘要

> 在材料科学领域，有效的信息检索系统对推动研究意义重大。在大型语言模型（LLMs）中，传统的检索增强生成（RAG）方法常面临诸多挑战，像信息陈旧、产生幻觉、因上下文限制导致可解释性有限以及检索不准确等。为应对这些问题，图 RAG 整合了图形数据库来优化检索过程。我们所提出的方法会从句子里提取关键实体（称作 MatIDs）来处理材料科学文档，接着用其查询外部的维基百科知识库（KBs）以获取更多相关信息。我们采用了一种基于代理的解析技术，以实现对文档更详尽的呈现。我们改进后的图 RAG 版本——G-RAG，进一步借助图形数据库捕捉这些实体间的关系，提升了检索的准确性和对上下文的理解。这种强化的方法在像材料科学这类需要精准信息检索的领域，其性能有了显著的提升。

> In the field of Material Science, effective information retrieval systems are essential for facilitating research. Traditional Retrieval-Augmented Generation (RAG) approaches in Large Language Models (LLMs) often encounter challenges such as outdated information, hallucinations, limited interpretability due to context constraints, and inaccurate retrieval. To address these issues, Graph RAG integrates graph databases to enhance the retrieval process. Our proposed method processes Material Science documents by extracting key entities (referred to as MatIDs) from sentences, which are then utilized to query external Wikipedia knowledge bases (KBs) for additional relevant information. We implement an agent-based parsing technique to achieve a more detailed representation of the documents. Our improved version of Graph RAG called G-RAG further leverages a graph database to capture relationships between these entities, improving both retrieval accuracy and contextual understanding. This enhanced approach demonstrates significant improvements in performance for domains that require precise information retrieval, such as Material Science.

[Arxiv](https://arxiv.org/abs/2411.14592)