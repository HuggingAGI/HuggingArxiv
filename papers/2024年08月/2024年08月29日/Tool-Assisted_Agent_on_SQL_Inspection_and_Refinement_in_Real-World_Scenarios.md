# 工具辅助代理在现实场景中的SQL检查与优化

发布时间：2024年08月29日

`LLM应用` `数据库` `软件开发`

> Tool-Assisted Agent on SQL Inspection and Refinement in Real-World Scenarios

# 摘要

> 近期，Text-to-SQL技术通过整合数据库系统的反馈，有效利用了大型语言模型（LLMs）。尽管这些技术能有效纠正SQL查询的执行错误，但在处理数据库不匹配问题上仍显不足，这类问题不会引发执行异常。为此，我们设计了一个辅助工具框架，包括检索器和检测器，专门用于诊断并修正SQL查询中的不匹配问题，从而提升LLM在实际应用中的查询处理能力。同时，我们推出了Spider-Mismatch数据集，专门针对现实场景中的条件不匹配问题。实验显示，我们的方法在少样本环境下，不仅在Spider系列数据集上表现卓越，更在Spider-Mismatch这一更具现实挑战的数据集上大幅超越了传统方法。

> Recent Text-to-SQL methods leverage large language models (LLMs) by incorporating feedback from the database management system. While these methods effectively address execution errors in SQL queries, they struggle with database mismatches -- errors that do not trigger execution exceptions. Database mismatches include issues such as condition mismatches and stricter constraint mismatches, both of which are more prevalent in real-world scenarios. To address these challenges, we propose a tool-assisted agent framework for SQL inspection and refinement, equipping the LLM-based agent with two specialized tools: a retriever and a detector, designed to diagnose and correct SQL queries with database mismatches. These tools enhance the capability of LLMs to handle real-world queries more effectively. We also introduce Spider-Mismatch, a new dataset specifically constructed to reflect the condition mismatch problems encountered in real-world scenarios. Experimental results demonstrate that our method achieves the highest performance on the averaged results of the Spider and Spider-Realistic datasets in few-shot settings, and it significantly outperforms baseline methods on the more realistic dataset, Spider-Mismatch.

[Arxiv](https://arxiv.org/abs/2408.16991)