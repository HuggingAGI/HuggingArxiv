# 在 GPU 张量核心上，为大型语言模型提供高效且灵活的精度加速方案。

发布时间：2024年09月26日

`LLM理论` `人工智能` `高性能计算`

> Efficient Arbitrary Precision Acceleration for Large Language Models on GPU Tensor Cores

# 摘要

> 大型语言模型（LLM）虽广泛应用，但在高效推理上仍遇难题。量化虽减计算负担，但超低比特任意精度因 GPU Tensor Core 支持不足及内存管理低效，加速效果欠佳。为此，我们提出全面加速方案。核心是创新双极性-INT 数据格式，促并行计算，支持对称量化，减数据冗余。进而，实现任意精度矩阵乘法，比特级分解与恢复矩阵，灵活精度，最大化 GPU Tensor Core 利用。再者，高效矩阵预处理，优化数据布局。最后，设计数据恢复导向内存管理，战略用快速共享内存，大幅提升内核执行速度，减内存访问延迟。实验显示，矩阵乘法比 NVIDIA 的 CUTLASS 快 13 倍。集成 LLM 后，推理加速达 6.7 倍。这些改进极大提升 LLM 推理效率，使其应用更广、响应更快。

> Large language models (LLMs) have been widely applied but face challenges in efficient inference. While quantization methods reduce computational demands, ultra-low bit quantization with arbitrary precision is hindered by limited GPU Tensor Core support and inefficient memory management, leading to suboptimal acceleration. To address these challenges, we propose a comprehensive acceleration scheme for arbitrary precision LLMs. At its core, we introduce a novel bipolar-INT data format that facilitates parallel computing and supports symmetric quantization, effectively reducing data redundancy. Building on this, we implement an arbitrary precision matrix multiplication scheme that decomposes and recovers matrices at the bit level, enabling flexible precision while maximizing GPU Tensor Core utilization. Furthermore, we develop an efficient matrix preprocessing method that optimizes data layout for subsequent computations. Finally, we design a data recovery-oriented memory management system that strategically utilizes fast shared memory, significantly enhancing kernel execution speed and minimizing memory access latency. Experimental results demonstrate our approach's effectiveness, with up to 13\times speedup in matrix multiplication compared to NVIDIA's CUTLASS. When integrated into LLMs, we achieve up to 6.7\times inference acceleration. These improvements significantly enhance LLM inference efficiency, enabling broader and more responsive applications of LLMs.

[Arxiv](https://arxiv.org/abs/2409.17870)