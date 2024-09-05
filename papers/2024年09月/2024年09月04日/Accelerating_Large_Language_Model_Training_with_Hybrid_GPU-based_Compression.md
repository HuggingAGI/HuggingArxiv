# 利用混合 GPU 压缩技术加速大型语言模型的训练过程

发布时间：2024年09月04日

`LLM理论` `超级计算` `人工智能`

> Accelerating Large Language Model Training with Hybrid GPU-based Compression

# 摘要

> 数据并行、张量并行和流水线并行是加速大型语言模型训练的三种常用策略。然而，这些方法通过密集的数据通信来处理梯度、激活等关键信息，带来了不小的开销。通过与GPU压缩库协同设计，MPI库已被证实能大幅减小通信量，提升训练效率，同时保持精度。在本研究中，我们探索了在分布式LLM训练中，结合3D并行和ZeRO优化，使用压缩辅助MPI集合的效果。我们在Lassen超级计算机上使用了192个V100 GPU进行实验。首先，我们实施了一种简单的全局压缩方案，结果显示GPT-NeoX-20B训练的性能有所提升，但忽略了不同并行维度间消息稀疏性的差异，导致训练损失下降。为此，我们针对不同并行维度采用了混合压缩策略，并调整了压缩力度。对于具有低秩结构的梯度，我们采用了更激进的压缩；而对于激活、优化器状态和模型参数，我们则采用了较温和的压缩以保持精度。最终，通过这种调整后的混合压缩方案，我们在保持基准损失收敛的同时，进一步提升了训练性能。

> Data Parallelism (DP), Tensor Parallelism (TP), and Pipeline Parallelism (PP) are the three strategies widely adopted to enable fast and efficient Large Language Model (LLM) training. However, these approaches rely on data-intensive communication routines to collect, aggregate, and re-distribute gradients, activations, and other important model information, which pose significant overhead. Co-designed with GPU-based compression libraries, MPI libraries have been proven to reduce message size significantly, and leverage interconnect bandwidth, thus increasing training efficiency while maintaining acceptable accuracy.
  In this work, we investigate the efficacy of compression-assisted MPI collectives under the context of distributed LLM training using 3D parallelism and ZeRO optimizations. We scaled up to 192 V100 GPUs on the Lassen supercomputer. First, we enabled a naïve compression scheme across all collectives and observed a 22.5\% increase in TFLOPS per GPU and a 23.6\% increase in samples per second for GPT-NeoX-20B training. Nonetheless, such a strategy ignores the sparsity discrepancy among messages communicated in each parallelism degree, thus introducing more errors and causing degradation in training loss. Therefore, we incorporated hybrid compression settings toward each parallel dimension and adjusted the compression intensity accordingly. Given their low-rank structure (arXiv:2301.02654), we apply aggressive compression on gradients when performing DP All-reduce. We adopt milder compression to preserve precision while communicating activations, optimizer states, and model parameters in TP and PP. Using the adjusted hybrid compression scheme, we demonstrate a 17.3\% increase in TFLOPS per GPU and a 12.7\% increase in samples per second while reaching baseline loss convergence.

[Arxiv](https://arxiv.org/abs/2409.02423)