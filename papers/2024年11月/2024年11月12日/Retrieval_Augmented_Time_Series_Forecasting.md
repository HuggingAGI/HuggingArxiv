# 检索增强型时间序列预测

发布时间：2024年11月12日

`RAG` `时间序列`

> Retrieval Augmented Time Series Forecasting

# 摘要

> 检索增强生成（RAG）是现代大型语言模型（LLM）系统的核心组成部分，特别是在需要最新信息以准确响应用户查询或当查询超出训练数据范围的情况下。时间序列基础模型（TSFM）的出现，如 Chronos，以及在各种时间序列领域实现有效零样本预测性能的需求引发了一个问题：RAG 的优势是否同样适用于时间序列预测？在本文中，我们主张时间序列数据的动态和事件驱动性质使 RAG 成为 TSFMs 的关键组成部分，并为时间序列预测引入了一个原则性的 RAG 框架，称为检索增强预测（RAF）。在 RAF 中，我们开发了检索相关时间序列示例并将其纳入预测的有效策略。通过实验和机制研究，我们证明 RAF 确实提高了不同时间序列领域的预测准确性，并且对于更大的 TSFM 规模，改进更为显著。

> Retrieval-augmented generation (RAG) is a central component of modern LLM systems, particularly in scenarios where up-to-date information is crucial for accurately responding to user queries or when queries exceed the scope of the training data. The advent of time-series foundation models (TSFM), such as Chronos, and the need for effective zero-shot forecasting performance across various time-series domains motivates the question: Do benefits of RAG similarly carry over to time series forecasting? In this paper, we advocate that the dynamic and event-driven nature of time-series data makes RAG a crucial component of TSFMs and introduce a principled RAG framework for time-series forecasting, called Retrieval Augmented Forecasting (RAF). Within RAF, we develop efficient strategies for retrieving related time-series examples and incorporating them into forecast. Through experiments and mechanistic studies, we demonstrate that RAF indeed improves the forecasting accuracy across diverse time series domains and the improvement is more significant for larger TSFM sizes.

[Arxiv](https://arxiv.org/abs/2411.08249)