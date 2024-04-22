# Cocoon：运用大型语言模型进行语义化表格剖析

发布时间：2024年04月18日

`LLM应用` `数据科学` `数据分析`

> Cocoon: Semantic Table Profiling Using Large Language Models

# 摘要

> 数据剖析器在数据预处理中至关重要，它们能够识别数据中的质量问题，如缺失、异常或错误值。然而，传统剖析器仅依赖统计方法，常出现误报和漏报。例如，它们可能会错误地将预期中的缺失值标记为异常。为了提高准确性，我们推出了 Cocoon，这是一款融合了大型语言模型（LLMs）的智能数据剖析系统，它通过语义分析增强了统计剖析的准确性。Cocoon 采用三步流程：语义上下文分析、语义剖析和语义审查，显著提升了对真实世界数据集中异常值判断的准确性。用户研究证实，Cocoon 能够有效区分异常值是真正的错误还是基于语义的合理变化。

> Data profilers play a crucial role in the preprocessing phase of data analysis by identifying quality issues such as missing, extreme, or erroneous values. Traditionally, profilers have relied solely on statistical methods, which lead to high false positives and false negatives. For example, they may incorrectly flag missing values where such absences are expected and normal based on the data's semantic context. To address these, we introduce Cocoon, a data profiling system that integrates LLMs to imbue statistical profiling with semantics. Cocoon enhances traditional profiling methods by adding a three-step process: Semantic Context, Semantic Profile, and Semantic Review. Our user studies show that Cocoon is highly effective at accurately discerning whether anomalies are genuine errors requiring correction or acceptable variations based on the semantics for real-world datasets.

[Arxiv](https://arxiv.org/abs/2404.12552)