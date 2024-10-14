# 你知道自己在说什么吗？探讨查询与知识的相关性，助力可靠的检索增强生成。

发布时间：2024年10月10日

`RAG` `问答系统` `知识管理`

> Do You Know What You Are Talking About? Characterizing Query-Knowledge Relevance For Reliable Retrieval Augmented Generation

# 摘要

> 语言模型常出现幻觉和错误信息，而检索增强生成 (RAG) 通过从外部知识库中提取可验证信息，为这些问题提供了有效解决方案。然而，RAG 的生成质量严重依赖于用户查询与检索文档的相关性。若查询超出知识库范围或信息过时，可能导致不准确响应。为此，我们构建了一个统计框架，通过评估知识相关性来判断 RAG 系统回答查询的能力。我们设计了在线测试程序，利用拟合优度测试识别低相关性的超出知识范围查询。同时，开发了离线测试框架，分析用户查询集合，以检测知识库是否仍能满足用户需求。通过在八个问答数据集上的系统评估，我们验证了这些策略的有效性，证明新测试框架能显著提升现有 RAG 系统的可靠性。

> Language models (LMs) are known to suffer from hallucinations and misinformation. Retrieval augmented generation (RAG) that retrieves verifiable information from an external knowledge corpus to complement the parametric knowledge in LMs provides a tangible solution to these problems. However, the generation quality of RAG is highly dependent on the relevance between a user's query and the retrieved documents. Inaccurate responses may be generated when the query is outside of the scope of knowledge represented in the external knowledge corpus or if the information in the corpus is out-of-date. In this work, we establish a statistical framework that assesses how well a query can be answered by an RAG system by capturing the relevance of knowledge. We introduce an online testing procedure that employs goodness-of-fit (GoF) tests to inspect the relevance of each user query to detect out-of-knowledge queries with low knowledge relevance. Additionally, we develop an offline testing framework that examines a collection of user queries, aiming to detect significant shifts in the query distribution which indicates the knowledge corpus is no longer sufficiently capable of supporting the interests of the users. We demonstrate the capabilities of these strategies through a systematic evaluation on eight question-answering (QA) datasets, the results of which indicate that the new testing framework is an efficient solution to enhance the reliability of existing RAG systems.

[Arxiv](https://arxiv.org/abs/2410.08320)