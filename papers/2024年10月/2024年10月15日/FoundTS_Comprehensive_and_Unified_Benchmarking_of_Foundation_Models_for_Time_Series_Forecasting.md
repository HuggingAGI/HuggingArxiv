# FoundTS：时间序列预测基础模型的全面统一基准

发布时间：2024年10月15日

`LLM应用` `能源管理`

> FoundTS: Comprehensive and Unified Benchmarking of Foundation Models for Time Series Forecasting

# 摘要

> 时间序列预测 (TSF) 在金融、天气服务和能源管理等多个领域中至关重要。尽管 TSF 方法不断涌现，但许多方法在新领域上的泛化能力较差，需要特定领域的数据和模型训练。基础模型通过在大规模数据上预训练，展现出在新数据上的强大推理能力，推动了新的 TSF 基础模型的兴起。我们提出了 FoundTS 基准，以全面、公平地评估这些模型。FoundTS 涵盖了多种基础模型，并支持零-shot、few-shot 和 full-shot 预测策略，确保评估的全面性。此外，FoundTS 标准化了评估流程，确保公平性。我们基于此对多个领域的数据集进行了广泛评估，揭示了现有模型的优缺点和未来设计方向。代码和数据集可在 https://anonymous.4open.science/r/FoundTS-C2B0 获取。

> Time Series Forecasting (TSF) is key functionality in numerous fields, including in finance, weather services, and energy management. While TSF methods are emerging these days, many of them require domain-specific data collection and model training and struggle with poor generalization performance on new domains. Foundation models aim to overcome this limitation. Pre-trained on large-scale language or time series data, they exhibit promising inferencing capabilities in new or unseen data. This has spurred a surge in new TSF foundation models. We propose a new benchmark, FoundTS, to enable thorough and fair evaluation and comparison of such models. FoundTS covers a variety of TSF foundation models, including those based on large language models and those pretrained on time series. Next, FoundTS supports different forecasting strategies, including zero-shot, few-shot, and full-shot, thereby facilitating more thorough evaluations. Finally, FoundTS offers a pipeline that standardizes evaluation processes such as dataset splitting, loading, normalization, and few-shot sampling, thereby facilitating fair evaluations. Building on this, we report on an extensive evaluation of TSF foundation models on a broad range of datasets from diverse domains and with different statistical characteristics. Specifically, we identify pros and cons and inherent limitations of existing foundation models, and we identify directions for future model design. We make our code and datasets available at https://anonymous.4open.science/r/FoundTS-C2B0.

[Arxiv](https://arxiv.org/abs/2410.11802)