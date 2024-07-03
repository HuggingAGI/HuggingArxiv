# RankRAG：整合上下文排序与检索增强生成于大型语言模型中

发布时间：2024年07月02日

`RAG` `生物医学` `人工智能`

> RankRAG: Unifying Context Ranking with Retrieval-Augmented Generation in LLMs

# 摘要

> 我们提出了一种名为 RankRAG 的创新指令微调框架，该框架使单个 LLM 能够同时进行上下文排序和答案生成，显著提升了 RAG 的性能。通过在训练中融入少量排序数据，RankRAG 不仅超越了专门优化的排序模型，还在生成任务上表现卓越，击败了包括 GPT-4 在内的多个顶尖模型。特别是在知识密集型和生物医学领域的基准测试中，RankRAG 展现了其强大的泛化能力，无需特定领域的微调即可与 GPT-4 媲美。

> Large language models (LLMs) typically utilize the top-k contexts from a retriever in retrieval-augmented generation (RAG). In this work, we propose a novel instruction fine-tuning framework RankRAG, which instruction-tunes a single LLM for the dual purpose of context ranking and answer generation in RAG. In particular, the instruction-tuned LLMs work surprisingly well by adding a small fraction of ranking data into the training blend, and outperform existing expert ranking models, including the same LLM exclusively fine-tuned on a large amount of ranking data. For generation, we compare our model with many strong baselines, including GPT-4-0613, GPT-4-turbo-2024-0409, and ChatQA-1.5, an open-sourced model with the state-of-the-art performance on RAG benchmarks. Specifically, our Llama3-RankRAG significantly outperforms Llama3-ChatQA-1.5 and GPT-4 models on nine knowledge-intensive benchmarks. In addition, it also performs comparably to GPT-4 on five RAG benchmarks in the biomedical domain without instruction fine-tuning on biomedical data, demonstrating its superb capability for generalization to new domains.

[Arxiv](https://arxiv.org/abs/2407.02485)