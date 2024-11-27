# 借助 I/O 感知的部分 KV 缓存重新计算来达成高效的 LLM 推理

发布时间：2024年11月25日

`LLM应用` `计算机硬件` `语言模型`

> Efficient LLM Inference with I/O-Aware Partial KV Cache Recomputation

# 摘要

> 大型语言模型（LLMs）的推理计算量巨大。为降低自回归解码的成本，采用键值（KV）缓存来存储中间激活值，让 GPU 仅进行每个新令牌所需的增量计算。此方法大幅降低了令牌生成的计算开销。然而，KV 缓存所需内存增长迅猛，常超出 GPU 内存容量。经济有效的替代方案是将 KV 缓存转存至 CPU 内存，虽减轻了 GPU 内存压力，却将瓶颈转移至 CPU 与 GPU 间有限的 PCIe 连接带宽上。现有方法试图通过让 GPU 计算与 I/O 重叠或采用 CPU - GPU 异构执行来解决这些问题，却因过多的数据移动和对 CPU 能力的依赖而受阻。本文引入了一种高效的 CPU - GPU I/O 感知的 LLM 推理方法，通过从激活值重新计算部分 KV 缓存，同时经 PCIe 总线传输其余 KV 缓存，避免了将整个 KV 缓存从 CPU 传至 GPU 。该方法使 GPU 重新计算与数据传输重叠，以最小化 GPU 空闲时间，最大化推理性能。我们的方法通过集成利用输入特征和系统硬件信息的分析器模块、优化计算和通信工作负载分布的调度器模块以及高效执行派生执行计划的运行时模块，实现了完全自动化。实验结果表明，与前沿方法相比，我们的方法在解码时实现了高达 35.8%的更低延迟和 46.2%的更高吞吐量。

> Inference for Large Language Models (LLMs) is computationally demanding. To reduce the cost of auto-regressive decoding, Key-Value (KV) caching is used to store intermediate activations, enabling GPUs to perform only the incremental computation required for each new token. This approach significantly lowers the computational overhead for token generation. However, the memory required for KV caching grows rapidly, often exceeding the capacity of GPU memory. A cost-effective alternative is to offload KV cache to CPU memory, which alleviates GPU memory pressure but shifts the bottleneck to the limited bandwidth of the PCIe connection between the CPU and GPU. Existing methods attempt to address these issues by overlapping GPU computation with I/O or employing CPU-GPU heterogeneous execution, but they are hindered by excessive data movement and dependence on CPU capabilities. In this paper, we introduce an efficient CPU-GPU I/O-aware LLM inference method that avoids transferring the entire KV cache from CPU to GPU by recomputing partial KV cache from activations while concurrently transferring the remaining KV cache via PCIe bus. This approach overlaps GPU recomputation with data transfer to minimize idle GPU time and maximize inference performance. Our method is fully automated by integrating a profiler module that utilizes input characteristics and system hardware information, a scheduler module to optimize the distribution of computation and communication workloads, and a runtime module to efficiently execute the derived execution plan. Experimental results show that our method achieves up to 35.8% lower latency and 46.2% higher throughput during decoding compared to state-of-the-art approaches.

[Arxiv](https://arxiv.org/abs/2411.17089)