# 大型语言模型的子空间优化，确保收敛性

发布时间：2024年10月15日

`LLM理论` `机器学习` `优化算法`

> Subspace Optimization for Large Language Models with Convergence Guarantees

# 摘要

> 子空间优化算法如 GaLore（Zhao et al., 2024）因其内存效率在 LLM 的预训练和微调中备受青睐。然而，其随机环境下的收敛性仍不明朗。本文意外发现 GaLore 并非总能收敛至最优解，并通过实例佐证。我们进一步探讨了 GaLore 的收敛条件，发现其在确定性环境或大批次训练时可收敛。更关键的是，我们提出了 GoLore（梯度随机低秩投影），这一 GaLore 变体在随机环境下也能确保收敛，即便使用常规批次。此外，我们的收敛分析可推广至其他稀疏子空间优化算法。最后，通过数值实验验证了理论成果，并探索了所提机制的实际效果。代码已公开于 https://github.com/pkumelon/Golore。

> Subspace optimization algorithms, with GaLore (Zhao et al., 2024) as a representative method, have gained popularity for pre-training or fine-tuning large language models (LLMs) due to their memory efficiency. However, their convergence guarantees remain unclear, particularly in stochastic settings. In this paper, we unexpectedly discover that GaLore does not always converge to the optimal solution and substantiate this finding with an explicit counterexample. We then investigate the conditions under which GaLore can achieve convergence, demonstrating that it does so either in deterministic scenarios or when using a sufficiently large mini-batch size. More significantly, we introduce GoLore (Gradient random Low-rank projection), a novel variant of GaLore that provably converges in stochastic settings, even with standard batch sizes. Our convergence analysis can be readily extended to other sparse subspace optimization algorithms. Finally, we conduct numerical experiments to validate our theoretical results and empirically explore the proposed mechanisms. Codes are available at https://github.com/pkumelon/Golore.

[Arxiv](https://arxiv.org/abs/2410.11289)