# 利用延迟同步遍历技术，加速基于图的向量搜索过程

发布时间：2024年06月18日

`LLM应用

理由：这篇论文主要关注的是向量搜索系统在大型语言模型服务、搜索引擎和推荐系统中的应用，特别是提出了一个硬件-算法协同设计方案，包括专为基于图的向量搜索（GVS）设计的加速器Falcon和优化的图遍历算法DST。这些技术旨在最小化在线搜索延迟，提高搜索性能和质量，这些都是大型语言模型应用中的关键技术。因此，这篇论文更适合归类于LLM应用。` `搜索引擎` `推荐系统`

> Accelerating Graph-based Vector Search via Delayed-Synchronization Traversal

# 摘要

> 在大型语言模型服务、搜索引擎和推荐系统中，向量搜索系统是不可或缺的，关键在于最小化在线搜索延迟。基于图的向量搜索（GVS）因其卓越的搜索性能和质量而备受青睐。为此，我们提出了一种创新的硬件-算法协同设计方案，其中包括Falcon——一种专为GVS设计的加速器，以及延迟同步遍历（DST）——一种专为加速器优化的图遍历算法。Falcon通过集成片上布隆过滤器来减少内存访问，实现了高效的GVS操作。而DST则通过优化图遍历顺序，大幅提升了加速器的利用率，从而提高了搜索性能和质量。经过在多个图和数据集上的严格测试，我们的Falcon原型在FPGA上与DST结合，相比基于CPU和GPU的GVS系统，在延迟上实现了高达4.3倍和19.5倍的速度提升，在能效上实现了高达8.0倍和26.9倍的显著改进。Falcon和DST的出色表现，预示着它们有望成为未来GVS加速领域的标准解决方案。

> Vector search systems are indispensable in large language model (LLM) serving, search engines, and recommender systems, where minimizing online search latency is essential. Among various algorithms, graph-based vector search (GVS) is particularly popular due to its high search performance and quality. To efficiently serve low-latency GVS, we propose a hardware-algorithm co-design solution including Falcon, a GVS accelerator, and Delayed-Synchronization Traversal (DST), an accelerator-optimized graph traversal algorithm. Falcon implements high-performance GVS operators and reduces memory accesses with an on-chip Bloom filter to track search states. DST improves search performance and quality by relaxing the graph traversal order to maximize accelerator utilization. Evaluation across various graphs and datasets shows that our Falcon prototype on FPGAs, coupled with DST, achieves up to 4.3$\times$ and 19.5$\times$ speedups in latency and up to 8.0$\times$ and 26.9$\times$ improvements in energy efficiency over CPU and GPU-based GVS systems. The remarkable efficiency of Falcon and DST demonstrates their potential to become the standard solutions for future GVS acceleration.

![利用延迟同步遍历技术，加速基于图的向量搜索过程](../../../paper_images/2406.12385/brewing_time_comparison.pdf)

![利用延迟同步遍历技术，加速基于图的向量搜索过程](../../../paper_images/2406.12385/brewing_quality_comparison.pdf)

[Arxiv](https://arxiv.org/abs/2406.12385)