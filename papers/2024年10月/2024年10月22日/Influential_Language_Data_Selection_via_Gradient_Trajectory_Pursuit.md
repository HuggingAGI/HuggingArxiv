# 通过梯度轨迹追踪进行有影响力的语言数据选择

发布时间：2024年10月22日

`LLM应用` `语言模型` `数据选择`

> Influential Language Data Selection via Gradient Trajectory Pursuit

# 摘要

> 为训练整理一个理想的数据集一直是构建高性能大型语言模型的核心（Touvron 等人，2023；Achiam 等人，2023；Team 等人，2024）。梯度影响分数（Pruthi 等人，2020；Xia 等人，2024）被证明与模型性能相关，并通常被用作数据选择的标准。然而，现有的方法要么基于单个样本的排名，要么基于低效的匹配过程，导致次优性能或扩展问题。在本文中，我们提出了梯度轨迹追踪（GTP），一种通过在 L0 范数正则化目标下联合选择数据点来追踪梯度轨迹的算法。所提出的算法突出了：（1）联合选择而不是独立的 top-k 选择，这会自动去除重复样本；（2）通过压缩采样过程提高效率，这可以使用分布式框架进一步加速。在实验中，我们在域内和目标域选择基准中展示了该算法，并表明它始终优于 top-k 选择和竞争算法，例如，我们的算法仅选择低至 0.5%的数据就能在目标指令调整任务中实现全性能。

> Curating a desirable dataset for training has been the core of building highly capable large language models (Touvron et al., 2023; Achiam et al., 2023; Team et al.,2024). Gradient influence scores (Pruthi et al., 2020; Xia et al., 2024) are shown to be correlated with model performance and are commonly used as the criterion for data selection. However, existing methods are built upon either individual sample rankings or inefficient matching process, leading to suboptimal performance or scaling up issues.In this paper, we propose Gradient Trajectory Pursuit (GTP), an algorithm that performs pursuit of gradient trajectories via jointly selecting data points under an L0-norm regularized objective. The proposed algorithm highlights: (1) joint selection instead of independent top-k selection, which automatically de-duplicates samples; (2) higher efficiency with compressive sampling processes, which can be further sped up using a distributed framework. In the experiments, we demonstrate the algorithm in both in-domain and target-domain selection benchmarks and show that it outperforms top-k selection and competitive algorithms consistently, for example, our algorithm chooses as low as 0.5% data to achieve full performance on the targeted instruction tuning tasks

[Arxiv](https://arxiv.org/abs/2410.16710)