# ScalingFilter：借助逆向缩放定律，精准评估数据质量

发布时间：2024年08月15日

`LLM理论` `人工智能` `数据处理`

> ScalingFilter: Assessing Data Quality through Inverse Utilization of Scaling Laws

# 摘要

> 高质量数据对大型语言模型预训练至关重要。然而，现有质量过滤方法依赖已知高质量数据集，可能带来偏差并损害多样性。本文提出ScalingFilter，一种基于两模型困惑度差异评估文本质量的新方法，有效消除了参考数据集的影响。理论分析表明，ScalingFilter是对缩放定律的逆向应用。实验显示，在同一数据源上使用不同过滤器训练的1.3B参数模型中，ScalingFilter能提升预训练模型的零-shot性能。为评估过滤偏差，我们引入语义多样性指标，利用文本嵌入模型进行语义表示。广泛实验证明，语义多样性是数据集多样性的可靠指标，ScalingFilter在保持下游性能的同时，实现了语义多样性的最佳平衡。

> High-quality data is crucial for the pre-training performance of large language models. Unfortunately, existing quality filtering methods rely on a known high-quality dataset as reference, which can introduce potential bias and compromise diversity. In this paper, we propose ScalingFilter, a novel approach that evaluates text quality based on the perplexity difference between two language models trained on the same data, thereby eliminating the influence of the reference dataset in the filtering process. An theoretical analysis shows that ScalingFilter is equivalent to an inverse utilization of scaling laws. Through training models with 1.3B parameters on the same data source processed by various quality filters, we find ScalingFilter can improve zero-shot performance of pre-trained models in downstream tasks. To assess the bias introduced by quality filtering, we introduce semantic diversity, a metric of utilizing text embedding models for semantic representations. Extensive experiments reveal that semantic diversity is a reliable indicator of dataset diversity, and ScalingFilter achieves an optimal balance between downstream performance and semantic diversity.

[Arxiv](https://arxiv.org/abs/2408.08310)