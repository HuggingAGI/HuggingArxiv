# Plan$	imes$RAG: 规划引导的检索增强式生成

发布时间：2024年10月28日

`RAG` `知识检索`

> Plan$\times$RAG: Planning-guided Retrieval Augmented Generation

# 摘要

> 我们推出了规划引导的检索增强生成（Plan×RAG）这一全新框架，它把现有 RAG 框架的“先检索后推理”模式拓展为“先规划后检索”。Plan×RAG 将推理规划构建成有向无环图（DAG），把查询拆解为相互关联的原子子查询。答案的生成遵循 DAG 结构，通过并行检索和生成大幅提升效率。当下最先进的 RAG 方案需要大量的数据生成以及对语言模型（LMs）的精细调整，而 Plan×RAG 则引入了冻结的 LMs 作为即插即用的专家来生成高质量答案。和现有的 RAG 方案相比，凭借其结构化的子查询分解，Plan×RAG 在减少幻觉和增强归因方面有显著提升。总之，Plan×RAG 为在 LMs 中整合外部知识并通过设计确保归因提供了新视角，有助于打造更可靠的基于 LM 的系统。

> We introduce Planning-guided Retrieval Augmented Generation (Plan$\times$RAG), a novel framework that augments the \emph{retrieve-then-reason} paradigm of existing RAG frameworks to \emph{plan-then-retrieve}. Plan$\times$RAG formulates a reasoning plan as a directed acyclic graph (DAG), decomposing queries into interrelated atomic sub-queries. Answer generation follows the DAG structure, allowing significant gains in efficiency through parallelized retrieval and generation. While state-of-the-art RAG solutions require extensive data generation and fine-tuning of language models (LMs), Plan$\times$RAG incorporates frozen LMs as plug-and-play experts to generate high-quality answers. Compared to existing RAG solutions, Plan$\times$RAG demonstrates significant improvements in reducing hallucinations and bolstering attribution due to its structured sub-query decomposition. Overall, Plan$\times$RAG offers a new perspective on integrating external knowledge in LMs while ensuring attribution by design, contributing towards more reliable LM-based systems.

[Arxiv](https://arxiv.org/abs/2410.20753)