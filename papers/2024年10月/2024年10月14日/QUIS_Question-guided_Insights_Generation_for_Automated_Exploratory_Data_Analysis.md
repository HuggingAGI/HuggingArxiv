# QUIS：通过问题引导实现自动化探索性数据分析的洞察生成

发布时间：2024年10月14日

`其他` `数据分析` `人工智能`

> QUIS: Question-guided Insights Generation for Automated Exploratory Data Analysis

# 摘要

> 探索性数据分析 (EDA) 旨在从海量数据中挖掘有价值的信息，这需要深入的数据探索和分析。自动化数据探索 (ADE) 系统借助大型语言模型和强化学习，力求实现完全自动化。然而，这些系统仍需人工设定目标，可能限制了见解的深度；而全自动系统则需大量计算资源和重新训练。为此，我们推出了 QUIS，一个全自动 EDA 系统，分为两阶段：问题生成 (QUGen) 驱动见解生成 (ISGen)。QUGen 模块通过迭代优化问题，覆盖更广，无需人工干预。ISGen 模块则直接分析数据，生成多维度见解，无需预训练，灵活适应新数据集。

> Discovering meaningful insights from a large dataset, known as Exploratory Data Analysis (EDA), is a challenging task that requires thorough exploration and analysis of the data. Automated Data Exploration (ADE) systems use goal-oriented methods with Large Language Models and Reinforcement Learning towards full automation. However, these methods require human involvement to anticipate goals that may limit insight extraction, while fully automated systems demand significant computational resources and retraining for new datasets. We introduce QUIS, a fully automated EDA system that operates in two stages: insight generation (ISGen) driven by question generation (QUGen). The QUGen module generates questions in iterations, refining them from previous iterations to enhance coverage without human intervention or manually curated examples. The ISGen module analyzes data to produce multiple relevant insights in response to each question, requiring no prior training and enabling QUIS to adapt to new datasets.

[Arxiv](https://arxiv.org/abs/2410.10270)