# DMQR-RAG：针对 RAG 的多样化多查询重写

发布时间：2024年11月20日

`RAG`

> DMQR-RAG: Diverse Multi-Query Rewriting for RAG

# 摘要

> 大型语言模型常受静态知识和幻觉的困扰，致使其可靠性受损。检索增强生成（RAG）通过融入外部信息来化解这些难题。不过，用户的查询往往带有噪声和意图偏差，所以需要进行查询重写以提升检索文档的相关性。在本文里，我们推出了 DMQR-RAG，这是一个多元的多查询重写框架，旨在增强 RAG 的文档检索和最终响应表现。具体而言，我们探究了不同信息量的查询怎样检索出多样的文档，并给出了四种在不同信息层级运作的重写策略，以提升基线方法的性能。另外，我们还提出了一种自适应的策略选择方式，在优化整体性能的同时将重写次数减到最少。我们的方法已在学术和工业领域通过大量实验得到了严格验证。

> Large language models often encounter challenges with static knowledge and hallucinations, which undermine their reliability. Retrieval-augmented generation (RAG) mitigates these issues by incorporating external information. However, user queries frequently contain noise and intent deviations, necessitating query rewriting to improve the relevance of retrieved documents. In this paper, we introduce DMQR-RAG, a Diverse Multi-Query Rewriting framework designed to improve the performance of both document retrieval and final responses in RAG. Specifically, we investigate how queries with varying information quantities can retrieve a diverse array of documents, presenting four rewriting strategies that operate at different levels of information to enhance the performance of baseline approaches. Additionally, we propose an adaptive strategy selection method that minimizes the number of rewrites while optimizing overall performance. Our methods have been rigorously validated through extensive experiments conducted in both academic and industry settings.

[Arxiv](https://arxiv.org/abs/2411.13154)