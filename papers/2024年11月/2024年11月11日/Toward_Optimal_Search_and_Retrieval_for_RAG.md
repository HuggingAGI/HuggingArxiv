# 致力于实现 RAG 的最优搜索与检索

发布时间：2024年11月11日

`RAG` `语言模型`

> Toward Optimal Search and Retrieval for RAG

# 摘要

> 检索增强生成（RAG）是应对大型语言模型（LLMs）部分记忆相关难题的颇具前景之法。RAG 流程由检索器和阅读器这两个独立系统构成，而它们各自对下游任务性能的影响尚不明确。在此，我们致力于探究如何为常见任务（如问答（QA））的 RAG 流程优化检索器。我们开展了聚焦于问答和归因问答中检索与 RAG 性能关系的实验，揭示了不少对开发高性能 RAG 流程的从业者有益的见解。比如，降低搜索准确率对 RAG 性能影响不大，却可能提升检索速度和内存效率。

> Retrieval-augmented generation (RAG) is a promising method for addressing some of the memory-related challenges associated with Large Language Models (LLMs). Two separate systems form the RAG pipeline, the retriever and the reader, and the impact of each on downstream task performance is not well-understood. Here, we work towards the goal of understanding how retrievers can be optimized for RAG pipelines for common tasks such as Question Answering (QA). We conduct experiments focused on the relationship between retrieval and RAG performance on QA and attributed QA and unveil a number of insights useful to practitioners developing high-performance RAG pipelines. For example, lowering search accuracy has minor implications for RAG performance while potentially increasing retrieval speed and memory efficiency.

[Arxiv](https://arxiv.org/abs/2411.07396)