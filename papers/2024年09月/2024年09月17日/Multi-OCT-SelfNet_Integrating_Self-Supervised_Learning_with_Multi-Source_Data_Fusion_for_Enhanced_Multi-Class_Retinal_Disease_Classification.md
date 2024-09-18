# Multi-OCT-SelfNet：融合自监督学习与多源数据，提升多类视网膜疾病分类效果

发布时间：2024年09月17日

`LLM应用` `人工智能`

> Multi-OCT-SelfNet: Integrating Self-Supervised Learning with Multi-Source Data Fusion for Enhanced Multi-Class Retinal Disease Classification

# 摘要

> 在医疗领域，隐私问题使得获取大型数据集变得困难。然而，开发强大的视网膜疾病诊断深度学习模型需要大量数据。如何在小型数据集上实现有效泛化仍是一大挑战。数据稀缺性阻碍了可扩展医疗AI解决方案的实际应用。为此，我们整合了多种数据源，通过深入理解多模态数据表示，提升模型性能和泛化能力。基于LLMs的SwinV2自监督框架，进一步增强了模型对OCT图像检测眼病的外推能力。我们采用自监督预训练和下游监督分类器微调的两阶段训练方法。消融研究显示，即使在不同编码器、无数据融合和低数据可用性等条件下，我们的方法依然稳健。研究结果表明，在多样条件下，我们的模型性能稳定，泛化能力优于ResNet-50。

> In the medical domain, acquiring large datasets poses significant challenges due to privacy concerns. Nonetheless, the development of a robust deep-learning model for retinal disease diagnosis necessitates a substantial dataset for training. The capacity to generalize effectively on smaller datasets remains a persistent challenge. The scarcity of data presents a significant barrier to the practical implementation of scalable medical AI solutions. To address this issue, we've combined a wide range of data sources to improve performance and generalization to new data by giving it a deeper understanding of the data representation from multi-modal datasets and developed a self-supervised framework based on large language models (LLMs), SwinV2 to gain a deeper understanding of multi-modal dataset representations, enhancing the model's ability to extrapolate to new data for the detection of eye diseases using optical coherence tomography (OCT) images. We adopt a two-phase training methodology, self-supervised pre-training, and fine-tuning on a downstream supervised classifier. An ablation study conducted across three datasets employing various encoder backbones, without data fusion, with low data availability setting, and without self-supervised pre-training scenarios, highlights the robustness of our method. Our findings demonstrate consistent performance across these diverse conditions, showcasing superior generalization capabilities compared to the baseline model, ResNet-50.

[Arxiv](https://arxiv.org/abs/2409.11375)