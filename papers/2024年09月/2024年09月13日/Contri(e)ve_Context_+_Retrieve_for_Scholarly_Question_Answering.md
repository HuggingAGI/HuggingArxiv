# Contri(e)ve：结合上下文与检索的学术问答新方法

发布时间：2024年09月13日

`RAG` `学术交流` `知识图谱`

> Contri(e)ve: Context + Retrieve for Scholarly Question Answering

# 摘要

> 学术交流领域知识丰富，但因其非结构化特性，传统检索方法难以有效提取信息。学术知识图谱通过语义网络表示文档，揭示隐藏见解，简化查询过程。然而，部分知识仍为非结构化文本，需混合问答系统。本文提出两步解决方案，利用开源LLM Llama3.1处理Scholarly-QALD数据集：首先，从DBLP、SemOpenAlex及Wikipedia中提取相关上下文；其次，通过提示工程优化LLM检索性能。实验F1得分为40%，并探讨了LLM的异常响应。

> Scholarly communication is a rapid growing field containing a wealth of knowledge. However, due to its unstructured and document format, it is challenging to extract useful information from them through conventional document retrieval methods. Scholarly knowledge graphs solve this problem, by representing the documents in a semantic network, providing, hidden insights, summaries and ease of accessibility through queries. Naturally, question answering for scholarly graphs expands the accessibility to a wider audience. But some of the knowledge in this domain is still presented as unstructured text, thus requiring a hybrid solution for question answering systems. In this paper, we present a two step solution using open source Large Language Model(LLM): Llama3.1 for Scholarly-QALD dataset. Firstly, we extract the context pertaining to the question from different structured and unstructured data sources: DBLP, SemOpenAlex knowledge graphs and Wikipedia text. Secondly, we implement prompt engineering to improve the information retrieval performance of the LLM. Our approach achieved an F1 score of 40% and also observed some anomalous responses from the LLM, that are discussed in the final part of the paper.

[Arxiv](https://arxiv.org/abs/2409.09010)