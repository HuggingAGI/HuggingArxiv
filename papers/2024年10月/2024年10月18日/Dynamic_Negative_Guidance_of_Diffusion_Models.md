# 扩散模型的动态负面引导

发布时间：2024年10月18日

`LLM应用` `图像生成` `扩散模型`

> Dynamic Negative Guidance of Diffusion Models

# 摘要

> 摘要：负提示（NP）在扩散模型中被广泛使用，特别是在文本到图像的应用中，以防止生成不想要的特征。在本文中，我们表明，传统的 NP 受到恒定引导尺度假设的限制，由于逆向过程的非平稳性和状态依赖性，这可能导致高度次优的结果，甚至完全失败。基于此分析，我们推导出一种称为动态负引导的原则性技术，它依赖于对引导的近乎最优的时间和状态相关调制，而不需要额外的训练。与 NP 不同，负引导需要在去噪过程中估计后验类别概率，这通过在生成过程中跟踪离散马尔可夫链以有限的额外计算开销来实现。我们在 MNIST 和 CIFAR10 上评估了 DNG 类去除的性能，结果表明，与基线方法相比，DNG 带来了更高的安全性、类平衡的保留和图像质量。此外，我们表明，将 DNG 与 Stable Diffusion 一起使用，可以获得比 NP 更准确和侵入性更小的引导。

> 
Abstract:Negative Prompting (NP) is widely utilized in diffusion models, particularly in text-to-image applications, to prevent the generation of undesired features. In this paper, we show that conventional NP is limited by the assumption of a constant guidance scale, which may lead to highly suboptimal results, or even complete failure, due to the non-stationarity and state-dependence of the reverse process. Based on this analysis, we derive a principled technique called Dynamic Negative Guidance, which relies on a near-optimal time and state dependent modulation of the guidance without requiring additional training. Unlike NP, negative guidance requires estimating the posterior class probability during the denoising process, which is achieved with limited additional computational overhead by tracking the discrete Markov Chain during the generative process. We evaluate the performance of DNG class-removal on MNIST and CIFAR10, where we show that DNG leads to higher safety, preservation of class balance and image quality when compared with baseline methods. Furthermore, we show that it is possible to use DNG with Stable Diffusion to obtain more accurate and less invasive guidance than NP.
    

[Arxiv](https://arxiv.org/pdf/2410.14398)