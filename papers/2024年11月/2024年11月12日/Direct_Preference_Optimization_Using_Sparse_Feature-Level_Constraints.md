# 使用稀疏特征级约束的直接偏好优化

发布时间：2024年11月12日

`LLM应用` `语言模型` `人工智能`

> Direct Preference Optimization Using Sparse Feature-Level Constraints

# 摘要

> 大型语言模型（LLM）与人类偏好的对齐仍然是一个关键挑战。虽然像基于人类反馈的强化学习（RLHF）和直接偏好优化（DPO）这样的训练后技术已经取得了显著的成功，但它们经常引入计算效率低下和训练不稳定的问题。在本文中，我们提出了特征级约束偏好优化（FPO），这是一种旨在简化对齐过程同时确保稳定性的新方法。FPO 利用预先训练的稀疏自编码器（SAE）并引入特征级约束，允许进行高效、稀疏强制的对齐。我们的方法通过使用在训练良好的稀疏自编码器中激活的稀疏特征来提高效率，并通过使用特征级离线参考来提高顺序 KL 散度的质量。在基准数据集上的实验结果表明，与最先进的基线相比，FPO 在胜率方面实现了 5.08％的绝对提高，计算成本要低得多，使其成为高效和可控 LLM 对齐的有前途的解决方案。

> The alignment of large language models (LLMs) with human preferences remains a key challenge. While post-training techniques like Reinforcement Learning from Human Feedback (RLHF) and Direct Preference Optimization (DPO) have achieved notable success, they often introduce computational inefficiencies and training instability. In this paper, we propose Feature-level constrained Preference Optimization (FPO), a novel method designed to simplify the alignment process while ensuring stability. FPO leverages pre-trained Sparse Autoencoders (SAEs) and introduces feature-level constraints, allowing for efficient, sparsity-enforced alignment. Our approach enjoys efficiency by using sparse features activated in a well-trained sparse autoencoder and the quality of sequential KL divergence by using the feature-level offline reference. Experimental results on benchmark datasets demonstrate that FPO achieves a 5.08% absolute improvement in win rate with much lower computational cost compared to state-of-the-art baselines, making it a promising solution for efficient and controllable LLM alignments.

[Arxiv](https://arxiv.org/abs/2411.07618)