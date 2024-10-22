# DRIM-ANN：一款基于商用 DRAM-PIM 技术的近似最近邻搜索引擎

发布时间：2024年10月20日

`RAG` `信息检索` `大数据`

> DRIM-ANN: An Approximate Nearest Neighbor Search Engine based on Commercial DRAM-PIMs

# 摘要

> 近似最近邻搜索 (ANNS) 在大数据集中实现高效的语义相似性搜索，已成为信息检索和检索增强生成 (RAG) 等关键应用的基本组成部分。然而，ANNS 是一个众所周知的 I/O 密集型算法，计算与 I/O 比率低，通常由于高维数据的大量体积而需要大量存储。这导致在 CPU 上出现 I/O 瓶颈，在 GPU 上出现内存限制。基于 DRAM 的内存处理 (DRAM-PIM) 架构，提供高带宽、大容量内存和在数据附近或内部进行高效计算的能力，为 ANNS 提供了一个有前景的解决方案。在这项工作中，我们首次研究了商业 DRAM-PIM 在 ANNS 中的应用，并提出了 DRIM-ANN，一个基于 UPMEM 的 DRAM-PIM 优化的 ANNS 引擎。值得注意的是，鉴于目标 DRAM-PIM 的计算与 I/O 比率甚至低于基本 ANNS，我们利用查找表 (LUT) 来替换更多的乘法运算为 I/O 操作。然后，我们系统地调整 ANNS 以搜索优化配置，降低计算负载，使 ANNS 的计算与 I/O 比率与 DRAM-PIM 相匹配，同时保持精度约束。在此调整后的 ANNS 算法基础上，我们进一步探索实现优化，以充分利用 DRAM-PIM 中的两千个并行处理单元及其私有本地内存。为了解决由 ANNS 请求分布在大型数据集的不同集群中引起的负载不平衡问题，我们提出了一种结合静态数据布局优化和动态运行时请求调度的负载均衡策略。在代表性数据集上的实验结果显示，DRIM-ANN 相对于 32 线程 CPU 实现了平均 2.92 倍的性能提升。

> Approximate Nearest Neighbor Search (ANNS), which enables efficient semantic similarity search in large datasets, has become a fundamental component of critical applications such as information retrieval and retrieval-augmented generation (RAG). However, ANNS is a well-known I/O-intensive algorithm with a low compute-to-I/O ratio, often requiring massive storage due to the large volume of high-dimensional data. This leads to I/O bottlenecks on CPUs and memory limitations on GPUs. DRAM-based Processing-in-Memory (DRAM-PIM) architecture, which offers high bandwidth, large-capacity memory, and the ability to perform efficient computation in or near the data, presents a promising solution for ANNS. In this work, we investigate the use of commercial DRAM-PIM for ANNS for the first time and propose DRIM-ANN, an optimized ANNS engine based on DRAM-PIMs from UPMEM. Notably, given that the target DRAM-PIM exhibits an even lower compute-to-I/O ratio than basic ANNS, we leverage lookup tables (LUTs) to replace more multiplications with I/O operations. We then systematically tune ANNS to search optimized configurations with lower computational load, aligning the compute-to-I/O ratio of ANNS with that of DRAM-PIMs while maintaining accuracy constraints. Building on this tuned ANNS algorithm, we further explore implementation optimizations to fully utilize the two thousand parallel processing units with private local memory in DRAM-PIMs. To address the load imbalance caused by ANNS requests distributed across different clusters of large datasets, we propose a load-balancing strategy that combines static data layout optimization with dynamic runtime request scheduling. Experimental results on representative datasets show that DRIM-ANN achieves an average performance speedup of 2.92x compared to a 32-thread CPU counterpart.

[Arxiv](https://arxiv.org/abs/2410.15621)