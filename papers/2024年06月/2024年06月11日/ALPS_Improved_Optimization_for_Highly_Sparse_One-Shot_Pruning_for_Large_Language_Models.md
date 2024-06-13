# ALPS：优化大型语言模型的高稀疏一次性修剪技术

发布时间：2024年06月11日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的优化问题，特别是通过剪枝技术来减少计算资源和存储需求。论文提出的ALPS框架采用算子分裂技术和预处理共轭梯度法进行后处理，以优化方式解决剪枝难题。这种方法不仅加速并确保理论上的收敛，还通过向量化和GPU并行性提升效率。因此，这篇论文更偏向于LLM的理论研究，特别是在模型优化和性能提升方面的理论探讨。` `模型优化`

> ALPS: Improved Optimization for Highly Sparse One-Shot Pruning for Large Language Models

# 摘要

> 大型语言模型（LLMs）在众多自然语言处理任务中展现出卓越性能，但背后是庞大的计算资源和存储需求。一次性剪枝技术通过剔除冗余权重，无需重新训练，有效减轻了这些负担。然而，LLMs的庞大规模常使现有剪枝方法不得不依赖启发式而非基于优化的策略，可能导致压缩效果不尽如人意。本文推出的ALPS框架，采用算子分裂技术和预处理共轭梯度法进行后处理，以优化方式解决剪枝难题。ALPS不仅加速并确保理论上的收敛，还通过向量化和GPU并行性提升效率。在高度稀疏模型中，ALPS在剪枝目标和降低困惑度方面显著超越现有技术。对于70%稀疏度的OPT-30B模型，ALPS在WikiText数据集上的测试困惑度降低了13%，零-shot性能提升了19%，远超现有方法。

> The impressive performance of Large Language Models (LLMs) across various natural language processing tasks comes at the cost of vast computational resources and storage requirements. One-shot pruning techniques offer a way to alleviate these burdens by removing redundant weights without the need for retraining. Yet, the massive scale of LLMs often forces current pruning approaches to rely on heuristics instead of optimization-based techniques, potentially resulting in suboptimal compression. In this paper, we introduce ALPS, an optimization-based framework that tackles the pruning problem using the operator splitting technique and a preconditioned conjugate gradient-based post-processing step. Our approach incorporates novel techniques to accelerate and theoretically guarantee convergence while leveraging vectorization and GPU parallelism for efficiency. ALPS substantially outperforms state-of-the-art methods in terms of the pruning objective and perplexity reduction, particularly for highly sparse models. On the OPT-30B model with 70% sparsity, ALPS achieves a 13% reduction in test perplexity on the WikiText dataset and a 19% improvement in zero-shot benchmark performance compared to existing methods.

[Arxiv](https://arxiv.org/abs/2406.07831)