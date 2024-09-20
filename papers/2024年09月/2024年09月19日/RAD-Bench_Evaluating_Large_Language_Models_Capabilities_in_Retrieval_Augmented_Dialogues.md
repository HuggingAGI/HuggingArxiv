# RAD-Bench：评估大型语言模型在检索增强对话中的表现

发布时间：2024年09月19日

`RAG` `对话系统` `人工智能`

> RAD-Bench: Evaluating Large Language Models Capabilities in Retrieval Augmented Dialogues

# 摘要

> 在 LLM 的实际应用中，外部检索机制如 SAG、工具利用和 RAG 常用于提升对话质量。现有基准多关注多轮对话中的聊天能力或单轮检索响应，但缺乏对多轮对话中精确检索能力的评估。为此，我们推出了 RAD-Bench，专门评估 LLM 在检索后多轮对话中的表现，这对上下文丰富的应用至关重要。RAD-Bench 通过区分性问题、检索上下文和参考答案，评估 LLM 的检索综合和推理能力。评估显示，即使检索上下文准确，随着对话轮次中条件或约束的增加，模型性能仍会下降。

> In real-world applications with Large Language Models (LLMs), external retrieval mechanisms - such as Search-Augmented Generation (SAG), tool utilization, and Retrieval-Augmented Generation (RAG) - are often employed to enhance the quality of augmented generations in dialogues. These approaches often come with multi-turn dialogue, where each interaction is enriched by relevant information retrieved from external sources. Existing benchmarks either assess LLMs' chat abilities in multi-turn dialogues or their use of retrieval for augmented responses in single-turn settings. However, there is a gap in evaluating LLMs' ability to leverage retrieval for more precise responses across multiple turns. To address this limitation, we introduce RAD-Bench (Retrieval Augmented Dialogue), a benchmark designed to evaluate LLMs' capabilities in multi-turn dialogues following retrievals, essential for their deployment in context-rich applications. RAD-Bench evaluates two key abilities of LLMs: Retrieval Synthesis and Retrieval Reasoning. These are measured using discriminative questions and retrieved contexts, and corresponding reference answers, assessing how effectively LLMs integrate and reason with context to maintain and enhance conversation quality over multiple turns. Our evaluation results on commonly used LLMs reveal that model performance deteriorates as additional layers of conditions or constraints are applied across conversation turns, even when accurate retrieved contexts are provided.

[Arxiv](https://arxiv.org/abs/2409.12558)