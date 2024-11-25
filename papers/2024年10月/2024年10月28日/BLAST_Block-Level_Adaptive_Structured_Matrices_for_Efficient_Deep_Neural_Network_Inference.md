# BLAST：用于深度神经网络高效推理的块级自适应结构化矩阵

发布时间：2024年10月28日

`LLM应用`

> BLAST: Block-Level Adaptive Structured Matrices for Efficient Deep Neural Network Inference

# 摘要

> 大规模基础模型在语言和视觉任务中展现出非凡的性能。然而，这些大型网络中众多的密集矩阵-向量运算在推理时带来了巨大的计算难题。为应对这些难题，我们引入了块级自适应结构化（BLAST）矩阵，旨在学习并利用深度学习模型线性层权重矩阵中常见的高效结构。和现有的结构化矩阵相比，BLAST 矩阵具有极大的灵活性，它能够表示从数据中学习到的或从已有权重矩阵计算出的各类结构。我们证明了使用 BLAST 矩阵压缩语言和视觉任务的高效性，具体表现为：（i）对于像 ViT 和 GPT-2 这类中型模型，用 BLAST 权重训练能提升性能，同时分别降低 70％和 40％的复杂度；（ii）对于像 Llama-7B 和 DiT-XL 这样的大型基础模型，BLAST 矩阵实现了 2 倍压缩，且在所有测试的结构化矩阵中性能下降最少。我们的代码可在 url{https://github.com/changwoolee/BLAST}获取。

> Large-scale foundation models have demonstrated exceptional performance in language and vision tasks. However, the numerous dense matrix-vector operations involved in these large networks pose significant computational challenges during inference. To address these challenges, we introduce the Block-Level Adaptive STructured (BLAST) matrix, designed to learn and leverage efficient structures prevalent in the weight matrices of linear layers within deep learning models. Compared to existing structured matrices, the BLAST matrix offers substantial flexibility, as it can represent various types of structures that are either learned from data or computed from pre-existing weight matrices. We demonstrate the efficiency of using the BLAST matrix for compressing both language and vision tasks, showing that (i) for medium-sized models such as ViT and GPT-2, training with BLAST weights boosts performance while reducing complexity by 70\% and 40\%, respectively; and (ii) for large foundation models such as Llama-7B and DiT-XL, the BLAST matrix achieves a 2x compression while exhibiting the lowest performance degradation among all tested structured matrices. Our code is available at url{https://github.com/changwoolee/BLAST}.

[Arxiv](https://arxiv.org/abs/2410.21262)