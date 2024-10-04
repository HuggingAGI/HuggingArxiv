# 动态梯度对齐助力在线数据混合

发布时间：2024年10月03日

`LLM理论` `人工智能` `数据科学`

> Dynamic Gradient Alignment for Online Data Mixing

# 摘要

> 训练数据混合物的组成对 LLM 的下游任务表现至关重要。我们旨在找到一种最佳数据混合物，使 LLM 在仅提供少量示例的情况下，能够专门化于特定任务。传统方法包括临时重新加权、重要性采样和梯度对齐技术。本文聚焦于梯度对齐，并引入了动态梯度对齐 (DGA) 算法。DGA 动态调整预训练数据混合物，使模型梯度与特定任务模型的梯度尽可能对齐，且无需重新训练模型。实验表明，DGA 在预训练数据集小或专业数据不足的情况下，显著优于重要性采样。这为在数据受限的环境中优化 LLM 表现提供了实用方案。

> The composition of training data mixtures is critical for effectively training large language models (LLMs), as it directly impacts their performance on downstream tasks. Our goal is to identify an optimal data mixture to specialize an LLM for a specific task with access to only a few examples. Traditional approaches to this problem include ad-hoc reweighting methods, importance sampling, and gradient alignment techniques. This paper focuses on gradient alignment and introduces Dynamic Gradient Alignment (DGA), a scalable online gradient alignment algorithm. DGA dynamically estimates the pre-training data mixture on which the models' gradients align as well as possible with those of the model on the specific task. DGA is the first gradient alignment approach that incurs minimal overhead compared to standard pre-training and outputs a competitive model, eliminating the need for retraining the model. Experimentally, we demonstrate significant improvements over importance sampling in two key scenarios: (i) when the pre-training set is small and importance sampling overfits due to limited data; and (ii) when there is insufficient specialized data, trapping importance sampling on narrow pockets of data. Our findings underscore the effectiveness of gradient alignment methods in optimizing training data mixtures, particularly in data-constrained environments, and offer a practical solution for enhancing LLM performance on specific tasks with limited data availability.

[Arxiv](https://arxiv.org/abs/2410.02498)