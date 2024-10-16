# LLM-Mixer：在 LLM 中实现时间序列预测的多尺度混合技术

发布时间：2024年10月15日

`LLM应用` `时间序列预测`

> LLM-Mixer: Multiscale Mixing in LLMs for Time Series Forecasting

# 摘要

> 时间序列预测在复杂的多尺度模式下尤为棘手。为此，我们推出了 LLM-Mixer 框架，通过融合多尺度时间序列分解与预训练 LLM，显著提升预测精度。该框架通过多分辨率分解数据，并借助冻结 LLM 和特制文本提示，精准捕捉短期波动与长期趋势。实验证明，LLM-Mixer 在多元与单变量数据集上均表现优异，超越了当前最先进模型。这表明，多尺度分析与 LLM 的结合，为高效且可扩展的时间序列预测开辟了新路径。

> Time series forecasting remains a challenging task, particularly in the context of complex multiscale temporal patterns. This study presents LLM-Mixer, a framework that improves forecasting accuracy through the combination of multiscale time-series decomposition with pre-trained LLMs (Large Language Models). LLM-Mixer captures both short-term fluctuations and long-term trends by decomposing the data into multiple temporal resolutions and processing them with a frozen LLM, guided by a textual prompt specifically designed for time-series data. Extensive experiments conducted on multivariate and univariate datasets demonstrate that LLM-Mixer achieves competitive performance, outperforming recent state-of-the-art models across various forecasting horizons. This work highlights the potential of combining multiscale analysis and LLMs for effective and scalable time-series forecasting.

[Arxiv](https://arxiv.org/abs/2410.11674)