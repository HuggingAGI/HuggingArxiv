# 从多模态生物观测中进行因果表示学习

发布时间：2024年11月10日

`其他`

> Causal Representation Learning from Multimodal Biological Observations

# 摘要

> 在生物应用（例如，人类表型测量）中普遍存在，多模态数据集可以为潜在的生物机制提供有价值的见解。然而，当前设计用于分析此类数据集的机器学习模型仍然缺乏可解释性和理论保证，这对于生物应用至关重要。因果表示学习的最新进展在揭示具有正式理论证书的可解释潜在因果变量方面显示出了希望。不幸的是，现有的多模态分布工作要么依赖于限制性的参数假设，要么提供相当粗糙的识别结果，限制了它们在生物研究中的适用性，生物研究更倾向于对机制的详细理解。

在这项工作中，我们旨在为多模态数据开发灵活的识别条件和原则性的方法，以促进对生物数据集的理解。从理论上讲，我们考虑了一个灵活的非参数潜在分布（参见先前工作中的参数假设），允许跨潜在不同模态的因果关系。我们为每个潜在组件建立了可识别性保证，扩展了先前工作中的子空间识别结果。我们的关键理论成分是不同模态之间因果连接的结构稀疏性，正如我们将讨论的那样，这对于大量的生物系统来说是自然的。从经验上讲，我们提出了一个实用的框架来实例化我们的理论见解。我们通过在数值和合成数据集上的广泛实验证明了我们方法的有效性。在真实世界的人类表型数据集上的结果与已建立的医学研究一致，验证了我们的理论和方法框架。

> Prevalent in biological applications (e.g., human phenotype measurements), multimodal datasets can provide valuable insights into the underlying biological mechanisms. However, current machine learning models designed to analyze such datasets still lack interpretability and theoretical guarantees, which are essential to biological applications. Recent advances in causal representation learning have shown promise in uncovering the interpretable latent causal variables with formal theoretical certificates. Unfortunately, existing works for multimodal distributions either rely on restrictive parametric assumptions or provide rather coarse identification results, limiting their applicability to biological research which favors a detailed understanding of the mechanisms.
  In this work, we aim to develop flexible identification conditions for multimodal data and principled methods to facilitate the understanding of biological datasets. Theoretically, we consider a flexible nonparametric latent distribution (c.f., parametric assumptions in prior work) permitting causal relationships across potentially different modalities. We establish identifiability guarantees for each latent component, extending the subspace identification results from prior work. Our key theoretical ingredient is the structural sparsity of the causal connections among distinct modalities, which, as we will discuss, is natural for a large collection of biological systems. Empirically, we propose a practical framework to instantiate our theoretical insights. We demonstrate the effectiveness of our approach through extensive experiments on both numerical and synthetic datasets. Results on a real-world human phenotype dataset are consistent with established medical research, validating our theoretical and methodological framework.

[Arxiv](https://arxiv.org/abs/2411.06518)