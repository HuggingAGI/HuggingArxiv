# Time-MoE：融合专家智慧的十亿级时间序列基础模型

发布时间：2024年09月24日

`LLM应用` `时间序列预测` `人工智能`

> Time-MoE: Billion-Scale Time Series Foundation Models with Mixture of Experts

# 摘要

> 深度学习在时间序列预测领域取得了长足进步，但预训练模型仍面临规模和成本的挑战。为此，我们推出了Time-MoE，一种可扩展且高效的架构，旨在预训练更大、更强大的预测模型，同时降低推理成本。通过稀疏混合专家（MoE）设计，Time-MoE仅激活部分网络进行预测，既减少计算负担又保持高模型容量。这使得Time-MoE在不增加推理成本的情况下有效扩展。Time-MoE由一系列仅解码器的Transformer模型组成，支持灵活的预测范围。我们在新引入的Time-300B数据集上预训练了这些模型，该数据集跨越9个领域，包含超过3000亿个时间点。我们首次将时间序列基础模型扩展到24亿参数，显著提升了预测精度。我们的研究验证了时间序列预测中训练令牌和模型规模的扩展规律。与同等参数或计算预算的密集模型相比，我们的模型表现更优。这些进展使Time-MoE成为解决实际时间序列预测问题的顶尖解决方案，兼具卓越能力、效率和灵活性。

> Deep learning for time series forecasting has seen significant advancements over the past decades. However, despite the success of large-scale pre-training in language and vision domains, pre-trained time series models remain limited in scale and operate at a high cost, hindering the development of larger capable forecasting models in real-world applications. In response, we introduce Time-MoE, a scalable and unified architecture designed to pre-train larger, more capable forecasting foundation models while reducing inference costs. By leveraging a sparse mixture-of-experts (MoE) design, Time-MoE enhances computational efficiency by activating only a subset of networks for each prediction, reducing computational load while maintaining high model capacity. This allows Time-MoE to scale effectively without a corresponding increase in inference costs. Time-MoE comprises a family of decoder-only transformer models that operate in an auto-regressive manner and support flexible forecasting horizons with varying input context lengths. We pre-trained these models on our newly introduced large-scale data Time-300B, which spans over 9 domains and encompassing over 300 billion time points. For the first time, we scaled a time series foundation model up to 2.4 billion parameters, achieving significantly improved forecasting precision. Our results validate the applicability of scaling laws for training tokens and model size in the context of time series forecasting. Compared to dense models with the same number of activated parameters or equivalent computation budgets, our models consistently outperform them by large margin. These advancements position Time-MoE as a state-of-the-art solution for tackling real-world time series forecasting challenges with superior capability, efficiency, and flexibility.

[Arxiv](https://arxiv.org/abs/2409.16040)