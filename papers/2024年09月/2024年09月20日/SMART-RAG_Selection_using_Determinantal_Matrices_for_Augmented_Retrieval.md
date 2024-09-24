# SMART-RAG：通过行列式矩阵优化增强检索的选择

发布时间：2024年09月20日

`RAG` `问答系统`

> SMART-RAG: Selection using Determinantal Matrices for Augmented Retrieval

# 摘要

> RAG 通过整合外部信息，使 LLM 能够生成更准确、更贴合上下文的响应，从而显著提升性能。然而，传统 RAG 方法仅依赖查询与上下文的相关性来选择文档，常导致信息冗余和冲突。在无监督检索中，这一问题尤为突出，因缺乏有效机制来优化上下文选择。为此，我们提出了 SMART，一个无需训练的无监督框架，专门用于优化 RAG 中的上下文选择。SMART 利用 DPP 同时考虑相关性、多样性和冲突，确保选择高质量的上下文。实验结果显示，SMART 在多个数据集上显著提升了问答性能，超越了以往的无监督方法，为 RAG 提供了新的有效策略。

> Retrieval-Augmented Generation (RAG) has greatly improved large language models (LLMs) by enabling them to generate accurate, contextually grounded responses through the integration of external information. However, conventional RAG approaches, which prioritize top-ranked documents based solely on query-context relevance, often introduce redundancy and conflicting information. This issue is particularly evident in unsupervised retrieval settings, where there are no mechanisms to effectively mitigate these problems, leading to suboptimal context selection. To address this, we propose Selection using Matrices for Augmented Retrieval (SMART) in question answering tasks, a fully unsupervised and training-free framework designed to optimize context selection in RAG. SMART leverages Determinantal Point Processes (DPPs) to simultaneously model relevance, diversity and conflict, ensuring the selection of potentially high-quality contexts. Experimental results across multiple datasets demonstrate that SMART significantly enhances QA performance and surpasses previous unsupervised context selection methods, showing a promising strategy for RAG.

[Arxiv](https://arxiv.org/abs/2409.13992)