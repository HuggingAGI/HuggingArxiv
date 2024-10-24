# 磁性偏好优化：实现语言模型对齐的最后迭代收敛

发布时间：2024年10月22日

`LLM应用` `语言模型`

> Magnetic Preference Optimization: Achieving Last-iterate Convergence for Language Models Alignment

# 摘要

> 自我博弈方法在各个领域提高模型能力方面已取得显著成功。在基于人类反馈的强化学习（RLHF）的背景下，自我博弈不仅提高了大型语言模型（LLM）的性能，而且通过找到基于偏好的两人恒定和博弈的纳什均衡（NE），克服了传统布拉德利 - 特里（BT）模型假设的局限性。然而，现有的方法要么仅保证平均迭代收敛，导致高存储和推理成本，要么收敛到正则化博弈的NE，无法准确反映真实的人类偏好。在本文中，我们引入了磁性偏好优化（MPO），这是一种能够实现对原始博弈的NE的最后迭代收敛的新方法，有效地克服了现有方法的局限性。基于磁性镜像下降（MMD），MPO 实现了线性收敛速度，使其特别适用于微调 LLM。为了确保我们的算法在理论上合理且在实践中可行，我们提出了一种简单而有效的实现，将理论见解适应于 RLHF 设置。实证结果表明，MPO 可以显著提高 LLM 的性能，突出了自我博弈方法在对齐方面的潜力。

> Self-play methods have demonstrated remarkable success in enhancing model capabilities across various domains. In the context of Reinforcement Learning from Human Feedback (RLHF), self-play not only boosts Large Language Model (LLM) performance but also overcomes the limitations of traditional Bradley-Terry (BT) model assumptions by finding the Nash equilibrium (NE) of a preference-based, two-player constant-sum game. However, existing methods either guarantee only average-iterate convergence, incurring high storage and inference costs, or converge to the NE of a regularized game, failing to accurately reflect true human preferences. In this paper, we introduce Magnetic Preference Optimization (MPO), a novel approach capable of achieving last-iterate convergence to the NE of the original game, effectively overcoming the limitations of existing methods. Building upon Magnetic Mirror Descent (MMD), MPO attains a linear convergence rate, making it particularly suitable for fine-tuning LLMs. To ensure our algorithm is both theoretically sound and practically viable, we present a simple yet effective implementation that adapts the theoretical insights to the RLHF setting. Empirical results demonstrate that MPO can significantly enhance the performance of LLMs, highlighting the potential of self-play methods in alignment.

[Arxiv](https://arxiv.org/abs/2410.16714)