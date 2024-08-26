# SQL-GEN：借助合成数据与模型融合，跨越文本转SQL的方言鸿沟

发布时间：2024年08月22日

`LLM应用` `数据库` `软件开发`

> SQL-GEN: Bridging the Dialect Gap for Text-to-SQL Via Synthetic Data And Model Merging

# 摘要

> Text-to-SQL 系统在 SQLite 方言上取得了显著进展，但适应其他方言如 BigQuery 和 PostgreSQL 仍具挑战。为此，我们推出了 SQL-GEN 框架，通过方言特定教程生成高质量合成数据，有效支持多方言训练数据集的创建。该方法性能提升高达 20%，并缩小了与人工标注数据集的差距。结合合成与人工标注数据，性能再提升 3.3% 至 5.6%。此外，我们创新的专家混合（MoE）初始化方法，通过整合自注意力层和方言关键词，进一步优化了跨方言性能。

> Text-to-SQL systems, which convert natural language queries into SQL commands, have seen significant progress primarily for the SQLite dialect. However, adapting these systems to other SQL dialects like BigQuery and PostgreSQL remains a challenge due to the diversity in SQL syntax and functions. We introduce SQL-GEN, a framework for generating high-quality dialect-specific synthetic data guided by dialect-specific tutorials, and demonstrate its effectiveness in creating training datasets for multiple dialects. Our approach significantly improves performance, by up to 20\%, over previous methods and reduces the gap with large-scale human-annotated datasets. Moreover, combining our synthetic data with human-annotated data provides additional performance boosts of 3.3\% to 5.6\%. We also introduce a novel Mixture of Experts (MoE) initialization method that integrates dialect-specific models into a unified system by merging self-attention layers and initializing the gates with dialect-specific keywords, further enhancing performance across different SQL dialects.

[Arxiv](https://arxiv.org/abs/2408.12733)