# LumosCore：具有光互连的高度可扩展的大型语言模型集群

发布时间：2024年11月03日

`其他` `计算机硬件` `通信技术`

> LumosCore: Highly Scalable LLM Clusters with Optical Interconnect

# 摘要

> 大型语言模型（LLM）技术的出现导致模型对计算资源的需求迅速增长。作为回应，企业正在构建拥有 1 万甚至更多 GPU 的大规模多租户 GPU 集群。与迅速增长的集群规模相比，集群的带宽也一直在增加以满足通信需求，800 Gbps 光模块已经实际使用，1.6 Tbps 模块即将出现。然而，由于电交换芯片容量有限，设计同时满足大规模和高带宽要求的集群具有挑战性。与电交换芯片不同，MEMS-OCS 的单端口带宽仅由光模块决定，因此很容易同时满足带宽和可扩展性要求。在本文中，我们提出了一种称为	extbf{LumosCore}的光电混合架构。我们通过物理拓扑和逻辑拓扑设计解决了 L2 协议不兼容、潜在网络争用和算法时间复杂度的问题。此外，我们设计了一个多项式时间复杂度的链路重配置算法，以最小的时间开销重新配置 MEMS-OCS。我们在一个由 128 个 NPU 组成的集群中验证了所提出方案的可行性，并通过基于真实跟踪的模拟，证明了	extbf{LumosCore}相对于传统架构的优越性。

> The emergence of Large Language Model(LLM) technologies has led to a rapidly growing demand for compute resources in models. In response, the enterprises are building large-scale multi-tenant GPU clusters with 10k or even ore GPUs. In contrast to the rapidly growing cluster size, the bandwidth of clusters has also been increasing to meet communication demands, with 800 Gbps optical modules already in practical use and 1.6 Tbps modules on the horizon. However, designing clusters that simultaneously meet the requirements of large scale and high bandwidth is challenging due to the limited capacity of electrical switch chips. Unlike electrical switch chips, the single-port bandwidth of MEMS-OCS is solely determined by the optical module, making it straightforward to achieve both bandwidth and scability requirement. In this paper, we propose an opto-electronic hybrid architecture called \textbf{LumosCore}. We address the issues of L2 protocols incompatibility potential network contention and algorithm time complexity through physical topology and logical topology design. Additionally, we design a polynomial-time complexity link reconfiguration algorithm to reconfigure MEMS-OCS with minimal time overhead. We validate the feasibility of the proposed scheme in a cluster consisting of 128 NPUs, and through simulation based on real traces, we demonstrate the superiority of \textbf{LumosCore} over traditional architectures.

[Arxiv](https://arxiv.org/abs/2411.01503)