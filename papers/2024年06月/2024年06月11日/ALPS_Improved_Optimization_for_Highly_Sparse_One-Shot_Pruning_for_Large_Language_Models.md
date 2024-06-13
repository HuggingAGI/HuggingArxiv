# ALPS：提升大型语言模型高稀疏一次性剪枝的优化策略

发布时间：2024年06月11日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的优化问题，特别是通过剪枝技术来减少模型的计算资源和存储需求。论文提出的ALPS框架是一种优化方法，用于解决剪枝过程中的问题，并通过算子分裂技术和预条件共轭梯度后处理来提高剪枝效率和效果。这种方法的理论基础和实证结果表明，它在提高模型性能和减少资源消耗方面优于现有技术。因此，这篇论文更偏向于LLM的理论研究，特别是关于模型优化和效率提升的方面。` `模型优化`

> ALPS: Improved Optimization for Highly Sparse One-Shot Pruning for Large Language Models

# 摘要

> 大型语言模型（LLMs）在众多自然语言处理任务中展现了卓越性能，但背后是庞大的计算资源和存储需求。一次剪枝技术通过剔除冗余权重，无需重新训练，有效减轻了这些负担。然而，LLMs的庞大规模使得当前剪枝方法多依赖启发式而非优化技术，可能导致压缩效果不尽人意。本文推出的ALPS框架，采用算子分裂技术和预条件共轭梯度后处理，以优化方式解决剪枝难题。ALPS不仅加速并确保理论上的收敛，还通过向量化和GPU并行提升了效率。在剪枝目标和降低困惑度方面，ALPS显著超越了现有技术，尤其在高度稀疏模型上表现突出。在稀疏度为70%的OPT-30B模型上，ALPS在WikiText数据集上的测试困惑度降低了13%，零-shot基准性能提升了19%，超越了现有方法。

> The impressive performance of Large Language Models (LLMs) across various natural language processing tasks comes at the cost of vast computational resources and storage requirements. One-shot pruning techniques offer a way to alleviate these burdens by removing redundant weights without the need for retraining. Yet, the massive scale of LLMs often forces current pruning approaches to rely on heuristics instead of optimization-based techniques, potentially resulting in suboptimal compression. In this paper, we introduce ALPS, an optimization-based framework that tackles the pruning problem using the operator splitting technique and a preconditioned conjugate gradient-based post-processing step. Our approach incorporates novel techniques to accelerate and theoretically guarantee convergence while leveraging vectorization and GPU parallelism for efficiency. ALPS substantially outperforms state-of-the-art methods in terms of the pruning objective and perplexity reduction, particularly for highly sparse models. On the OPT-30B model with 70% sparsity, ALPS achieves a 13% reduction in test perplexity on the WikiText dataset and a 19% improvement in zero-shot benchmark performance compared to existing methods.

[Arxiv](https://arxiv.org/abs/2406.07831)