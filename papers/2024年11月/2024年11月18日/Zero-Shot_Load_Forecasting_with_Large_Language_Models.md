# 利用大型语言模型进行零-Shot 负载预测

发布时间：2024年11月18日

`LLM应用` `负荷预测`

> Zero-Shot Load Forecasting with Large Language Models

# 摘要

> 深度学习模型在负荷预测领域表现抢眼，不过在应用于新场景时，通常得靠大量数据来训练模型，这就限制了其在数据稀缺场景下的效果。受自然语言处理中预训练语言模型（LLMs）大获成功的启发，本文提出了一种运用先进的 LLM 框架——Chronos 模型的零样本负荷预测方法。凭借其丰富的预训练知识，Chronos 模型能在数据稀缺的情况下实现精准的负荷预测，无需针对特定数据进行大量训练。在五个真实世界数据集上的模拟结果显示，对于不同预测时长（比如 1 至 48 小时）的确定性和概率性负荷预测，Chronos 模型都明显优于九个热门的基线模型，尽管 Chronos 模型既未针对这些特定的负荷数据集做定制化处理，也未进行微调。特别要指出的是，与基线模型相比，Chronos 分别使均方根误差（RMSE）、连续排名概率得分（CRPS）和分位数得分（QS）降低了大约 7.34% - 84.30%、19.63% - 60.06%和 22.83% - 54.49%。这些结果彰显了 Chronos 模型的卓越性和灵活性，使其成为数据稀缺场景中的有效之选。

> Deep learning models have shown strong performance in load forecasting, but they generally require large amounts of data for model training before being applied to new scenarios, which limits their effectiveness in data-scarce scenarios. Inspired by the great success of pre-trained language models (LLMs) in natural language processing, this paper proposes a zero-shot load forecasting approach using an advanced LLM framework denoted as the Chronos model. By utilizing its extensive pre-trained knowledge, the Chronos model enables accurate load forecasting in data-scarce scenarios without the need for extensive data-specific training. Simulation results across five real-world datasets demonstrate that the Chronos model significantly outperforms nine popular baseline models for both deterministic and probabilistic load forecasting with various forecast horizons (e.g., 1 to 48 hours), even though the Chronos model is neither tailored nor fine-tuned to these specific load datasets. Notably, Chronos reduces root mean squared error (RMSE), continuous ranked probability score (CRPS), and quantile score (QS) by approximately 7.34%-84.30%, 19.63%-60.06%, and 22.83%-54.49%, respectively, compared to baseline models. These results highlight the superiority and flexibility of the Chronos model, positioning it as an effective solution in data-scarce scenarios.

[Arxiv](https://arxiv.org/abs/2411.11350)