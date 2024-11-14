# 知识基础支持用于处理网络新闻的大型语言模型

发布时间：2024年11月12日

`LLM应用` `知识库`

> Knowledge Bases in Support of Large Language Models for Processing Web News

# 摘要

> 大型语言模型（LLMs）最近在广泛的应用中引起了相当大的兴趣。在通过大规模数据集进行预训练期间，这样的模型在其隐藏参数中隐式地记住了训练数据集的事实知识。然而，由于缺乏常识推理，隐式地保存在参数中的知识往往使得其被下游应用使用时效果不佳。在本文中，我们介绍了一个通用框架，允许借助 LLMs 构建知识库，专门用于处理网络新闻。该框架将基于规则的新闻信息提取器（NewsIE）应用于新闻项，以提取其关系元组，称为知识库，然后将其与 LLMs 获得的新闻项的隐式知识事实进行图卷积，以进行分类。它涉及两个轻量级组件：1）NewsIE：用于以关系元组的形式提取每个新闻项的结构信息；2）BERTGraph：用于将隐式知识事实与 NewsIE 提取的关系元组进行图卷积。我们在不同的新闻相关数据集下对我们的框架进行了新闻类别分类的评估，取得了有希望的实验结果。

> Large Language Models (LLMs) have received considerable interest in wide applications lately. During pre-training via massive datasets, such a model implicitly memorizes the factual knowledge of trained datasets in its hidden parameters. However, knowledge held implicitly in parameters often makes its use by downstream applications ineffective due to the lack of common-sense reasoning. In this article, we introduce a general framework that permits to build knowledge bases with an aid of LLMs, tailored for processing Web news. The framework applies a rule-based News Information Extractor (NewsIE) to news items for extracting their relational tuples, referred to as knowledge bases, which are then graph-convoluted with the implicit knowledge facts of news items obtained by LLMs, for their classification. It involves two lightweight components: 1) NewsIE: for extracting the structural information of every news item, in the form of relational tuples; 2) BERTGraph: for graph convoluting the implicit knowledge facts with relational tuples extracted by NewsIE. We have evaluated our framework under different news-related datasets for news category classification, with promising experimental results.

[Arxiv](https://arxiv.org/abs/2411.08278)