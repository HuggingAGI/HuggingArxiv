# SynDL：一款大规模合成测试集

发布时间：2024年08月29日

`LLM应用` `信息检索` `搜索引擎`

> SynDL: A Large-Scale Synthetic Test Collection

# 摘要

> 在信息检索研究中，大规模测试集至关重要。然而，现有研究多基于小规模数据集，依赖人工评估相关性，耗时且成本高昂。最新研究表明，大型语言模型能以低成本实现与人类相当的相关性判断。本文针对缺乏大规模临时文档检索数据集的问题，通过扩展TREC深度学习轨道测试集，引入语言模型合成标签，助力研究人员大规模测试和评估搜索系统。该测试集包含1,900多个历史查询，经比较发现，合成的大规模测试集能有效提升系统排名的一致性。

> Large-scale test collections play a crucial role in Information Retrieval (IR) research. However, according to the Cranfield paradigm and the research into publicly available datasets, the existing information retrieval research studies are commonly developed on small-scale datasets that rely on human assessors for relevance judgments - a time-intensive and expensive process. Recent studies have shown the strong capability of Large Language Models (LLMs) in producing reliable relevance judgments with human accuracy but at a greatly reduced cost. In this paper, to address the missing large-scale ad-hoc document retrieval dataset, we extend the TREC Deep Learning Track (DL) test collection via additional language model synthetic labels to enable researchers to test and evaluate their search systems at a large scale. Specifically, such a test collection includes more than 1,900 test queries from the previous years of tracks. We compare system evaluation with past human labels from past years and find that our synthetically created large-scale test collection can lead to highly correlated system rankings.

[Arxiv](https://arxiv.org/abs/2408.16312)