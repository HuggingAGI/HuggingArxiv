# 通过暖启动 EM 学习大型 softmax 混合模型

发布时间：2024年09月15日

`LLM理论` `人工智能` `机器学习`

> Learning large softmax mixtures with warm start EM

# 摘要

> 混合多项式逻辑回归模型，又称 softmax 混合模型，近年来在 AI 领域备受瞩目。它通过神经网络的最后一层，将大量向量映射为概率分布。尽管应用广泛且效果显著，但如何高效且准确地估计其参数仍是一个挑战。本文针对大型语言模型等现代应用场景，提出了一种结合矩方法和期望最大化算法的参数估计方案。我们不仅为 softmax 混合模型量身定制了新的矩估计方法，还首次提供了其理论分析。尽管矩方法在数值表现上可能不尽如人意，但其理论上的接近性使其成为预热启动的理想选择。最终，我们推荐使用矩方法预热启动的 EM 算法，以实现更精确的参数估计。

> Mixed multinomial logits are discrete mixtures introduced several decades ago to model the probability of choosing an attribute from $p$ possible candidates, in heterogeneous populations. The model has recently attracted attention in the AI literature, under the name softmax mixtures, where it is routinely used in the final layer of a neural network to map a large number $p$ of vectors in $\mathbb{R}^L$ to a probability vector. Despite its wide applicability and empirical success, statistically optimal estimators of the mixture parameters, obtained via algorithms whose running time scales polynomially in $L$, are not known. This paper provides a solution to this problem for contemporary applications, such as large language models, in which the mixture has a large number $p$ of support points, and the size $N$ of the sample observed from the mixture is also large. Our proposed estimator combines two classical estimators, obtained respectively via a method of moments (MoM) and the expectation-minimization (EM) algorithm. Although both estimator types have been studied, from a theoretical perspective, for Gaussian mixtures, no similar results exist for softmax mixtures for either procedure. We develop a new MoM parameter estimator based on latent moment estimation that is tailored to our model, and provide the first theoretical analysis for a MoM-based procedure in softmax mixtures. Although consistent, MoM for softmax mixtures can exhibit poor numerical performance, as observed other mixture models. Nevertheless, as MoM is provably in a neighborhood of the target, it can be used as warm start for any iterative algorithm. We study in detail the EM algorithm, and provide its first theoretical analysis for softmax mixtures. Our final proposal for parameter estimation is the EM algorithm with a MoM warm start.

[Arxiv](https://arxiv.org/abs/2409.09903)