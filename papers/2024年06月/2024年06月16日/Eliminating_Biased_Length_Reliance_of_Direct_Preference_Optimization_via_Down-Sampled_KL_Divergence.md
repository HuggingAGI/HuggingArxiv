# 借助下采样KL散度，我们消除了直接偏好优化中对偏置长度的依赖，从而提升了算法的公正性与效率。

发布时间：2024年06月16日

`LLM应用

这篇论文主要讨论了直接偏好优化（DPO）算法在大型语言模型（LLMs）中的应用，特别是在解决“冗长”问题上的改进。论文通过分析DPO算法对序列长度的依赖性，提出了一种新的下采样方法SamPO，以减少这种依赖性并改善模型的性能。这一研究直接关联到LLMs的实际应用问题，即如何优化模型以更好地符合人类偏好，因此属于LLM应用分类。` `人工智能` `语言模型`

> Eliminating Biased Length Reliance of Direct Preference Optimization via Down-Sampled KL Divergence

# 摘要

> 直接偏好优化（DPO）作为一种直接且稳健的算法，已成为将大型语言模型（LLMs）与人类偏好对齐的重要工具，相较于复杂的人类反馈强化学习（RLHF），它提供了一种更直接的解决方案。然而，DPO存在一个显著问题——“冗长”，这是一种在RLHF中也常见的过度优化现象。我们发现，除了数据中的偏差标签外，DPO算法本身对序列长度的依赖也是导致冗长的原因之一。具体而言，DPO中使用的序列级KL散度差异，因令牌长度不同，可能导致奖励评估失准。通过实证分析，我们展示了不同标签长度的数据集中的偏差奖励，并提出了一种名为SamPO的有效下采样方法，以消除这种长度依赖性。在跨越三种规模LLMs和多种条件性与开放式基准的实验中，SamPO显著减轻了冗长问题，通过去偏差的奖励实现了比DPO提升5%至12%的性能改进。相关代码已公开，详情请访问：https://github.com/LuJunru/SamPO/。

> Direct Preference Optimization (DPO) has emerged as a prominent algorithm for the direct and robust alignment of Large Language Models (LLMs) with human preferences, offering a more straightforward alternative to the complex Reinforcement Learning from Human Feedback (RLHF). Despite its promising efficacy, DPO faces a notable drawback: "verbosity", a common over-optimization phenomenon also observed in RLHF. While previous studies mainly attributed verbosity to biased labels within the data, we propose that the issue also stems from an inherent algorithmic length reliance in DPO. Specifically, we suggest that the discrepancy between sequence-level Kullback-Leibler (KL) divergences between chosen and rejected sequences, used in DPO, results in overestimated or underestimated rewards due to varying token lengths. Empirically, we utilize datasets with different label lengths to demonstrate the presence of biased rewards. We then introduce an effective downsampling approach, named SamPO, to eliminate potential length reliance. Our experimental evaluations, conducted across three LLMs of varying scales and a diverse array of conditional and open-ended benchmarks, highlight the efficacy of SamPO in mitigating verbosity, achieving improvements of 5% to 12% over DPO through debaised rewards. Our codes can be accessed at: https://github.com/LuJunru/SamPO/.

![借助下采样KL散度，我们消除了直接偏好优化中对偏置长度的依赖，从而提升了算法的公正性与效率。](../../../paper_images/2406.10957/introduction.png)

![借助下采样KL散度，我们消除了直接偏好优化中对偏置长度的依赖，从而提升了算法的公正性与效率。](../../../paper_images/2406.10957/rewards.png)

![借助下采样KL散度，我们消除了直接偏好优化中对偏置长度的依赖，从而提升了算法的公正性与效率。](../../../paper_images/2406.10957/group.png)

![借助下采样KL散度，我们消除了直接偏好优化中对偏置长度的依赖，从而提升了算法的公正性与效率。](../../../paper_images/2406.10957/stability.png)

![借助下采样KL散度，我们消除了直接偏好优化中对偏置长度的依赖，从而提升了算法的公正性与效率。](../../../paper_images/2406.10957/topk.png)

![借助下采样KL散度，我们消除了直接偏好优化中对偏置长度的依赖，从而提升了算法的公正性与效率。](../../../paper_images/2406.10957/debias.png)

![借助下采样KL散度，我们消除了直接偏好优化中对偏置长度的依赖，从而提升了算法的公正性与效率。](../../../paper_images/2406.10957/alpacaeval.png)

[Arxiv](https://arxiv.org/abs/2406.10957)