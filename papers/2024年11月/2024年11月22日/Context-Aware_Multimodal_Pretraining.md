# 具备上下文感知的多模态预训练

发布时间：2024年11月22日

`LLM应用` `多模态学习` `预训练模型`

> Context-Aware Multimodal Pretraining

# 摘要

> 大规模多模态表示学习在测试时成功实现了零样本迁移的优化。然而，标准的预训练范式（对大量图像 - 文本数据进行对比学习）并未明确促使表示支持少样本适应。在本研究中，我们提出了一个简单却精心设计的多模态预训练拓展，让表示能够适应更多的上下文。基于此目标，我们发现视觉 - 语言模型经过训练能够显著增强少样本适应能力：在 21 个下游任务中，测试时样本效率提升高达四倍，平均少样本适应增益超 5%，同时在不同模型规模和训练时长下保持零样本泛化性能。特别地，配备了简单、无需训练且基于度量的适应机制后，我们的表示轻松超越了更复杂且昂贵的基于优化的方案，极大地简化了对新领域的泛化。

> Large-scale multimodal representation learning successfully optimizes for zero-shot transfer at test time. Yet the standard pretraining paradigm (contrastive learning on large amounts of image-text data) does not explicitly encourage representations to support few-shot adaptation. In this work, we propose a simple, but carefully designed extension to multimodal pretraining which enables representations to accommodate additional context. Using this objective, we show that vision-language models can be trained to exhibit significantly increased few-shot adaptation: across 21 downstream tasks, we find up to four-fold improvements in test-time sample efficiency, and average few-shot adaptation gains of over 5%, while retaining zero-shot generalization performance across model scales and training durations. In particular, equipped with simple, training-free, metric-based adaptation mechanisms, our representations easily surpass more complex and expensive optimization-based schemes, vastly simplifying generalization to new domains.

[Arxiv](https://arxiv.org/abs/2411.15099)