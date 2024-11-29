# 基于阈值相关高斯过程的空间变化相关性贝叶斯推断

发布时间：2024年11月26日

`其他` `神经影像学` `医学成像`

> Bayesian Inference of Spatially Varying Correlations via the Thresholded Correlation Gaussian Process

# 摘要

> 在多模态神经影像学分析里，核心问题在于搞清楚两种成像模式的关联，找出这种关联具有统计学显著意义的大脑区域。本文中，我们提出了一种贝叶斯非参数空间变化相关模型来推断此类区域。我们以阈值相关高斯过程（TCGP）为基础构建模型。该模型能保证空间变化相关性的分段平滑、稀疏和跳跃不连续，即便受试者数量有限或者信噪比低也能适用良好。我们对模型的可识别性进行了研究，确立了大支持性质，推导出后验一致性和选择一致性。此外，我们还开发了一种高效的吉布斯采样器及其变体来计算后验分布。我们通过模拟以及对人类连接组计划的功能磁共振成像数据的分析来展示该方法。

> A central question in multimodal neuroimaging analysis is to understand the association between two imaging modalities and to identify brain regions where such an association is statistically significant. In this article, we propose a Bayesian nonparametric spatially varying correlation model to make inference of such regions. We build our model based on the thresholded correlation Gaussian process (TCGP). It ensures piecewise smoothness, sparsity, and jump discontinuity of spatially varying correlations, and is well applicable even when the number of subjects is limited or the signal-to-noise ratio is low. We study the identifiability of our model, establish the large support property, and derive the posterior consistency and selection consistency. We also develop a highly efficient Gibbs sampler and its variant to compute the posterior distribution. We illustrate the method with both simulations and an analysis of functional magnetic resonance imaging data from the Human Connectome Project.

[Arxiv](https://arxiv.org/abs/2411.18012)