# 利用延迟同步遍历技术，加速基于图的向量搜索过程

发布时间：2024年06月18日

`LLM应用

这篇论文主要讨论了在大型语言模型服务、搜索引擎和推荐系统中，如何通过结合硬件与算法的协同设计来优化基于图的向量搜索系统（GVS），以减少在线搜索延迟。具体来说，论文提出了一种名为Falcon的GVS加速器和一种名为延迟同步遍历（DST）的图遍历算法，这些技术旨在提高搜索性能和质量。因此，这篇论文的内容与大型语言模型的应用紧密相关，特别是在优化搜索系统方面，属于LLM应用分类。` `搜索引擎` `推荐系统`

> Accelerating Graph-based Vector Search via Delayed-Synchronization Traversal

# 摘要

> 在大型语言模型服务、搜索引擎和推荐系统中，向量搜索系统是不可或缺的，关键在于减少在线搜索延迟。基于图的向量搜索（GVS）因其卓越的搜索性能和质量而备受青睐。为此，我们提出了一种结合硬件与算法的协同设计方案，其中包括Falcon——一种GVS加速器，以及延迟同步遍历（DST）——一种专为加速器优化的图遍历算法。Falcon通过内置的高性能GVS操作和片上布隆过滤器减少内存访问，有效跟踪搜索状态。DST则通过调整图遍历顺序，最大化加速器利用率，从而提升搜索性能和质量。实验结果表明，在FPGA上运行的Falcon原型结合DST，相比基于CPU和GPU的GVS系统，在延迟上实现了高达4.3倍和19.5倍的速度提升，在能效上实现了高达8.0倍和26.9倍的改进。Falcon与DST的高效表现预示着它们有望成为未来GVS加速的标准方案。

> Vector search systems are indispensable in large language model (LLM) serving, search engines, and recommender systems, where minimizing online search latency is essential. Among various algorithms, graph-based vector search (GVS) is particularly popular due to its high search performance and quality. To efficiently serve low-latency GVS, we propose a hardware-algorithm co-design solution including Falcon, a GVS accelerator, and Delayed-Synchronization Traversal (DST), an accelerator-optimized graph traversal algorithm. Falcon implements high-performance GVS operators and reduces memory accesses with an on-chip Bloom filter to track search states. DST improves search performance and quality by relaxing the graph traversal order to maximize accelerator utilization. Evaluation across various graphs and datasets shows that our Falcon prototype on FPGAs, coupled with DST, achieves up to 4.3$\times$ and 19.5$\times$ speedups in latency and up to 8.0$\times$ and 26.9$\times$ improvements in energy efficiency over CPU and GPU-based GVS systems. The remarkable efficiency of Falcon and DST demonstrates their potential to become the standard solutions for future GVS acceleration.

![利用延迟同步遍历技术，加速基于图的向量搜索过程](../../../paper_images/2406.12385/brewing_time_comparison.pdf)

![利用延迟同步遍历技术，加速基于图的向量搜索过程](../../../paper_images/2406.12385/brewing_quality_comparison.pdf)

[Arxiv](https://arxiv.org/abs/2406.12385)