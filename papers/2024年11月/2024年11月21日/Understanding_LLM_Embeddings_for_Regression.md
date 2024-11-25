# 对用于回归的 LLM 嵌入的理解

发布时间：2024年11月21日

`LLM应用` `回归分析` `语言模型`

> Understanding LLM Embeddings for Regression

# 摘要

> 随着大型语言模型（LLMs）在灵活处理字符串信息方面的兴起，回归成为其一个自然应用，具体做法是将字符串表示预处理为 LLM 嵌入，作为度量预测的下游特征。在本文中，我们率先对基于嵌入的回归展开了全面研究之一，并表明在高维回归任务中，以 LLM 嵌入作为特征可能比传统特征工程效果更佳。这种回归性能部分归因于 LLM 嵌入在数值数据上于特征空间内本质上保持了利普希茨连续性。此外，我们对不同模型效果的贡献进行了量化，其中最显著的是模型大小和语言理解，令人惊讶的是，我们发现它们并非总能提升回归性能。

> With the rise of large language models (LLMs) for flexibly processing information as strings, a natural application is regression, specifically by preprocessing string representations into LLM embeddings as downstream features for metric prediction. In this paper, we provide one of the first comprehensive investigations into embedding-based regression and demonstrate that LLM embeddings as features can be better for high-dimensional regression tasks than using traditional feature engineering. This regression performance can be explained in part due to LLM embeddings over numeric data inherently preserving Lipschitz continuity over the feature space. Furthermore, we quantify the contribution of different model effects, most notably model size and language understanding, which we find surprisingly do not always improve regression performance.

[Arxiv](https://arxiv.org/abs/2411.14708)