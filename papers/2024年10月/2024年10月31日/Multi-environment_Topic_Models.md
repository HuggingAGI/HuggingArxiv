# 多环境的主题模型

发布时间：2024年10月31日

`其他`

> Multi-environment Topic Models

# 摘要

> 概率主题模型是从大型文本数据集中挖掘潜在主题的有力手段。在众多文本数据集中，我们还能观察到每份文档的协变量（比如来源、风格、政治归属），它们充当着调节“全局”（与环境无关）主题表征的环境因素。精准学习这些表征对于在未曾见过的环境中对新文档进行预测以及估算主题对现实结果的因果影响至关重要。为此，我们引入了多环境主题模型（MTM），这是一种无监督的概率模型，能够分离全局和特定环境的术语。通过对从广告到推文和演讲等各类政治内容展开实验，我们发现 MTM 生成了带有不同特定环境词汇的可解释全局主题。在多环境数据方面，MTM 在分布内和分布外的表现都优于强劲的基线。它还能够探寻到准确的因果效应。

> Probabilistic topic models are a powerful tool for extracting latent themes from large text datasets. In many text datasets, we also observe per-document covariates (e.g., source, style, political affiliation) that act as environments that modulate a "global" (environment-agnostic) topic representation. Accurately learning these representations is important for prediction on new documents in unseen environments and for estimating the causal effect of topics on real-world outcomes. To this end, we introduce the Multi-environment Topic Model (MTM), an unsupervised probabilistic model that separates global and environment-specific terms. Through experimentation on various political content, from ads to tweets and speeches, we show that the MTM produces interpretable global topics with distinct environment-specific words. On multi-environment data, the MTM outperforms strong baselines in and out-of-distribution. It also enables the discovery of accurate causal effects.

[Arxiv](https://arxiv.org/abs/2410.24126)