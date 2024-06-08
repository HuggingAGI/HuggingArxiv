# SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用

发布时间：2024年06月04日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的预训练方法，特别是通过引入一种名为SLTrain的新方法，该方法通过将权重分解为低秩和稀疏矩阵的和来优化预训练过程。这种方法旨在提高预训练效果的同时减少计算资源和内存的需求。因此，这篇论文的内容更偏向于LLM的理论研究，即如何优化和改进LLM的预训练技术，而不是具体的应用案例或Agent的设计与实现。` `机器学习`

> SLTrain: a sparse plus low-rank approach for parameter and memory efficient pretraining

# 摘要

> 大型语言模型（LLMs）在多任务中表现出色，但训练它们需要巨大的计算资源和内存。近期研究通过低秩适应或分解，探索了权重上的低秩结构，以实现参数和内存的高效微调。尽管微调效果显著，低秩结构在预训练中并不理想，因其限制了参数的维度。本研究提出了一种名为SLTrain的新方法，通过将权重分解为低秩和稀疏矩阵的和来进行预训练。低秩部分通过矩阵分解学习，而稀疏部分则采用随机选择固定支持的简单策略，仅学习非零元素。这种简单的策略与低秩学习结合，极大地提升了预训练效果。实验表明，SLTrain在几乎不增加额外参数和内存成本的情况下，性能大幅提升，与全秩训练相当。特别地，结合量化和逐层更新，SLTrain在预训练LLaMA 7B模型时，内存需求可降低高达73%。

> Large language models (LLMs) have shown impressive capabilities across various tasks. However, training LLMs from scratch requires significant computational power and extensive memory capacity. Recent studies have explored low-rank structures on weights for efficient fine-tuning in terms of parameters and memory, either through low-rank adaptation or factorization. While effective for fine-tuning, low-rank structures are generally less suitable for pretraining because they restrict parameters to a low-dimensional subspace. In this work, we propose to parameterize the weights as a sum of low-rank and sparse matrices for pretraining, which we call SLTrain. The low-rank component is learned via matrix factorization, while for the sparse component, we employ a simple strategy of uniformly selecting the sparsity support at random and learning only the non-zero entries with the fixed support. While being simple, the random fixed-support sparse learning strategy significantly enhances pretraining when combined with low-rank learning. Our results show that SLTrain adds minimal extra parameters and memory costs compared to pretraining with low-rank parameterization, yet achieves substantially better performance, which is comparable to full-rank training. Remarkably, when combined with quantization and per-layer updates, SLTrain can reduce memory requirements by up to 73% when pretraining the LLaMA 7B model.

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x1.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x2.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_o.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x3.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x4.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x5.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x6.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_o.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_k.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_q.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_v.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/mlp_down.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/mlp_up.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x7.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_o_0.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_k_0.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_q_0.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_v_0.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/mlp_down_0.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/mlp_up_0.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x8.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_o_3.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_k_3.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_q_3.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_v_3.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/mlp_down_3.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/mlp_up_3.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x9.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_o_130m.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_k_130m.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_q_130m.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/attn_v_130m.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/mlp_down_130m.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/mlp_up_130m.jpg)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x10.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x11.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x12.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x13.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x14.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x15.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x16.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x17.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x18.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x19.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x20.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x21.png)

![SLTrain：一种结合稀疏与低秩的预训练方法，旨在实现参数与内存的高效利用](../../../paper_images/2406.02214/x22.png)

[Arxiv](https://arxiv.org/abs/2406.02214)