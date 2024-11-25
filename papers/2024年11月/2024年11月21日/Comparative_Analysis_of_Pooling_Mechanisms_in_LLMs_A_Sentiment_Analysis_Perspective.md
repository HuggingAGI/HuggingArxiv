# 从情感分析的视角对 LLMs 中的池化机制进行比较分析

发布时间：2024年11月21日

`LLM应用` `情感分析`

> Comparative Analysis of Pooling Mechanisms in LLMs: A Sentiment Analysis Perspective

# 摘要

> 大型语言模型（LLMs）凭借在各类任务中的出色表现，给自然语言处理（NLP）带来了革命性的变化。其中，像 BERT 和 GPT 这类基于 Transformer 的模型借助池化层将标记级嵌入聚合为句子级表示。常见的池化机制，比如均值、最大值和加权和在这一聚合过程中发挥着关键作用。尽管它们应用广泛，但这些策略在不同 LLM 架构上的对比性能仍有待深入探究。为填补这一空白，本文在句子级情感分析的情境中，研究了这些池化机制对 BERT 和 GPT 这两个知名的 LLM 家族的影响。综合实验显示，每个池化机制依据任务的具体要求，都有其独特的优劣之处。我们的发现凸显了根据特定应用需求选择池化方法的重要性，促使人们重新审视有关池化操作的常见假定。通过提供切实可行的见解，本研究有助于为下游任务优化基于 LLM 的模型。

> Large Language Models (LLMs) have revolutionized natural language processing (NLP) by delivering state-of-the-art performance across a variety of tasks. Among these, Transformer-based models like BERT and GPT rely on pooling layers to aggregate token-level embeddings into sentence-level representations. Common pooling mechanisms such as Mean, Max, and Weighted Sum play a pivotal role in this aggregation process. Despite their widespread use, the comparative performance of these strategies on different LLM architectures remains underexplored. To address this gap, this paper investigates the effects of these pooling mechanisms on two prominent LLM families -- BERT and GPT, in the context of sentence-level sentiment analysis. Comprehensive experiments reveal that each pooling mechanism exhibits unique strengths and weaknesses depending on the task's specific requirements. Our findings underline the importance of selecting pooling methods tailored to the demands of particular applications, prompting a re-evaluation of common assumptions regarding pooling operations. By offering actionable insights, this study contributes to the optimization of LLM-based models for downstream tasks.

[Arxiv](https://arxiv.org/abs/2411.14654)