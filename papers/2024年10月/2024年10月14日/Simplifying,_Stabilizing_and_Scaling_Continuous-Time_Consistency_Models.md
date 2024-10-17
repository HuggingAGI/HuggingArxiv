# 精简、稳固并扩展连续时间一致性模型

发布时间：2024年10月14日

`其他` `图像生成` `人工智能`

> Simplifying, Stabilizing and Scaling Continuous-Time Consistency Models

# 摘要

> 一致性模型 (CMs) 是一类专为快速采样优化的扩散生成模型。现有的大多数 CMs 采用离散时间步长训练，这不仅增加了超参数，还易导致离散误差。尽管连续时间公式能缓解这些问题，但其训练稳定性仍受限。为此，我们提出一个简化框架，统一了先前扩散模型和 CMs 的参数化，并找出了不稳定性的根源。基于此，我们改进了扩散过程参数化、网络架构和训练目标。这些改进使我们能在 ImageNet 512x512 上训练出 1.5B 参数的连续时间 CMs。我们的训练算法仅需两个采样步骤，在 CIFAR-10、ImageNet 64x64 和 ImageNet 512x512 上的 FID 分数分别达到 2.06、1.48 和 1.88，将 FID 分数与最佳扩散模型的差距缩小至 10% 以内。

> 
Abstract:Consistency models (CMs) are a powerful class of diffusion-based generative models optimized for fast sampling. Most existing CMs are trained using discretized timesteps, which introduce additional hyperparameters and are prone to discretization errors. While continuous-time formulations can mitigate these issues, their success has been limited by training instability. To address this, we propose a simplified theoretical framework that unifies previous parameterizations of diffusion models and CMs, identifying the root causes of instability. Based on this analysis, we introduce key improvements in diffusion process parameterization, network architecture, and training objectives. These changes enable us to train continuous-time CMs at an unprecedented scale, reaching 1.5B parameters on ImageNet 512x512. Our proposed training algorithm, using only two sampling steps, achieves FID scores of 2.06 on CIFAR-10, 1.48 on ImageNet 64x64, and 1.88 on ImageNet 512x512, narrowing the gap in FID scores with the best existing diffusion models to within 10%.
    

[Arxiv](https://arxiv.org/pdf/2410.11081)