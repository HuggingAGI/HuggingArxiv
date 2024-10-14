# 半监督噪声混合专家模型学习

发布时间：2024年10月11日

`LLM理论` `机器学习` `数据科学`

> Semi-Supervised Learning of Noisy Mixture of Experts Models

# 摘要

> 专家混合 (MoE) 模型在大语言模型时代再次受到关注，它通过学习一组预测“专家”和一个控制每个专家影响力的“门控函数”，在复杂数据环境中表现出色。面对广泛存在的未标记数据和稀缺的标记数据，我们提出了一种新的 MoE 模型半监督学习方法。该方法放松了传统假设，认为未标记数据的聚类结构与专家影响力之间存在噪声连接，并采用基于最小修剪平方的算法，即使在数据未对齐的情况下也能有效运作。理论分析和实际数据验证均表明，该方法在特定条件下能够实现近似参数的收敛率，展现出显著的有效性。

> The mixture of experts (MoE) model is a versatile framework for predictive modeling that has gained renewed interest in the age of large language models. A collection of predictive ``experts'' is learned along with a ``gating function'' that controls how much influence each expert is given when a prediction is made. This structure allows relatively simple models to excel in complex, heterogeneous data settings. In many contemporary settings, unlabeled data are widely available while labeled data are difficult to obtain. Semi-supervised learning methods seek to leverage the unlabeled data. We propose a novel method for semi-supervised learning of MoE models. We start from a semi-supervised MoE model that was developed by oceanographers that makes the strong assumption that the latent clustering structure in unlabeled data maps directly to the influence that the gating function should give each expert in the supervised task. We relax this assumption, imagining a noisy connection between the two, and propose an algorithm based on least trimmed squares, which succeeds even in the presence of misaligned data. Our theoretical analysis characterizes the conditions under which our approach yields estimators with a near-parametric rate of convergence. Simulated and real data examples demonstrate the method's efficacy.

[Arxiv](https://arxiv.org/abs/2410.09039)