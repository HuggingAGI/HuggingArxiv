# GPUVM: 由 GPU 驱动的统一虚拟内存

发布时间：2024年11月07日

`其他` `计算机硬件` `高性能计算`

> GPUVM: GPU-driven Unified Virtual Memory

# 摘要

> 图形处理单元（GPU）凭借大规模并行性和大内存带宽，为多媒体渲染、加密货币挖掘、深度学习、自然语言处理等高性能计算应用提供支持。然而，这些应用所需的模型和数据集规模日益增大，单个 GPU 的内存容量已难以承载，从而产生了显著的性能开销。为应对此问题，程序员不得不对数据进行分区，并手动在 GPU 内外传输数据。但这种方式要求程序员精心调试应用程序，对于像深度学习、推荐系统和图形应用这类具有不规则访问模式的工作负载，往往难以实现。为了提升可编程性，可以采用诸如统一虚拟内存（UVM）这样的编程抽象，在整个系统中创建一个虚拟统一的内存空间，并在访问时按需透明地移动数据。不过，UVM 存在操作系统参与的开销，且在 GPU 内存超额预订时，会因产生众多传输请求而效率低下。本文提出了 GPUVM，这是一种 GPU 内存管理系统，它借助具有 RDMA 功能的网络设备构建虚拟内存系统，无需 CPU/OS 参与。GPUVM 为 GPU 应用实现按需分页，依靠 GPU 线程进行内存管理和页面迁移。由于 CPU 芯片组不支持 GPU 驱动的内存管理，我们使用网络接口卡来实现从/到 GPU 的透明页面迁移。对于延迟受限的应用，GPUVM 的性能可达 UVM 的 4 倍，同时提供了便捷的编程抽象，用户无需直接管理内存传输。

> Graphics Processing Units (GPUs) leverage massive parallelism and large memory bandwidth to support high-performance computing applications, such as multimedia rendering, crypto-mining, deep learning, and natural language processing. These applications require models and datasets that are getting bigger in size and currently challenge the memory capacity of a single GPU, causing substantial performance overheads. To address this problem, a programmer has to partition the data and manually transfer data in and out of the GPU. This approach requires programmers to carefully tune their applications and can be impractical for workloads with irregular access patterns, such as deep learning, recommender systems, and graph applications. To ease programmability, programming abstractions such as unified virtual memory (UVM) can be used, creating a virtually unified memory space across the whole system and transparently moving the data on demand as it is accessed. However, UVM brings in the overhead of the OS involvement and inefficiencies due to generating many transfer requests especially when the GPU memory is oversubscribed. This paper proposes GPUVM, a GPU memory management system that uses an RDMA-capable network device to construct a virtual memory system without involving the CPU/OS. GPUVM enables on-demand paging for GPU applications and relies on GPU threads for memory management and page migration. Since CPU chipsets do not support GPU-driven memory management, we use a network interface card to facilitate transparent page migration from/to the GPU. GPUVM achieves performance up to 4x higher than UVM for latency-bound applications while providing accessible programming abstractions that do not require the users to manage memory transfers directly.

[Arxiv](https://arxiv.org/abs/2411.05309)