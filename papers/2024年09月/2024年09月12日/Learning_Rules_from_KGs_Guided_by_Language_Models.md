# 借助语言模型，从知识图谱中提炼学习规则

发布时间：2024年09月12日

`LLM应用` `知识图谱` `数据分析`

> Learning Rules from KGs Guided by Language Models

# 摘要

> 信息提取技术的进步推动了大型知识图谱（如 Yago、Wikidata 和 Google KG）的自动构建，这些图谱在语义搜索和数据分析等领域广泛应用。然而，由于其半自动构建特性，知识图谱往往存在不完整性。规则学习方法通过提取知识图谱中的频繁模式并将其转化为规则，可用于预测缺失事实。其中，规则排序是关键步骤。在高度不完整或偏斜的知识图谱（如主要存储名人信息的图谱）上，规则排序尤为复杂，因为偏斜规则可能因标准统计指标（如规则置信度）而排名靠前。为解决这一问题，已有研究提出结合原始知识图谱和知识图谱嵌入模型预测的事实进行规则排序。此外，随着语言模型（LMs）的兴起，有观点认为 LMs 可作为知识图谱补全的替代手段。本研究旨在探讨利用语言模型在多大程度上能提升规则学习系统的质量。

> Advances in information extraction have enabled the automatic construction of large knowledge graphs (e.g., Yago, Wikidata or Google KG), which are widely used in many applications like semantic search or data analytics. However, due to their semi-automatic construction, KGs are often incomplete. Rule learning methods, concerned with the extraction of frequent patterns from KGs and casting them into rules, can be applied to predict potentially missing facts. A crucial step in this process is rule ranking. Ranking of rules is especially challenging over highly incomplete or biased KGs (e.g., KGs predominantly storing facts about famous people), as in this case biased rules might fit the data best and be ranked at the top based on standard statistical metrics like rule confidence. To address this issue, prior works proposed to rank rules not only relying on the original KG but also facts predicted by a KG embedding model. At the same time, with the recent rise of Language Models (LMs), several works have claimed that LMs can be used as alternative means for KG completion. In this work, our goal is to verify to which extent the exploitation of LMs is helpful for improving the quality of rule learning systems.

[Arxiv](https://arxiv.org/abs/2409.07869)