# 优化学习率在令牌视野中的扩展

发布时间：2024年09月29日

`LLM理论` `机器学习` `人工智能`

> Scaling Optimal LR Across Token Horizon

# 摘要

> 最先进的 LLM 通过扩展模型、数据集和集群大小来实现卓越性能。然而，对于最大规模的运行，广泛调整超参数在经济上并不可行。因此，我们需要从较小实验中推断或转移近似最优的超参数。尽管 Yang 等人研究了跨模型大小的超参数转移，但跨数据集大小或令牌视野的转移尚未被探讨。为此，我们进行了一项大规模实证研究，揭示了最优学习率 (LR) 如何随令牌视野变化。我们发现，更长的训练需要更小的 LR，并且最优 LR 遵循缩放定律，使得从较短视野准确估计较长视野的 LR 成为可能。此外，我们提供了一个无需额外开销的经验法则，用于在不同令牌视野间转移 LR。最后，我们指出 LLama-1 可能使用了过高的 LR，并估计了其对性能的影响。因此，我们认为跨数据大小的超参数转移是 LLM 训练中一个重要且被忽视的环节。

> State-of-the-art LLMs are powered by scaling -- scaling model size, dataset size and cluster size. It is economically infeasible to extensively tune hyperparameter for the largest runs. Instead, approximately optimal hyperparameters must be inferred or \textit{transferred} from smaller experiments. Hyperparameter transfer across model sizes has been studied in Yang et al. However, hyperparameter transfer across dataset size -- or token horizon -- has not been studied yet. To remedy this we conduct a large scale empirical study on how optimal learning rate (LR) depends on token horizon in LLM training. We first demonstrate that the optimal LR changes significantly with token horizon -- longer training necessitates smaller LR. Secondly we demonstrate the the optimal LR follows a scaling law, and that the optimal LR for longer horizons can be accurately estimated from shorter horizons via our scaling laws. We also provide a rule-of-thumb for transferring LR across token horizons with zero overhead over current practices. Lastly we provide evidence that LLama-1 used too high LR, and estimate the performance hit from this. We thus argue that hyperparameter transfer across data size is an important and overlooked component of LLM training.

[Arxiv](https://arxiv.org/abs/2409.19913)