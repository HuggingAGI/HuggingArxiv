# 利用 LLM 增强通货膨胀的即时预测：新闻情绪分析

发布时间：2024年10月26日

`LLM应用` `经济预测`

> Enhancing Inflation Nowcasting with LLM: Sentiment Analysis on News

# 摘要

> 本研究探索了将大型语言模型（LLMs）融入经典的通货膨胀现期预测框架，尤其是在像 COVID-19 大流行这样的高通胀波动时期。我们推出了 InflaBERT，这是基于 BERT 并经过微调的 LLM，用于预测新闻中与通胀相关的情绪。我们利用该模型生成了 NEWS，这是一个能捕捉每月有关通胀新闻情绪的指数。把我们的预期指数纳入仅基于宏观经济自回归过程的克利夫兰联邦储备银行模型中，在大流行期间现期预测的准确性有了些许提升。这彰显了将情绪分析与传统经济指标相结合的潜力，建议进一步开展研究来完善这些方法，以便更好地进行实时通胀监测。源代码可在 https://github.com/paultltc/InflaBERT 获取。

> This study explores the integration of large language models (LLMs) into classic inflation nowcasting frameworks, particularly in light of high inflation volatility periods such as the COVID-19 pandemic. We propose InflaBERT, a BERT-based LLM fine-tuned to predict inflation-related sentiment in news. We use this model to produce NEWS, an index capturing the monthly sentiment of the news regarding inflation. Incorporating our expectation index into the Cleveland Fed's model, which is only based on macroeconomic autoregressive processes, shows a marginal improvement in nowcast accuracy during the pandemic. This highlights the potential of combining sentiment analysis with traditional economic indicators, suggesting further research to refine these methodologies for better real-time inflation monitoring. The source code is available at https://github.com/paultltc/InflaBERT.

[Arxiv](https://arxiv.org/abs/2410.20198)