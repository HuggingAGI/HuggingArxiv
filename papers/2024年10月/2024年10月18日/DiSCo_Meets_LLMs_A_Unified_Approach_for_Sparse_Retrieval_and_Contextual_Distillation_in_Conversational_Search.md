# DiSCo 与 LLM 结合：对话搜索中稀疏检索与上下文蒸馏的统一方案

发布时间：2024年10月18日

`LLM应用` `搜索引擎` `对话系统`

> DiSCo Meets LLMs: A Unified Approach for Sparse Retrieval and Contextual Distillation in Conversational Search

# 摘要

> 对话搜索 (CS) 结合了检索与对话上下文建模，旨在从语料库中提取相关文档。随着大型语言模型 (LLM) 的兴起，CS 领域通过 LLM 重写用户查询并考虑对话上下文，取得了显著进展。然而，推理时使用 LLM 会降低效率。现有方法通过从人工重写的查询中提取嵌入来解决这一问题，但主要关注上下文建模，仅在蒸馏无关的损失项中处理检索任务的对比部分。为此，我们提出了一种新的蒸馏方法，通过蒸馏对话与文档间的相似性分数，统一了检索与上下文建模，从而在表示空间中提供了更多自由度，并利用了文档相关性的对比性质。实验结果显示，我们的方法在 5 个 CS 数据集的 Learned Sparse Retrieval (LSR) 任务中，域内和域外检索性能均显著提升，超过了最先进的方法，域外数据集的召回率提高了多达 6 个点。此外，通过多教师蒸馏，我们使用多个 LLM 作为教师，进一步提升了性能，并在域内实验中超越了教师模型。最后，模型稀疏性分析表明，我们的蒸馏方法能更好地控制训练模型的稀疏性。

> Conversational Search (CS) is the task of retrieving relevant documents from a corpus within a conversational context, combining retrieval with conversational context modeling. With the explosion of Large Language Models (LLMs), the CS field has seen major improvements with LLMs rewriting user queries, accounting for conversational context. However, engaging LLMs at inference time harms efficiency. Current methods address this by distilling embeddings from human-rewritten queries to learn the context modeling task. Yet, these approaches predominantly focus on context modeling, and only treat the contrastive component of the retrieval task within a distillation-independent loss term. To address these limitations, we propose a new distillation method, as a relaxation of the previous objective, unifying retrieval and context modeling. We relax the existing training objectives by distilling similarity scores between conversations and documents, rather than relying solely on representation learning. Our proposed distillation objective allows for more freedom in the representation space and leverages the contrastive nature of document relevance. Through experiments on Learned Sparse Retrieval (LSR) across 5 CS datasets, our approach demonstrates substantial improvements in both in-domain and out-of-domain retrieval performance, outperforming state-of-the-art with gains of up to 6 points in recall for out-of-domain datasets. Additionally, through the relaxation of the objective, we propose a multi-teacher distillation, using multiple LLMs as teachers, yielding additional gains, and outperforming the teachers themselves in in-domain experiments. Finally, analysis of the sparsity of the models reveals that our distillation allows for better control over the sparsity of the trained models.

[Arxiv](https://arxiv.org/abs/2410.14609)