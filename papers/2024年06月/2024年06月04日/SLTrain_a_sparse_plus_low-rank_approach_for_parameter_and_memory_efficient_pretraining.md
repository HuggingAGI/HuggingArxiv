# SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化

发布时间：2024年06月04日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的预训练优化方法，特别是通过引入低秩和稀疏矩阵的权重参数化来提高预训练效率。这种方法不仅关注了微调阶段的优化，还特别强调了预训练阶段的改进，这与LLM的理论研究紧密相关。因此，将其归类为LLM理论是合适的。` `机器学习`

> SLTrain: a sparse plus low-rank approach for parameter and memory efficient pretraining

# 摘要

> 大型语言模型（LLMs）在多任务中表现出色，但其从头训练对计算和内存要求极高。近期研究通过低秩适应或分解，探索了权重上的低秩结构，以优化微调效率。尽管微调效果显著，低秩结构在预训练中却不太适用，因其限制了参数的维度。为此，我们提出了SLTrain方法，将权重参数化为低秩与稀疏矩阵的和。低秩部分通过矩阵分解学习，稀疏部分则采用随机选择固定支持的简单策略，仅学习非零项。这种简单的策略与低秩学习结合，大幅提升了预训练效果。实验显示，SLTrain在几乎不增加额外参数和内存成本的情况下，性能显著提升，媲美全秩训练。更令人瞩目的是，结合量化和逐层更新，SLTrain在预训练LLaMA 7B模型时，内存需求可降低高达73%。

> Large language models (LLMs) have shown impressive capabilities across various tasks. However, training LLMs from scratch requires significant computational power and extensive memory capacity. Recent studies have explored low-rank structures on weights for efficient fine-tuning in terms of parameters and memory, either through low-rank adaptation or factorization. While effective for fine-tuning, low-rank structures are generally less suitable for pretraining because they restrict parameters to a low-dimensional subspace. In this work, we propose to parameterize the weights as a sum of low-rank and sparse matrices for pretraining, which we call SLTrain. The low-rank component is learned via matrix factorization, while for the sparse component, we employ a simple strategy of uniformly selecting the sparsity support at random and learning only the non-zero entries with the fixed support. While being simple, the random fixed-support sparse learning strategy significantly enhances pretraining when combined with low-rank learning. Our results show that SLTrain adds minimal extra parameters and memory costs compared to pretraining with low-rank parameterization, yet achieves substantially better performance, which is comparable to full-rank training. Remarkably, when combined with quantization and per-layer updates, SLTrain can reduce memory requirements by up to 73% when pretraining the LLaMA 7B model.

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x1.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x2.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_o.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x3.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x4.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x5.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x6.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_o.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_k.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_q.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_v.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/mlp_down.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/mlp_up.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x7.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_o_0.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_k_0.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_q_0.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_v_0.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/mlp_down_0.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/mlp_up_0.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x8.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_o_3.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_k_3.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_q_3.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_v_3.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/mlp_down_3.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/mlp_up_3.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x9.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_o_130m.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_k_130m.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_q_130m.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/attn_v_130m.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/mlp_down_130m.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/mlp_up_130m.jpg)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x10.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x11.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x12.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x13.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x14.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x15.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x16.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x17.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x18.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x19.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x20.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x21.png)

![SLTrain：采用稀疏加低秩策略，实现高效预训练，兼顾参数与内存优化](../../../paper_images/2406.02214/x22.png)

[Arxiv](https://arxiv.org/abs/2406.02214)