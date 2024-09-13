# 利用排名模型提升问答文本检索：RAG 的 Rerankers 基准测试、微调与部署

发布时间：2024年09月11日

`LLM应用` `信息检索` `问答系统`

> Enhancing Q&A Text Retrieval with Ranking Models: Benchmarking, fine-tuning and deploying Rerankers for RAG

# 摘要

> 排名模型在提升文本检索系统准确性方面至关重要。这些系统通常先通过密集嵌入或稀疏索引检索相关段落，再由排名模型根据相关性进行排序。本文测试了多种公开的排名模型，并探讨了它们对问答任务检索准确性的影响。我们引入的NV-RerankQA-Mistral-4B-v3模型，相比其他重排器，准确性提升了约14%。此外，我们还对比了不同配置下排名模型的微调效果。最后，我们探讨了实际应用中，模型大小、准确性与系统性能之间的权衡。

> Ranking models play a crucial role in enhancing overall accuracy of text retrieval systems. These multi-stage systems typically utilize either dense embedding models or sparse lexical indices to retrieve relevant passages based on a given query, followed by ranking models that refine the ordering of the candidate passages by its relevance to the query.
  This paper benchmarks various publicly available ranking models and examines their impact on ranking accuracy. We focus on text retrieval for question-answering tasks, a common use case for Retrieval-Augmented Generation systems. Our evaluation benchmarks include models some of which are commercially viable for industrial applications.
  We introduce a state-of-the-art ranking model, NV-RerankQA-Mistral-4B-v3, which achieves a significant accuracy increase of ~14% compared to pipelines with other rerankers. We also provide an ablation study comparing the fine-tuning of ranking models with different sizes, losses and self-attention mechanisms.
  Finally, we discuss challenges of text retrieval pipelines with ranking models in real-world industry applications, in particular the trade-offs among model size, ranking accuracy and system requirements like indexing and serving latency / throughput.

[Arxiv](https://arxiv.org/abs/2409.07691)