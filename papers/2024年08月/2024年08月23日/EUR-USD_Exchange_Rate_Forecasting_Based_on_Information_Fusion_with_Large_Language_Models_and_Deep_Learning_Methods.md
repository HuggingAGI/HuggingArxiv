# 结合大型语言模型与深度学习技术，本研究探索了EUR-USD汇率的预测方法，通过信息融合提升预测精度。

发布时间：2024年08月23日

`LLM应用` `外汇市场`

> EUR-USD Exchange Rate Forecasting Based on Information Fusion with Large Language Models and Deep Learning Methods

# 摘要

> 预测欧元/美元汇率对多方至关重要。本文提出的IUS框架，融合新闻与分析的非结构化文本及结构化财务数据，显著提升预测精度。通过大型语言模型处理文本，结合定量数据，经Optuna优化的Bi-LSTM模型精准预测汇率，性能超越传统基准，MAE和RMSE分别降低10.69%和9.56%。实验证实，数据融合策略优于单一结构化数据，而精选的12个定量特征与文本特征组合效果最佳。IUS框架与Optuna-Bi-LSTM模型，通过整合多源数据，为汇率预测开辟了新路径。

> Accurate forecasting of the EUR/USD exchange rate is crucial for investors, businesses, and policymakers. This paper proposes a novel framework, IUS, that integrates unstructured textual data from news and analysis with structured data on exchange rates and financial indicators to enhance exchange rate prediction. The IUS framework employs large language models for sentiment polarity scoring and exchange rate movement classification of texts. These textual features are combined with quantitative features and input into a Causality-Driven Feature Generator. An Optuna-optimized Bi-LSTM model is then used to forecast the EUR/USD exchange rate. Experiments demonstrate that the proposed method outperforms benchmark models, reducing MAE by 10.69% and RMSE by 9.56% compared to the best performing baseline. Results also show the benefits of data fusion, with the combination of unstructured and structured data yielding higher accuracy than structured data alone. Furthermore, feature selection using the top 12 important quantitative features combined with the textual features proves most effective. The proposed IUS framework and Optuna-Bi-LSTM model provide a powerful new approach for exchange rate forecasting through multi-source data integration.

[Arxiv](https://arxiv.org/abs/2408.13214)