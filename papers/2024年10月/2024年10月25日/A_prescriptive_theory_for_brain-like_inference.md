# 一种类似大脑推理的规范性理论

发布时间：2024年10月25日

`LLM理论` `神经科学` `机器学习`

> A prescriptive theory for brain-like inference

# 摘要

> 摘要：证据下界（ELBO）是训练深度生成模型（如变分自编码器（VAEs））广泛使用的目标。在神经科学文献中，相同的目标被称为变分自由能，这暗示了大脑功能和机器学习的潜在统一框架。尽管它在解释生成模型（包括扩散模型）方面很有用，但ELBO最大化通常被认为过于宽泛，无法为神经科学或机器学习中的特定架构提供规范性指导。在这项工作中，我们表明，在一般序列数据的泊松假设下最大化ELBO会导致一个脉冲神经网络，通过其膜电位动力学进行贝叶斯后验推断。所得模型，即迭代泊松VAE（iP-VAE），与之前基于高斯假设的受大脑启发的预测编码模型相比，与生物神经元的联系更紧密。与摊销和迭代的VAE相比，iP-VAE学习到更稀疏的表示，并对分布外样本表现出更优越的泛化能力。这些发现表明，结合泊松假设优化ELBO为NeuroAI中规范性理论的发展提供了坚实的基础。

> 
Abstract:The Evidence Lower Bound (ELBO) is a widely used objective for training deep generative models, such as Variational Autoencoders (VAEs). In the neuroscience literature, an identical objective is known as the variational free energy, hinting at a potential unified framework for brain function and machine learning. Despite its utility in interpreting generative models, including diffusion models, ELBO maximization is often seen as too broad to offer prescriptive guidance for specific architectures in neuroscience or machine learning. In this work, we show that maximizing ELBO under Poisson assumptions for general sequence data leads to a spiking neural network that performs Bayesian posterior inference through its membrane potential dynamics. The resulting model, the iterative Poisson VAE (iP-VAE), has a closer connection to biological neurons than previous brain-inspired predictive coding models based on Gaussian assumptions. Compared to amortized and iterative VAEs, iP-VAElearns sparser representations and exhibits superior generalization to out-of-distribution samples. These findings suggest that optimizing ELBO, combined with Poisson assumptions, provides a solid foundation for developing prescriptive theories in NeuroAI.
    

[Arxiv](https://arxiv.org/pdf/2410.19315)