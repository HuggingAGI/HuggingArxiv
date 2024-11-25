# LLM-Forest 用于健康领域的表格数据插补

发布时间：2024年10月28日

`LLM应用` `数据插补`

> LLM-Forest for Health Tabular Data Imputation

# 摘要

> 缺失数据插补在表格数据集中是个关键难题，尤其在医疗保健领域，数据的完整性对精准分析极为重要。在海量语料库上训练的大型语言模型（LLMs）于数据生成领域展现出强大潜力，成为表格数据插补的有力工具。不过，在为无需微调的流程设计有效提示以及降低LLM产生幻觉的风险方面，仍存在挑战。为应对这些问题，我们提出了一个新颖的框架——LLM-Forest，它引入了带有基于置信度加权投票的少样本学习LLM“树”组成的“森林”。此框架基于二分信息图的新概念构建，用于识别具有特征和值粒度的高质量相关相邻条目。在四个真实的医疗保健数据集上开展的大量实验，证实了LLM-Forest的有效性和高效性。

> Missing data imputation is a critical challenge in tabular datasets, especially in healthcare, where data completeness is vital for accurate analysis. Large language models (LLMs), trained on vast corpora, have shown strong potential in data generation, making them a promising tool for tabular data imputation. However, challenges persist in designing effective prompts for a finetuning-free process and in mitigating the risk of LLM hallucinations. To address these issues, we propose a novel framework, LLM-Forest, which introduces a "forest" of few-shot learning LLM "trees" with confidence-based weighted voting. This framework is established on a new concept of bipartite information graphs to identify high-quality relevant neighboring entries with both feature and value granularity. Extensive experiments on four real-world healthcare datasets demonstrate the effectiveness and efficiency of LLM-Forest.

[Arxiv](https://arxiv.org/abs/2410.21520)