# StockTime：专为时间序列设计的大型语言模型架构，精准预测股票价格

发布时间：2024年08月24日

`LLM应用` `股票市场`

> StockTime: A Time Series Specialized Large Language Model Architecture for Stock Price Prediction

# 摘要

> 股票价格预测在金融领域至关重要，且研究历史悠久。近期，大型语言模型 (LLM) 为提升预测精度提供了新途径。尽管金融大型语言模型 (FinLLM) 在金融 NLP 任务中表现优异，但在股票价格预测上仍面临挑战。首先，整合时间序列数据与自然语言以充分发挥其潜力仍具复杂性。其次，FinLLM 侧重分析与解释性，可能忽略时间序列数据的核心特征。此外，金融市场充斥的虚假与冗余信息常导致模型预测不准确。为此，我们推出 StockTime，一种专为股票价格设计的新型 LLM 架构。StockTime 不同于 FinLLM，它将股票价格视为连续 token，直接提取相关性、趋势与时间戳等文本信息，并将文本与时间序列数据融合于嵌入空间，从而实现对任意回溯期股票价格的精准预测。实验证明，StockTime 在提升预测精度的同时，有效降低了内存与运行成本。

> The stock price prediction task holds a significant role in the financial domain and has been studied for a long time. Recently, large language models (LLMs) have brought new ways to improve these predictions. While recent financial large language models (FinLLMs) have shown considerable progress in financial NLP tasks compared to smaller pre-trained language models (PLMs), challenges persist in stock price forecasting. Firstly, effectively integrating the modalities of time series data and natural language to fully leverage these capabilities remains complex. Secondly, FinLLMs focus more on analysis and interpretability, which can overlook the essential features of time series data. Moreover, due to the abundance of false and redundant information in financial markets, models often produce less accurate predictions when faced with such input data. In this paper, we introduce StockTime, a novel LLM-based architecture designed specifically for stock price data. Unlike recent FinLLMs, StockTime is specifically designed for stock price time series data. It leverages the natural ability of LLMs to predict the next token by treating stock prices as consecutive tokens, extracting textual information such as stock correlations, statistical trends and timestamps directly from these stock prices. StockTime then integrates both textual and time series data into the embedding space. By fusing this multimodal data, StockTime effectively predicts stock prices across arbitrary look-back periods. Our experiments demonstrate that StockTime outperforms recent LLMs, as it gives more accurate predictions while reducing memory usage and runtime costs.

[Arxiv](https://arxiv.org/abs/2409.08281)