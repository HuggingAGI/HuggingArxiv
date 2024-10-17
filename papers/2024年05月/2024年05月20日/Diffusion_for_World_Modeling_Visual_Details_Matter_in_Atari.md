# 在 Atari 游戏中，视觉细节对于世界建模的扩散过程至关重要。

发布时间：2024年05月20日

`Agent` `人工智能`

> Diffusion for World Modeling: Visual Details Matter in Atari

# 摘要

> 摘要：世界模型为强化学习代理的训练提供了一种安全且高效的方法。然而，现有的世界模型多依赖于离散潜在变量的序列，这可能忽略了重要的视觉细节。与此同时，扩散模型在图像生成领域崭露头角，挑战了传统的离散建模方法。基于此，我们推出了 DIAMOND，一种在扩散世界模型中训练的强化学习代理。我们探讨了使扩散模型适用于世界建模的关键设计，并展示了视觉细节的提升如何增强代理性能。DIAMOND 在 Atari 100k 基准测试中取得了 1.46 的平均人类归一化分数，创下了新纪录。为推动相关研究，我们公开了代码和模型。

> 
Abstract:World models constitute a promising approach for training reinforcement learning agents in a safe and sample-efficient manner. Recent world models predominantly operate on sequences of discrete latent variables to model environment dynamics. However, this compression into a compact discrete representation may ignore visual details that are important for reinforcement learning. Concurrently, diffusion models have become a dominant approach for image generation, challenging well-established methods modeling discrete latents. Motivated by this paradigm shift, we introduce DIAMOND (DIffusion As a Model Of eNvironment Dreams), a reinforcement learning agent trained in a diffusion world model. We analyze the key design choices that are required to make diffusion suitable for world modeling, and demonstrate how improved visual details can lead to improved agent performance. DIAMOND achieves a mean human normalized score of 1.46 on the competitive Atari 100k benchmark; a new best for agents trained entirely within a world model. To foster future research on diffusion for world modeling, we release our code, agents and playable world models at this https URL.
    

[Arxiv](https://arxiv.org/pdf/2405.12399)