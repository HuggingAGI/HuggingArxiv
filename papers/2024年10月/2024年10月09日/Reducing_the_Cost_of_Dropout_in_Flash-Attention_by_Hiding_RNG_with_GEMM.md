# 借助 GEMM 隐藏 RNG，巧妙降低 Flash-Attention 中 Dropout 的开销。

发布时间：2024年10月09日

`LLM理论` `人工智能` `高性能计算`

> Reducing the Cost of Dropout in Flash-Attention by Hiding RNG with GEMM

# 摘要

> Dropout 的启用可能会显著影响 Flash-Attention 的性能，进而增加 LLM 的训练时间。主要原因是传统的 RNG 阶段被融合到 Flash-Attention 内核中，而 RNG 和 Attention 共享硬件瓶颈，导致 RNG 延迟难以隐藏。  我们提出将 RNG 与前一层 GEMM 重叠，以隐藏 RNG 运行时间并提升端到端性能。RNG 和 GEMM 具有不同的资源需求和硬件瓶颈，因此可以并行运行而不影响彼此性能。我们的细粒度性能模型显示，在 Llama2 的一个 transformer 块上实现了 1.14 倍的加速，在 GH100 GPU 上使用 FP8 精度时，最高可达 1.23 倍的加速。此外，我们将理论模型扩展到不同的 RNG 实现和硬件架构，并讨论了将 RNG 与 GEMM 层重叠的广泛适用的好处。

> Dropout, a network operator, when enabled is likely to dramatically impact the performance of Flash-Attention, which in turn increases the end-to-end training time of Large-Language-Models (LLMs). The main contributor to such performance degradation is the Random Number Generation (RNG) phase that is traditionally fused into the Flash-Attention kernel. As RNG and Attention have the same hardware bottlenecks, RNG latency can hardly be hidden within the Attention kernel.
  We propose overlapping RNG with previous GEMM layers in the network to hide RNG runtime and improve end-to-end performance. RNG and GEMM have distinct resource requirements and hardware bottlenecks, so they can run in parallel without compromising each other's performance. Our fine-grained performance model, cross-validated by silicon results, shows 1.14x speedup on one transformer block (including multi-head attention and feed-forward layers) for Llama2, and up to 1.23x speedup when varying workload sizes, on GH100 GPUs with FP8 precision. Further, we extend our theoretical model to different RNG implementations and hardware architectures, and discuss the widely applicable benefits for overlapping RNG with GEMM layers.

[Arxiv](https://arxiv.org/abs/2410.07531)