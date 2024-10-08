# 利用派生特征关联提升问答系统检索效率

发布时间：2024年10月02日

`RAG` `问答系统` `人工智能`

> Enhancing Retrieval in QA Systems with Derived Feature Association

# 摘要

> RAG 已成为长上下文问答系统的标配，但其检索机制较为简单，常导致主观任务中答案不准确。为此，我们提出了 RAIDD，一种利用 LLM 推导文档特征（如摘要和示例问题）的新型检索方法。实验证明，RAIDD 显著提升了 RAG 在长上下文问答任务中的表现。

> Retrieval augmented generation (RAG) has become the standard in long context question answering (QA) systems. However, typical implementations of RAG rely on a rather naive retrieval mechanism, in which texts whose embeddings are most similar to that of the query are deemed most relevant. This has consequences in subjective QA tasks, where the most relevant text may not directly contain the answer. In this work, we propose a novel extension to RAG systems, which we call Retrieval from AI Derived Documents (RAIDD). RAIDD leverages the full power of the LLM in the retrieval process by deriving inferred features, such as summaries and example questions, from the documents at ingest. We demonstrate that this approach significantly improves the performance of RAG systems on long-context QA tasks.

[Arxiv](https://arxiv.org/abs/2410.03754)