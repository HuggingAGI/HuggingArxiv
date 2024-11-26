# AtomR：赋能于原子运算符的大型语言模型，用于异构知识推理

发布时间：2024年11月25日

`RAG` `知识推理`

> AtomR: Atomic Operator-Empowered Large Language Models for Heterogeneous Knowledge Reasoning

# 摘要

> 近期，大型语言模型（LLMs）的发展给各类自然语言处理任务带来了显著的提升。然而，由于LLMs在推理规划方面效率不高以及存在幻觉问题，其在处理知识密集型的复杂问答时仍面临挑战。典型的解决办法是采用检索增强生成（RAG）与思维链（CoT）推理相结合的方式，将复杂问题分解为链状子问题，并在每个子问题上应用迭代RAG。但此前的工作存在推理规划欠佳以及忽视从异构源动态检索知识的问题。在本文中，我们提出了AtomR，这是一个全新的异构知识推理框架，能在原子级别进行多源推理。受知识图建模的启发，AtomR借助大型语言模型（LLMs）将复杂问题分解为三个原子知识操作符的组合，极大地增强了推理过程中的规划和执行阶段。我们还引入了BlendQA，这是一个专门用于评估复杂异构知识推理的全新评估基准。实验显示，AtomR在三个单源和两个多源推理基准上的表现显著优于最先进的基线，在2WikiMultihop上性能提升了9.4％，在BlendQA上提升了9.5％。

> Recent advancements in large language models (LLMs) have led to significant improvements in various natural language processing tasks, but it is still challenging for LLMs to perform knowledge-intensive complex question answering due to LLMs' inefficacy in reasoning planning and the hallucination problem. A typical solution is to employ retrieval-augmented generation (RAG) coupled with chain-of-thought (CoT) reasoning, which decomposes complex questions into chain-like sub-questions and applies iterative RAG at each sub-question. However, prior works exhibit sub-optimal reasoning planning and overlook dynamic knowledge retrieval from heterogeneous sources. In this paper, we propose AtomR, a novel heterogeneous knowledge reasoning framework that conducts multi-source reasoning at the atomic level. Drawing inspiration from the graph modeling of knowledge, AtomR leverages large language models (LLMs) to decompose complex questions into combinations of three atomic knowledge operators, significantly enhancing the reasoning process at both the planning and execution stages. We also introduce BlendQA, a novel evaluation benchmark tailored to assess complex heterogeneous knowledge reasoning. Experiments show that AtomR significantly outperforms state-of-the-art baselines across three single-source and two multi-source reasoning benchmarks, with notable performance gains of 9.4% on 2WikiMultihop and 9.5% on BlendQA.

[Arxiv](https://arxiv.org/abs/2411.16495)