# 借助 Hölder 散度实现多视图表示学习中的不确定性量化

发布时间：2024年10月29日

`其他` `多视图学习`

> Uncertainty Quantification via Hölder Divergence for Multi-View Representation Learning

# 摘要

> 基于证据的深度学习是不确定性估计领域的新兴范式，能提供可靠预测，额外计算开销极小。现有方法常采用 Kullback-Leibler 散度估计网络预测的不确定性，却忽略了不同模态间的域差距。为此，本文引入基于 Hölder 散度（HD）的新算法，以应对不完整或含噪数据带来的固有不确定性挑战，提升多视图学习的可靠性。通常，我们的方法通过并行网络分支提取多模态的表示，再用 HD 估计预测的不确定性。借助 Dempster-Shafer 理论整合不同模态的不确定性，从而生成综合考虑所有可用表示的结果。从数学角度看，HD 能更优地测量真实数据分布与模型预测分布的“距离”，提升多类识别任务的性能。
    具体来说，我们的方法在所有评估基准上都超越了现有的先进水平。
    我们还在不同的骨干网络上开展了大量实验，以验证其卓越的鲁棒性。结果显示，我们的方法成功拓展了相应的性能边界。最后，我们在更具挑战性的场景，即从不完整或含噪数据中学习进行实验，发现我们的方法对这类受损数据具有很高的容忍度。

> Evidence-based deep learning represents a burgeoning paradigm for uncertainty estimation, offering reliable predictions with negligible extra computational overheads. Existing methods usually adopt Kullback-Leibler divergence to estimate the uncertainty of network predictions, ignoring domain gaps among various modalities. To tackle this issue, this paper introduces a novel algorithm based on Hölder Divergence (HD) to enhance the reliability of multi-view learning by addressing inherent uncertainty challenges from incomplete or noisy data. Generally, our method extracts the representations of multiple modalities through parallel network branches, and then employs HD to estimate the prediction uncertainties. Through the Dempster-Shafer theory, integration of uncertainty from different modalities, thereby generating a comprehensive result that considers all available representations. Mathematically, HD proves to better measure the ``distance'' between real data distribution and predictive distribution of the model and improve the performances of multi-class recognition tasks.
  Specifically, our method surpass the existing state-of-the-art counterparts on all evaluating benchmarks.
  We further conduct extensive experiments on different backbones to verify our superior robustness. It is demonstrated that our method successfully pushes the corresponding performance boundaries. Finally, we perform experiments on more challenging scenarios, \textit{i.e.}, learning with incomplete or noisy data, revealing that our method exhibits a high tolerance to such corrupted data.

[Arxiv](https://arxiv.org/abs/2411.00826)