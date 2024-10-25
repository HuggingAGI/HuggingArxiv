# 分散的专家混合体实现

发布时间：2024年03月13日

`其他` `计算机硬件` `人工智能`

> Scattered Mixture-of-Experts Implementation

# 摘要

> 摘要：我们提出了 ScatterMoE，这是在 GPU 上的稀疏专家混合（SMoE）的一种实现。ScatterMoE 基于现有的实现，并克服了一些限制以提高推理和训练速度以及内存占用。这种实现通过避免填充和对输入进行过多的复制来实现这一点。我们引入了 ParallelLinear，这是我们用于构建我们的实现的主要组件以及用于加速操作的各种内核。我们将我们的实现与 Megablocks 进行基准测试，并表明它能够实现更高的吞吐量和更低的内存占用。我们还展示了 ParallelLinear 如何通过展示注意力混合的实现来扩展专家混合的概念。

> 
Abstract:We present ScatterMoE, an implementation of Sparse Mixture-of-Experts (SMoE) on GPUs. ScatterMoE builds upon existing implementations, and overcoming some of the limitations to improve inference and training speed, and memory footprint. This implementation achieves this by avoiding padding and making excessive copies of the input. We introduce ParallelLinear, the main component we use to build our implementation and the various kernels used to speed up the operation. We benchmark our implementation against Megablocks, and show that it enables a higher throughput and lower memory footprint. We also show how ParallelLinear enables extension of the Mixture-of-Experts concept by demonstrating with an implementation of Mixture of Attention.
    

[Arxiv](https://arxiv.org/pdf/2403.08245)