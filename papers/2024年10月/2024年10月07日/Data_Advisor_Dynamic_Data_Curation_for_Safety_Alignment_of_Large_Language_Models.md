# 数据顾问：为大型语言模型安全对齐提供动态数据管理

发布时间：2024年10月07日

`LLM应用` `人工智能` `数据管理`

> Data Advisor: Dynamic Data Curation for Safety Alignment of Large Language Models

# 摘要

> 数据在 LLM 对齐中至关重要。尽管 LLM 在数据收集方面表现出色，但其生成的数据常存在质量问题，如代表性不足或缺失。为此，我们推出了 Data Advisor，一种基于 LLM 的增强方法，旨在生成更符合需求的数据集。Data Advisor 从预设原则出发，实时监控数据生成过程，识别并修正数据集中的缺陷，从而提升数据质量和覆盖率。实验证明，Data Advisor 不仅能有效增强 LLM 的安全性，还能在不降低模型效用的情况下，应对各种细粒度安全问题。

> Data is a crucial element in large language model (LLM) alignment. Recent studies have explored using LLMs for efficient data collection. However, LLM-generated data often suffers from quality issues, with underrepresented or absent aspects and low-quality datapoints. To address these problems, we propose Data Advisor, an enhanced LLM-based method for generating data that takes into account the characteristics of the desired dataset. Starting from a set of pre-defined principles in hand, Data Advisor monitors the status of the generated data, identifies weaknesses in the current dataset, and advises the next iteration of data generation accordingly. Data Advisor can be easily integrated into existing data generation methods to enhance data quality and coverage. Experiments on safety alignment of three representative LLMs (i.e., Mistral, Llama2, and Falcon) demonstrate the effectiveness of Data Advisor in enhancing model safety against various fine-grained safety issues without sacrificing model utility.

[Arxiv](https://arxiv.org/abs/2410.05269)