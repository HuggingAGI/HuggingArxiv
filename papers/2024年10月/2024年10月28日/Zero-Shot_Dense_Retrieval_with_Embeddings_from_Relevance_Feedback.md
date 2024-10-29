# 零-shot 密集检索与来自相关性反馈的嵌入

发布时间：2024年10月28日

`LLM应用` `信息检索`

> Zero-Shot Dense Retrieval with Embeddings from Relevance Feedback

# 摘要

> 在没有相关性监督的情况下构建有效的密集检索系统仍然困难。最近的工作试图通过使用大型语言模型（LLM）生成可用于查找最接近的真实文档的假设文档来克服这一挑战。然而，这种方法完全依赖于 LLM 具有与查询相关的特定领域知识，这可能不实际。此外，生成假设文档可能效率低下，因为它要求 LLM 为每个查询生成大量标记。为了解决这些挑战，我们引入了来自相关性反馈的真实文档嵌入（ReDE-RF）。受相关性反馈的启发，ReDE-RF 提议将假设文档生成重新定义为相关性估计任务，使用 LLM 选择应用于最近邻搜索的文档。通过这种重新定义，LLM 不再需要特定领域的知识，而只需要判断什么是相关的。此外，相关性估计只要求 LLM 输出单个标记，从而提高搜索延迟。我们的实验表明，ReDE-RF 在各种低资源检索数据集中始终超越最先进的零样本密集检索方法，同时在每个查询的延迟方面也有显著改进。

> Building effective dense retrieval systems remains difficult when relevance supervision is not available. Recent work has looked to overcome this challenge by using a Large Language Model (LLM) to generate hypothetical documents that can be used to find the closest real document. However, this approach relies solely on the LLM to have domain-specific knowledge relevant to the query, which may not be practical. Furthermore, generating hypothetical documents can be inefficient as it requires the LLM to generate a large number of tokens for each query. To address these challenges, we introduce Real Document Embeddings from Relevance Feedback (ReDE-RF). Inspired by relevance feedback, ReDE-RF proposes to re-frame hypothetical document generation as a relevance estimation task, using an LLM to select which documents should be used for nearest neighbor search. Through this re-framing, the LLM no longer needs domain-specific knowledge but only needs to judge what is relevant. Additionally, relevance estimation only requires the LLM to output a single token, thereby improving search latency. Our experiments show that ReDE-RF consistently surpasses state-of-the-art zero-shot dense retrieval methods across a wide range of low-resource retrieval datasets while also making significant improvements in latency per-query.

[Arxiv](https://arxiv.org/abs/2410.21242)