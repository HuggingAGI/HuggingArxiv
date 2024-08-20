# PLUTUS，一款精心预训练的大型统一Transformer模型，能够揭示金融时间序列中的规律。

发布时间：2024年08月19日

`LLM应用` `时间序列分析`

> PLUTUS: A Well Pre-trained Large Unified Transformer can Unveil Financial Time Series Regularities

# 摘要

> 金融时间序列建模对市场行为的理解和预测至关重要，但受限于非线性、非平稳性和高噪声等挑战。传统模型因这些难题及计算资源限制而难以捕捉复杂模式。借鉴NLP领域大型语言模型的成功，我们推出了**PLUTUS**——一个预训练的大型统一Transformer模型，旨在揭示金融时间序列的规律。PLUTUS通过结合对比学习和自编码技术的可逆嵌入模块，实现了原始数据与嵌入间的一对一映射。其核心架构TimeFormer利用注意力机制有效处理高噪声序列，并创新性地整合了跨变量与时间维度的特征捕捉机制。在包含1000亿数据的庞大数据集上预训练，PLUTUS专为复杂金融环境设计。作为首个开源、拥有超十亿参数的预训练金融时间序列模型，PLUTUS在多项任务中表现卓越，展现了出色的迁移能力，并为金融建模奠定了坚实基础。我们的研究不仅为金融时间序列预训练提供了技术指引，更在该领域树立了新标杆。

> Financial time series modeling is crucial for understanding and predicting market behaviors but faces challenges such as non-linearity, non-stationarity, and high noise levels. Traditional models struggle to capture complex patterns due to these issues, compounded by limitations in computational resources and model capacity. Inspired by the success of large language models in NLP, we introduce \textbf{PLUTUS}, a \textbf{P}re-trained \textbf{L}arge \textbf{U}nified \textbf{T}ransformer-based model that \textbf{U}nveils regularities in financial time \textbf{S}eries. PLUTUS uses an invertible embedding module with contrastive learning and autoencoder techniques to create an approximate one-to-one mapping between raw data and patch embeddings. TimeFormer, an attention based architecture, forms the core of PLUTUS, effectively modeling high-noise time series. We incorporate a novel attention mechanisms to capture features across both variable and temporal dimensions. PLUTUS is pre-trained on an unprecedented dataset of 100 billion observations, designed to thrive in noisy financial environments. To our knowledge, PLUTUS is the first open-source, large-scale, pre-trained financial time series model with over one billion parameters. It achieves state-of-the-art performance in various tasks, demonstrating strong transferability and establishing a robust foundational model for finance. Our research provides technical guidance for pre-training financial time series data, setting a new standard in the field.

[Arxiv](https://arxiv.org/abs/2408.10111)