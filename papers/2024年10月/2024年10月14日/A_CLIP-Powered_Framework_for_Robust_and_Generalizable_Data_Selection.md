# 基于 CLIP 的框架，助力数据选择更稳健、更通用

发布时间：2024年10月14日

`其他` `数据科学` `机器学习`

> A CLIP-Powered Framework for Robust and Generalizable Data Selection

# 摘要

> 近年来，大规模数据集推动了深度学习模型的显著进步，但训练这些数据集带来的存储和计算成本巨大。现实世界的数据集往往包含冗余和噪声，影响训练效率和模型性能。数据选择技术旨在从海量数据中挑选最具代表性的样本，以降低训练成本并缩小性能差距。现有方法多依赖单一模态信息评估样本重要性，容易在处理噪声数据时出现偏差。为此，我们提出了一种基于 CLIP 的多模态数据选择框架，通过数据集适应、样本评分和选择优化三大模块，全面评估样本影响并优化选择结果。实验证明，该方法在多个基准数据集上均优于现有最先进技术，有效剔除噪声数据，提升数据质量和模型性能。这不仅加速了训练过程，更提高了数据的整体质量。

> Large-scale datasets have been pivotal to the advancements of deep learning models in recent years, but training on such large datasets invariably incurs substantial storage and computational overhead. Meanwhile, real-world datasets often contain redundant and noisy data, imposing a negative impact on training efficiency and model performance. Data selection has shown promise in identifying the most representative samples from the entire dataset, which aims to minimize the performance gap with reduced training costs. Existing works typically rely on single-modality information to assign importance scores for individual samples, which may lead to inaccurate assessments, especially when dealing with noisy or corrupted samples. To address this limitation, we propose a novel CLIP-powered data selection framework that leverages multimodal information for more robust and generalizable sample selection. Specifically, our framework consists of three key modules-dataset adaptation, sample scoring, and selection optimization-that together harness extensive pre-trained multimodal knowledge to comprehensively assess sample influence and optimize the selection results through multi-objective optimization. Extensive experiments demonstrate that our approach consistently outperforms existing state-of-the-art baselines on various benchmark datasets. Notably, our method effectively removes noisy or damaged samples from the dataset, enabling it to achieve even higher performance with less data. This indicates that it is not only a way to accelerate training but can also improve overall data quality.

[Arxiv](https://arxiv.org/abs/2410.11215)