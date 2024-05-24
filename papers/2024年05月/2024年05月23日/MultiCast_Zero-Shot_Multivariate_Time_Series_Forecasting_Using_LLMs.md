# MultiCast：借助LLMs实现零-shot多元时间序列预测

发布时间：2024年05月23日

`LLM应用

理由：这篇论文介绍了一种名为MultiCast的方法，该方法利用大型语言模型（LLMs）来预测多变量时间序列的未来值。这种方法涉及创新的令牌复用技术和量化方案，旨在提高LLMs在处理多变量时间序列数据时的效率和准确性。论文通过在真实数据集上的实验结果展示了其方法的性能。因此，这项工作属于LLM在特定应用场景（即时间序列预测）中的应用研究。` `时间序列预测` `数据分析`

> MultiCast: Zero-Shot Multivariate Time Series Forecasting Using LLMs

# 摘要

> 在多个领域中，预测多变量时间序列的未来值至关重要。本研究采用大型语言模型（LLMs）来应对这一挑战。尽管LLMs通常处理一维数据，我们提出的MultiCast方法，一种零-shot的LLM技术，能够预测多变量时间序列。通过三种创新的令牌复用技术，MultiCast在降低数据维度的同时，保留了关键的重复模式。此外，量化方案的引入不仅增强了LLMs对这些模式的识别能力，还大幅减少了令牌的使用，使其更适用于实际场景。我们在三个真实数据集上，通过RMSE和执行时间指标，展示了我们的方法与现有技术的性能对比。

> Predicting future values in multivariate time series is vital across various domains. This work explores the use of large language models (LLMs) for this task. However, LLMs typically handle one-dimensional data. We introduce MultiCast, a zero-shot LLM-based approach for multivariate time series forecasting. It allows LLMs to receive multivariate time series as input, through three novel token multiplexing solutions that effectively reduce dimensionality while preserving key repetitive patterns. Additionally, a quantization scheme helps LLMs to better learn these patterns, while significantly reducing token use for practical applications. We showcase the performance of our approach in terms of RMSE and execution time against state-of-the-art approaches on three real-world datasets.

[Arxiv](https://arxiv.org/abs/2405.14748)