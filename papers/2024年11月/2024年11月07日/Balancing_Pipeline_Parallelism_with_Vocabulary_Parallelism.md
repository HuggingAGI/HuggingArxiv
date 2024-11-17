# 实现管道并行性与词汇并行性的平衡

发布时间：2024年11月07日

`LLM应用` `计算机系统`

> Balancing Pipeline Parallelism with Vocabulary Parallelism

# 摘要

> 管道并行在扩展基于 Transformer 的大型语言模型训练方面应用广泛，为提升其吞吐量和降低内存占用，已开展了诸多工作。本文聚焦一个常被忽略的问题：词汇层会致使管道各阶段的计算和内存使用失衡，加重管道气泡和内存瓶颈。对此，我们在管道设备间均匀划分词汇层，并将计算归入管道阶段。为降低激活内存开销，我们提出若干算法以减少词汇层内的通信障碍。此外，我们采用通用方法将词汇并行与现有管道调度相融合。通过这些技术的结合，我们的方法有效平衡了计算和参数内存，仅产生少量恒定的激活内存开销。值得一提的是，与像 V-Half 这样的激活内存平衡调度相结合时，我们的方法在内存和计算上达到了完美平衡。大量评估显示，无论词汇规模大小，我们的方法都实现了计算和内存的平衡，相较于常规方法，吞吐量提升 5%至 51%，同时大幅降低了峰值内存使用，在大词汇量场景下尤为显著。我们的实现已在 https://github.com/sail-sg/VocabularyParallelism 开源。

> Pipeline parallelism is widely used to scale the training of transformer-based large language models, various works have been done to improve its throughput and memory footprint. In this paper, we address a frequently overlooked issue: the vocabulary layers can cause imbalanced computation and memory usage across pipeline stages, worsening pipeline bubbles and the memory bottleneck. To tackle this, we partition the vocabulary layers evenly across pipeline devices and group the computation into pipeline passes. To reduce the activation memory overhead, we propose several algorithms to reduce communication barriers within vocabulary layers. Additionally, we utilize a generalizable method to integrate Vocabulary Parallelism with existing pipeline schedules. By combining these techniques, our methods effectively balance the computation and parameter memory, with only a small constant activation memory overhead. Notably, when combined with activation memory-balanced schedules like V-Half, our approach achieves perfect balance in both memory and computation. Extensive evaluations demonstrate that our method achieves computation and memory balance regardless of the vocabulary size, resulting in a 5% to 51% improvement in throughput compared to naive approaches, meanwhile significantly reducing peak memory usage especially for large vocabulary scenarios. Our implementation is open-sourced at https://github.com/sail-sg/VocabularyParallelism .

[Arxiv](https://arxiv.org/abs/2411.05288)