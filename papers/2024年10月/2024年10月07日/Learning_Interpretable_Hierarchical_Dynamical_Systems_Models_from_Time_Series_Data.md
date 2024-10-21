# 从时间序列数据中构建可解释的分层动态模型

发布时间：2024年10月07日

`其他` `科学研究` `数据分析`

> Learning Interpretable Hierarchical Dynamical Systems Models from Time Series Data

# 摘要

> 在科学领域，我们常需从时间序列中提取系统动力学的生成模型。尽管单一领域数据的重建方法强大，但如何整合多领域数据以实现泛化仍待解答。尤其当时间序列较短时，群体信息尤为关键。然而，简单平均会抹去动力学特性，如极限环与混沌。因此，我们提出了一种分层框架，既能高效利用多领域信息，又保留单一领域特性。该方法不仅忠实重建了各动力学状态，还发现了相似动力学数据集的低维特征空间，这些特征与控制参数呈线性关系，极具解释性。最后，我们展示了该方法在迁移学习和泛化方面的潜力。

> 
Abstract:In science, we are often interested in obtaining a generative model of the underlying system dynamics from observed time series. While powerful methods for dynamical systems reconstruction (DSR) exist when data come from a single domain, how to best integrate data from multiple dynamical regimes and leverage it for generalization is still an open question. This becomes particularly important when individual time series are short, and group-level information may help to fill in for gaps in single-domain data. At the same time, averaging is not an option in DSR, as it will wipe out crucial dynamical properties (e.g., limit cycles in one domain vs. chaos in another). Hence, a framework is needed that enables to efficiently harvest group-level (multi-domain) information while retaining all single-domain dynamical characteristics. Here we provide such a hierarchical approach and showcase it on popular DSR benchmarks, as well as on neuroscientific and medical time series. In addition to faithful reconstruction of all individual dynamical regimes, our unsupervised methodology discovers common low-dimensional feature spaces in which datasets with similar dynamics cluster. The features spanning these spaces were further dynamically highly interpretable, surprisingly in often linear relation to control parameters that govern the dynamics of the underlying system. Finally, we illustrate transfer learning and generalization to new parameter regimes.
    

[Arxiv](https://arxiv.org/pdf/2410.04814)