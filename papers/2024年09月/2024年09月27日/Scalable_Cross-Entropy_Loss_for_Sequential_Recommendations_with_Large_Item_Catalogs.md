# 大型商品目录下序列推荐的可扩展交叉熵损失

发布时间：2024年09月27日

`LLM应用` `推荐系统` `大规模计算`

> Scalable Cross-Entropy Loss for Sequential Recommendations with Large Item Catalogs

# 摘要

> 在现代推荐系统中，可扩展性问题至关重要。即使是轻量级架构也可能因中间计算而面临高计算负载，限制了其在实际应用中的实用性。具体而言，尽管全交叉熵（CE）损失在推荐质量上表现卓越，但在处理大型商品目录时，其GPU内存利用率过高。本文提出了一种新的可扩展交叉熵（SCE）损失函数，通过近似CE损失，提高了时间和内存效率，同时不牺牲推荐质量。与传统负采样方法不同，我们的方法采用了一种选择性的GPU高效计算策略，专注于目录中最具信息量的元素，特别是那些可能成为假阳性的元素。通过最大内积搜索近似模型输出子集上的softmax分布，实现了这一目标。实验结果显示，SCE在减少峰值内存使用方面比替代方案有效高达100倍，同时保持或超越其性能指标。这一方法还为大型语言模型等不同领域的大规模发展提供了新的视角。

> Scalability issue plays a crucial role in productionizing modern recommender systems. Even lightweight architectures may suffer from high computational overload due to intermediate calculations, limiting their practicality in real-world applications. Specifically, applying full Cross-Entropy (CE) loss often yields state-of-the-art performance in terms of recommendations quality. Still, it suffers from excessive GPU memory utilization when dealing with large item catalogs. This paper introduces a novel Scalable Cross-Entropy (SCE) loss function in the sequential learning setup. It approximates the CE loss for datasets with large-size catalogs, enhancing both time efficiency and memory usage without compromising recommendations quality. Unlike traditional negative sampling methods, our approach utilizes a selective GPU-efficient computation strategy, focusing on the most informative elements of the catalog, particularly those most likely to be false positives. This is achieved by approximating the softmax distribution over a subset of the model outputs through the maximum inner product search. Experimental results on multiple datasets demonstrate the effectiveness of SCE in reducing peak memory usage by a factor of up to 100 compared to the alternatives, retaining or even exceeding their metrics values. The proposed approach also opens new perspectives for large-scale developments in different domains, such as large language models.

[Arxiv](https://arxiv.org/abs/2409.18721)