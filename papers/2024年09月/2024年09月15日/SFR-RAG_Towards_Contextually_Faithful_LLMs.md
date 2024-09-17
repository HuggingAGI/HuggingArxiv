# SFR-RAG：迈向上下文忠实的大型语言模型

发布时间：2024年09月15日

`RAG` `人工智能`

> SFR-RAG: Towards Contextually Faithful LLMs

# 摘要

> RAG 通过整合外部信息与 LLM，显著提升了生成内容的事实准确性，成为生成式 AI 的核心技术。RAG 中的 LLM 需精准理解上下文及用户问题，避免幻觉，应对复杂推理，并提供可靠引用。本文介绍的 SFR-RAG 是一款小型 LLM，特别优化了基于上下文的生成和幻觉控制。同时，我们推出的 ContextualBench 评估框架，整合了 HotpotQA 和 TriviaQA 等多样基准，确保评估的一致性和可重复性。实验显示，SFR-RAG-9B 在多个基准测试中超越了 Command-R+ 和 GPT-4o，参数更少却表现更优。SFR-RAG 还能灵活应对上下文变化，并在相关信息缺失时依然表现稳健。此外，它在指令跟随和功能调用方面也表现出色。

> Retrieval Augmented Generation (RAG), a paradigm that integrates external contextual information with large language models (LLMs) to enhance factual accuracy and relevance, has emerged as a pivotal area in generative AI. The LLMs used in RAG applications are required to faithfully and completely comprehend the provided context and users' questions, avoid hallucination, handle unanswerable, counterfactual or otherwise low-quality and irrelevant contexts, perform complex multi-hop reasoning and produce reliable citations. In this paper, we introduce SFR-RAG, a small LLM that is instruction-tuned with an emphasis on context-grounded generation and hallucination minimization. We also present ContextualBench, a new evaluation framework compiling multiple popular and diverse RAG benchmarks, such as HotpotQA and TriviaQA, with consistent RAG settings to ensure reproducibility and consistency in model assessments. Experimental results demonstrate that our SFR-RAG-9B model outperforms leading baselines such as Command-R+ (104B) and GPT-4o, achieving state-of-the-art results in 3 out of 7 benchmarks in ContextualBench with significantly fewer parameters. The model is also shown to be resilient to alteration in the contextual information and behave appropriately when relevant context is removed. Additionally, the SFR-RAG model maintains competitive performance in general instruction-following tasks and function-calling capabilities.

[Arxiv](https://arxiv.org/abs/2409.09916)