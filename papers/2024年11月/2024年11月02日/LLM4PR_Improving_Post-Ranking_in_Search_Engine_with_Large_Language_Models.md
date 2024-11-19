# LLM4PR：借助大型语言模型提升搜索引擎的后排名

发布时间：2024年11月02日

`LLM应用` `信息检索` `搜索引擎`

> LLM4PR: Improving Post-Ranking in Search Engine with Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的迅猛发展，在信息检索（IR）和搜索引擎（SE）中整合LLM技术的努力显著增多。近来，搜索引擎（SE）中提议增设一个额外的后排名阶段，以提升实际应用中的用户满意度。然而，借助LLMs来强化后排名阶段的研究在很大程度上仍未被深入探索。在本研究中，我们推出了一种名为搜索引擎后排名的大型语言模型（LLM4PR）的新范式，它借助LLMs的能力来完成SE中的后排名任务。具体而言，设计了一个查询指导适配器（QIA）模块，通过融合用户/项目的异构特征来推导出用户/项目的表示向量。同时，还进一步引入了一个特征适配步骤，让用户/项目表示的语义与LLM相契合。最后，LLM4PR整合了一个学习后排名步骤，利用主任务和辅助任务来微调模型，以适应后排名任务。实验研究表明，与其他方案相比，所提出的框架带来了显著的提升，展现出了最前沿的性能。

> Alongside the rapid development of Large Language Models (LLMs), there has been a notable increase in efforts to integrate LLM techniques in information retrieval (IR) and search engines (SE). Recently, an additional post-ranking stage is suggested in SE to enhance user satisfaction in practical applications. Nevertheless, research dedicated to enhancing the post-ranking stage through LLMs remains largely unexplored. In this study, we introduce a novel paradigm named Large Language Models for Post-Ranking in search engine (LLM4PR), which leverages the capabilities of LLMs to accomplish the post-ranking task in SE. Concretely, a Query-Instructed Adapter (QIA) module is designed to derive the user/item representation vectors by incorporating their heterogeneous features. A feature adaptation step is further introduced to align the semantics of user/item representations with the LLM. Finally, the LLM4PR integrates a learning to post-rank step, leveraging both a main task and an auxiliary task to fine-tune the model to adapt the post-ranking task. Experiment studies demonstrate that the proposed framework leads to significant improvements and exhibits state-of-the-art performance compared with other alternatives.

[Arxiv](https://arxiv.org/abs/2411.01178)