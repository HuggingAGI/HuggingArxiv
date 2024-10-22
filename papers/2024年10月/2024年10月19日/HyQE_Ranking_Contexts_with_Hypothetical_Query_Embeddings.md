# HyQE：通过假设查询嵌入来排序上下文

发布时间：2024年10月19日

`RAG` `信息检索`

> HyQE: Ranking Contexts with Hypothetical Query Embeddings

# 摘要

> 在检索增强系统中，上下文排序技术常用于根据相关性对检索结果进行重新排序。传统方法通过嵌入空间中的相似性来衡量相关性，但往往不够准确。大型语言模型 (LLM) 也被用于排序，但在候选上下文增多时可能面临可扩展性问题，且需要特定领域数据的微调。我们提出了一种无需微调的排序框架，结合了嵌入相似性和 LLM 能力。该框架利用预训练 LLM 根据检索结果生成假设查询，并基于假设查询与用户查询的相似性进行排序。实验证明，我们的方法在多个基准测试中显著提升了排序效果。完整代码和数据已公开，详见 https://github.com/zwc662/hyqe。

> In retrieval-augmented systems, context ranking techniques are commonly employed to reorder the retrieved contexts based on their relevance to a user query. A standard approach is to measure this relevance through the similarity between contexts and queries in the embedding space. However, such similarity often fails to capture the relevance. Alternatively, large language models (LLMs) have been used for ranking contexts. However, they can encounter scalability issues when the number of candidate contexts grows and the context window sizes of the LLMs remain constrained. Additionally, these approaches require fine-tuning LLMs with domain-specific data. In this work, we introduce a scalable ranking framework that combines embedding similarity and LLM capabilities without requiring LLM fine-tuning. Our framework uses a pre-trained LLM to hypothesize the user query based on the retrieved contexts and ranks the context based on the similarity between the hypothesized queries and the user query. Our framework is efficient at inference time and is compatible with many other retrieval and ranking techniques. Experimental results show that our method improves the ranking performance across multiple benchmarks. The complete code and data are available at https://github.com/zwc662/hyqe

[Arxiv](https://arxiv.org/abs/2410.15262)