# SEE-DPO：自我熵增强直接偏好优化

发布时间：2024年11月05日

`LLM应用` `图像生成`

> SEE-DPO: Self Entropy Enhanced Direct Preference Optimization

# 摘要

> 直接偏好优化（DPO）已成功用于根据人类偏好调整大型语言模型（LLM），最近它也被应用于提高文本到图像扩散模型的质量。然而，基于 DPO 的方法，如 SPO、Diffusion-DPO 和 D3PO 极易受到过拟合和奖励黑客攻击的影响，特别是当生成模型在长期训练中被优化以适应分布外数据时。为了克服这些挑战并稳定扩散模型的训练，我们在基于人类反馈的强化学习中引入了一种自熵正则化机制。这种增强通过鼓励更广泛的探索和更大的鲁棒性来改善 DPO 训练。我们的正则化技术有效地减轻了奖励黑客攻击，导致在潜在空间中提高了稳定性和增强了图像质量。大量实验表明，将人类反馈与自熵正则化相结合可以显著提高图像的多样性和特异性，在关键图像生成指标上取得最先进的结果。

> Direct Preference Optimization (DPO) has been successfully used to align large language models (LLMs) according to human preferences, and more recently it has also been applied to improving the quality of text-to-image diffusion models. However, DPO-based methods such as SPO, Diffusion-DPO, and D3PO are highly susceptible to overfitting and reward hacking, especially when the generative model is optimized to fit out-of-distribution during prolonged training. To overcome these challenges and stabilize the training of diffusion models, we introduce a self-entropy regularization mechanism in reinforcement learning from human feedback. This enhancement improves DPO training by encouraging broader exploration and greater robustness. Our regularization technique effectively mitigates reward hacking, leading to improved stability and enhanced image quality across the latent space. Extensive experiments demonstrate that integrating human feedback with self-entropy regularization can significantly boost image diversity and specificity, achieving state-of-the-art results on key image generation metrics.

[Arxiv](https://arxiv.org/abs/2411.04712)