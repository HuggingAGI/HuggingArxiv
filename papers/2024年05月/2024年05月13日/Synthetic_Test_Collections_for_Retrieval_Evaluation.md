# 检索评估的合成测试集

发布时间：2024年05月13日

`RAG

理由：这篇论文主要探讨了利用大型语言模型（LLMs）生成合成数据集，特别是构建全合成测试集合，用于信息检索系统的评估。这与RAG（Retrieval-Augmented Generation）的概念相关，因为RAG是一种结合了检索和生成的模型，旨在提高信息检索和文本生成的性能。论文中提到的利用LLMs生成查询和相关性判断，以及构建合成测试集合，都是RAG领域的应用。因此，这篇论文更符合RAG分类，而不是Agent、LLM应用或LLM理论。` `信息检索` `数据集构建`

> Synthetic Test Collections for Retrieval Evaluation

# 摘要

> 在信息检索系统的评估中，测试集合至关重要。然而，构建包含多样化用户查询的测试集合颇具挑战，而获取相关性判断（即检索文档与查询的匹配度）则成本高昂且耗费资源。近期，利用大型语言模型（LLMs）生成合成数据集的方法备受瞩目。尽管已有研究利用LLMs生成查询或文档以提升排名模型性能，但LLMs在构建合成测试集合方面的应用尚未充分探索。本文深入探讨了LLMs是否能构建全合成测试集合，包括生成查询和相关性判断。我们特别关注了构建可靠合成测试集合的可能性及其对LLM模型的潜在偏见风险。实验结果显示，LLMs能够生成可靠的合成测试集合，用于检索系统的评估。

> Test collections play a vital role in evaluation of information retrieval (IR) systems. Obtaining a diverse set of user queries for test collection construction can be challenging, and acquiring relevance judgments, which indicate the appropriateness of retrieved documents to a query, is often costly and resource-intensive. Generating synthetic datasets using Large Language Models (LLMs) has recently gained significant attention in various applications. In IR, while previous work exploited the capabilities of LLMs to generate synthetic queries or documents to augment training data and improve the performance of ranking models, using LLMs for constructing synthetic test collections is relatively unexplored. Previous studies demonstrate that LLMs have the potential to generate synthetic relevance judgments for use in the evaluation of IR systems. In this paper, we comprehensively investigate whether it is possible to use LLMs to construct fully synthetic test collections by generating not only synthetic judgments but also synthetic queries. In particular, we analyse whether it is possible to construct reliable synthetic test collections and the potential risks of bias such test collections may exhibit towards LLM-based models. Our experiments indicate that using LLMs it is possible to construct synthetic test collections that can reliably be used for retrieval evaluation.

[Arxiv](https://arxiv.org/abs/2405.07767)