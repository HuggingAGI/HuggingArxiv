# ARTEMIS：一款结合模拟与随机技术的DRAM加速器，专为Transformer神经网络设计。

发布时间：2024年07月17日

`LLM理论` `半导体` `计算机硬件`

> ARTEMIS: A Mixed Analog-Stochastic In-DRAM Accelerator for Transformer Neural Networks

# 摘要

> Transformer 模型通过其注意力机制，在 NLP 和计算机视觉领域展现出超越传统 RNN 和 CNN 的显著性能优势。然而，其庞大的计算量和内存需求导致执行时间较长。内存内处理 (PIM) 和近内存计算 (NMC) 因其高并行性和带宽成为加速 Transformer 的潜在方案，但设计支持复杂操作和数据移动的 PIM/NMC 架构仍具挑战。为此，我们设计了 ARTEMIS，一种结合模拟与随机计算的 DRAM 加速器，通过最小化对传统 DRAM 的改动，有效降低了 Transformer 模型的执行成本。实验数据显示，ARTEMIS 在速度、能耗和能效方面均优于现有 GPU、TPU、CPU 及 PIM 加速器，分别至少提升 3.0 倍、降低 1.8 倍和提高 1.9 倍。

> Transformers have emerged as a powerful tool for natural language processing (NLP) and computer vision. Through the attention mechanism, these models have exhibited remarkable performance gains when compared to conventional approaches like recurrent neural networks (RNNs) and convolutional neural networks (CNNs). Nevertheless, transformers typically demand substantial execution time due to their extensive computations and large memory footprint. Processing in-memory (PIM) and near-memory computing (NMC) are promising solutions to accelerating transformers as they offer high compute parallelism and memory bandwidth. However, designing PIM/NMC architectures to support the complex operations and massive amounts of data that need to be moved between layers in transformer neural networks remains a challenge. We propose ARTEMIS, a mixed analog-stochastic in-DRAM accelerator for transformer models. Through employing minimal changes to the conventional DRAM arrays, ARTEMIS efficiently alleviates the costs associated with transformer model execution by supporting stochastic computing for multiplications and temporal analog accumulations using a novel in-DRAM metal-on-metal capacitor. Our analysis indicates that ARTEMIS exhibits at least 3.0x speedup, 1.8x lower energy, and 1.9x better energy efficiency compared to GPU, TPU, CPU, and state-of-the-art PIM transformer hardware accelerators.

[Arxiv](https://arxiv.org/abs/2407.12638)