# HOLMES：借助大型语言模型，构建超关系知识图谱，以精妙解答多层次问题。

发布时间：2024年06月10日

`RAG

理由：这篇论文介绍了一种上下文感知的知识图谱（KG），并将其用于改进大型语言模型（LLM）在处理复杂问题时的性能。这种方法通过精简的KG来提供与查询相关的信息，从而优化了LLM的信息提取和整合过程。这与RAG（Retrieval-Augmented Generation）模型的概念相符，即通过检索增强生成过程，以提高模型在特定任务上的表现。因此，这篇论文应归类于RAG。` `问答系统` `知识图谱`

> HOLMES: Hyper-Relational Knowledge Graphs for Multi-hop Question Answering using LLMs

# 摘要

> 大型语言模型（LLMs）在处理非结构化文本时，能轻松应对简单问题，但面对复杂问题时，其性能却大打折扣。这主要是因为理解复杂问题及从原始文本中提取和整合信息的复杂性所致。近期研究尝试通过引入结构化知识三元组来简化这一过程，但这种方法忽略了查询的特定性，导致提取的事实缺乏明确的上下文。为此，我们提出了一种上下文感知的知识图谱（KG），该图谱经过精心提炼，专注于包含与查询相关的信息。通过将这一精简的KG输入LLM，我们的方法在处理支持文档中的查询相关信息时，比现有技术节省了高达67%的令牌。实验结果显示，在HotpotQA和MuSiQue这两个知名基准数据集上，我们的方法在多个评估指标上均优于当前最先进技术。

> Given unstructured text, Large Language Models (LLMs) are adept at answering simple (single-hop) questions. However, as the complexity of the questions increase, the performance of LLMs degrade. We believe this is due to the overhead associated with understanding the complex question followed by filtering and aggregating unstructured information in the raw text. Recent methods try to reduce this burden by integrating structured knowledge triples into the raw text, aiming to provide a structured overview that simplifies information processing. However, this simplistic approach is query-agnostic and the extracted facts are ambiguous as they lack context. To address these drawbacks and to enable LLMs to answer complex (multi-hop) questions with ease, we propose to use a knowledge graph (KG) that is context-aware and is distilled to contain query-relevant information. The use of our compressed distilled KG as input to the LLM results in our method utilizing up to $67\%$ fewer tokens to represent the query relevant information present in the supporting documents, compared to the state-of-the-art (SoTA) method. Our experiments show consistent improvements over the SoTA across several metrics (EM, F1, BERTScore, and Human Eval) on two popular benchmark datasets (HotpotQA and MuSiQue).

[Arxiv](https://arxiv.org/abs/2406.06027)