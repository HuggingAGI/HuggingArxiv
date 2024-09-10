# MemoRAG：借助记忆启发的知识发现，迈向新一代 RAG 技术。

发布时间：2024年09月09日

`RAG` `人工智能`

> MemoRAG: Moving towards Next-Gen RAG Via Memory-Inspired Knowledge Discovery

# 摘要

> RAG 通过访问外部数据库提升 LLM 的生成质量，但现有检索方法仅限于处理明确且结构化的知识。为此，我们提出 **MemoRAG**，一种结合长期记忆的新型检索增强生成系统。MemoRAG 采用双系统架构：轻量级 LLM 负责全局记忆和生成草稿答案，提示检索工具定位信息；而表达力强的 LLM 则根据检索结果生成最终答案。通过优化提示机制和记忆能力，MemoRAG 在复杂和直接任务中均表现出色，超越了传统 RAG 的性能。

> Retrieval-Augmented Generation (RAG) leverages retrieval tools to access external databases, thereby enhancing the generation quality of large language models (LLMs) through optimized context. However, the existing retrieval methods are constrained inherently, as they can only perform relevance matching between explicitly stated queries and well-formed knowledge, but unable to handle tasks involving ambiguous information needs or unstructured knowledge. Consequently, existing RAG systems are primarily effective for straightforward question-answering tasks. In this work, we propose \textbf{MemoRAG}, a novel retrieval-augmented generation paradigm empowered by long-term memory. MemoRAG adopts a dual-system architecture. On the one hand, it employs a \textit{light but long-range} LLM to form the global memory of database. Once a task is presented, it generates draft answers, cluing the retrieval tools to locate useful information within the database. On the other hand, it leverages an \textit{expensive but expressive} LLM, which generates the ultimate answer based on the retrieved information. Building on this general framework, we further optimize MemoRAG's performance by enhancing its cluing mechanism and memorization capacity. In our experiment, MemoRAG achieves superior performance across a variety of evaluation tasks, including both complex ones where conventional RAG fails and straightforward ones where RAG is commonly applied.

[Arxiv](https://arxiv.org/abs/2409.05591)