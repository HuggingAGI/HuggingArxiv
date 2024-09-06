# GraphInsight：揭示大型语言模型中图结构理解的深层见解

发布时间：2024年09月05日

`LLM应用` `数据分析` `人工智能`

> GraphInsight: Unlocking Insights in Large Language Models for Graph Structure Understanding

# 摘要

> 尽管 LLM 在处理图表方面表现出色，但在理解大型图表结构时，通过描述序列的提示仍显不足。这主要源于 LLM 在不同位置的记忆性能差异，即“位置偏差”。为此，我们推出了 GraphInsight，一个旨在提升 LLM 对图表信息全面理解的新框架。GraphInsight 通过两大策略实现这一目标：首先，将关键信息置于 LLM 记忆较强的位置；其次，借鉴 RAG 理念，引入轻量级外部知识库，弥补记忆薄弱区域的不足。此外，GraphInsight 还将这些策略融入 LLM 的多步骤推理过程中，以应对复杂图表任务。实证研究显示，GraphInsight 在理解各类图表结构方面，显著超越了现有的提示技术和重新排序策略。

> Although Large Language Models (LLMs) have demonstrated potential in processing graphs, they struggle with comprehending graphical structure information through prompts of graph description sequences, especially as the graph size increases. We attribute this challenge to the uneven memory performance of LLMs across different positions in graph description sequences, known as ''positional biases''. To address this, we propose GraphInsight, a novel framework aimed at improving LLMs' comprehension of both macro- and micro-level graphical information. GraphInsight is grounded in two key strategies: 1) placing critical graphical information in positions where LLMs exhibit stronger memory performance, and 2) investigating a lightweight external knowledge base for regions with weaker memory performance, inspired by retrieval-augmented generation (RAG). Moreover, GraphInsight explores integrating these two strategies into LLM agent processes for composite graph tasks that require multi-step reasoning. Extensive empirical studies on benchmarks with a wide range of evaluation tasks show that GraphInsight significantly outperforms all other graph description methods (e.g., prompting techniques and reordering strategies) in understanding graph structures of varying sizes.

[Arxiv](https://arxiv.org/abs/2409.03258)