# 探究大规模语言模型训练中局部随机梯度下降的缩放规律

发布时间：2024年09月20日

`LLM理论` `云计算` `边缘计算`

> Exploring Scaling Laws for Local SGD in Large Language Model Training

# 摘要

> 本文探讨了 LLM 训练中本地 SGD 的缩放定律，这是一种适用于松散连接设备的分布式优化算法。实验表明，在同等条件下，本地 SGD 的表现与传统方法不相上下。我们还研究了其在多集群和边缘计算环境中的应用。研究揭示了多集群 LLM 训练的有效条件，并探讨了边缘计算在 LLM 训练中的潜力与局限。这表明本地 SGD 可作为传统大集群训练的替代方案。

> This paper investigates scaling laws for local SGD in LLM training, a distributed optimization algorithm that facilitates training on loosely connected devices. Through extensive experiments, we show that local SGD achieves competitive results compared to conventional methods, given equivalent model parameters, datasets, and computational resources. Furthermore, we explore the application of local SGD in various practical scenarios, including multi-cluster setups and edge computing environments. Our findings elucidate the necessary conditions for effective multi-cluster LLM training and examine the potential and limitations of leveraging edge computing resources in the LLM training process. This demonstrates its viability as an alternative to single large-cluster training.

[Arxiv](https://arxiv.org/abs/2409.13198)