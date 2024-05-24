# DuetRAG：协同检索增强生成技术

发布时间：2024年05月12日

`RAG

理由：这篇论文主要讨论了RAG（Retrieval-Augmented Generation）方法在处理特定领域问题时的改进，特别是通过引入DuetRAG框架来优化知识检索和提升生成质量。这直接涉及到RAG方法的应用和改进，因此归类为RAG。虽然它也涉及到LLM（大型语言模型）的应用，但核心贡献和讨论集中在RAG方法的改进上，而不是LLM的理论或一般应用。` `问答系统`

> DuetRAG: Collaborative Retrieval-Augmented Generation

# 摘要

> RAG 方法通过为 LLMs 提供相关检索内容，有效降低了知识密集型任务中的事实错误。但在处理如 HotPot QA 这类复杂领域问题时，由于缺乏特定领域知识，现有 RAG 方法常检索到无关信息，影响生成质量。为此，我们创新性地提出了 DuetRAG 框架，通过结合领域微调与 RAG 模型，优化知识检索，进而提升生成质量。实证表明，DuetRAG 在 HotPot QA 任务上与专家级人类表现相当。

> Retrieval-Augmented Generation (RAG) methods augment the input of Large Language Models (LLMs) with relevant retrieved passages, reducing factual errors in knowledge-intensive tasks. However, contemporary RAG approaches suffer from irrelevant knowledge retrieval issues in complex domain questions (e.g., HotPot QA) due to the lack of corresponding domain knowledge, leading to low-quality generations. To address this issue, we propose a novel Collaborative Retrieval-Augmented Generation framework, DuetRAG. Our bootstrapping philosophy is to simultaneously integrate the domain fintuning and RAG models to improve the knowledge retrieval quality, thereby enhancing generation quality. Finally, we demonstrate DuetRAG' s matches with expert human researchers on HotPot QA.

[Arxiv](https://arxiv.org/abs/2405.13002)