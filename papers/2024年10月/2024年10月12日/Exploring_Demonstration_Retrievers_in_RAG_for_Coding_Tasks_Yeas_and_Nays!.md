# RAG 中编码任务演示检索器的探索：利弊分析！

发布时间：2024年10月12日

`RAG` `软件开发` `人工智能`

> Exploring Demonstration Retrievers in RAG for Coding Tasks: Yeas and Nays!

# 摘要

> RAG 通过整合外部知识库，显著提升了 LLM 在编码任务中的表现。然而，代码的高维性和庞大的知识库常导致效率瓶颈，这在以往研究中被忽视。本文系统评估了三种编码任务中检索器的效率与有效性。研究发现，BM25 在有效性上表现优异，但随着知识库规模扩大，效率显著下降。相比之下，近似密集检索器在大规模检索中表现出色，如 HNSW 在提交生成任务中实现了 44 倍的速度提升，且 RougeL 仅下降 1.74%。此外，增加演示数量并不总能提升效果，反而可能增加延迟和错误。这些发现为构建高效且有效的 RAG 系统提供了重要参考。

> Retrieval-Augmented Generation (RAG) enhances Large Language Models (LLMs) by integrating external knowledge bases, achieving state-of-the-art results in various coding tasks. The core of RAG is retrieving demonstration examples, which is essential to balance effectiveness (generation quality) and efficiency (retrieval time) for optimal performance. However, the high-dimensional nature of code representations and large knowledge bases often create efficiency bottlenecks, which are overlooked in previous research. This paper systematically evaluates the efficiency-effectiveness trade-off of retrievers across three coding tasks: Program Synthesis, Commit Message Generation, and Assertion Generation. We examined six retrievers: two sparse (BM25 and BM25L) and four dense retrievers, including one exhaustive dense retriever (SBERT's Semantic Search) and three approximate dense retrievers (ANNOY, LSH, and HNSW). Our findings show that while BM25 excels in effectiveness, it suffers in efficiency as the knowledge base grows beyond 1000 entries. In large-scale retrieval, efficiency differences become more pronounced, with approximate dense retrievers offering the greatest gains. For instance, in Commit Generation task, HNSW achieves a 44x speed up, while only with a 1.74% drop in RougeL compared with BM25. Our results also show that increasing the number of demonstrations in the prompt doesn't always improve the effectiveness and can increase latency and lead to incorrect outputs. Our findings provide valuable insights for practitioners aiming to build efficient and effective RAG systems for coding tasks.

[Arxiv](https://arxiv.org/abs/2410.09662)