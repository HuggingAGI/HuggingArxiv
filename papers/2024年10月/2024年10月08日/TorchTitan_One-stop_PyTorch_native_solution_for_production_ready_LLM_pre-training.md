# TorchTitan：专为生产环境设计的 PyTorch 原生 LLM 预训练一站式解决方案

发布时间：2024年10月08日

`LLM理论` `人工智能` `分布式计算`

> TorchTitan: One-stop PyTorch native solution for production ready LLM pre-training

# 摘要

> 大型语言模型（LLM）的进步极大地推动了自然语言处理的前沿应用。然而，训练这些拥有数十亿参数和万亿级标记的模型，需要复杂的分布式系统来高效整合和比较多种尖端技术。现有解决方案不仅复杂，还分散在多个库中，缺乏互操作性，维护起来也颇为繁琐。因此，设计和比较训练方案需要大量的工程投入。本文推出的 TorchTitan，是一个开源的、基于 PyTorch 的分布式训练系统，它整合了最先进的技术，简化了集成过程，降低了开销。TorchTitan 以模块化方式实现 3D 并行，具备弹性扩展能力，并提供全面的日志记录、检查点和调试工具，确保训练过程的生产就绪。此外，它还采用了硬件与软件协同设计的方案，如 Float8 训练和对称内存等特性。作为一个灵活的测试平台，TorchTitan 支持定制训练方案的开发与比较，帮助我们为 Llama 3.1 优化训练流程，并根据实际经验提供技术选择的指导，以实现最高效率。我们对 TorchTitan 在 Llama 3.1 系列模型（从 80 亿到 4050 亿参数）上进行了全面测试，结果显示其性能卓越，模块化组合性强，且具备弹性扩展能力。通过叠加训练优化，我们在 128 GPU 规模（Llama 3.1 8B）上实现了 65.08% 的加速，在 256 GPU 规模（Llama 3.1 70B）上额外提升了 12.59%，在 512 GPU 规模（Llama 3.1 405B）上通过 3D 并行进一步提升了 30%，均超越了优化基线。

> The development of large language models (LLMs) has been instrumental in advancing state-of-the-art natural language processing applications. Training LLMs with billions of parameters and trillions of tokens require sophisticated distributed systems that enable composing and comparing several state-of-the-art techniques in order to efficiently scale across thousands of accelerators. However, existing solutions are complex, scattered across multiple libraries/repositories, lack interoperability, and are cumbersome to maintain. Thus, curating and empirically comparing training recipes require non-trivial engineering effort.
  This paper introduces TorchTitan, an open-source, PyTorch-native distributed training system that unifies state-of-the-art techniques, streamlining integration and reducing overhead. TorchTitan enables 3D parallelism in a modular manner with elastic scaling, providing comprehensive logging, checkpointing, and debugging tools for production-ready training. It also incorporates hardware-software co-designed solutions, leveraging features like Float8 training and SymmetricMemory. As a flexible test bed, TorchTitan facilitates custom recipe curation and comparison, allowing us to develop optimized training recipes for Llama 3.1 and provide guidance on selecting techniques for maximum efficiency based on our experiences.
  We thoroughly assess TorchTitan on the Llama 3.1 family of LLMs, spanning 8 billion to 405 billion parameters, and showcase its exceptional performance, modular composability, and elastic scalability. By stacking training optimizations, we demonstrate accelerations of 65.08% with 1D parallelism at the 128-GPU scale (Llama 3.1 8B), an additional 12.59% with 2D parallelism at the 256-GPU scale (Llama 3.1 70B), and an additional 30% with 3D parallelism at the 512-GPU scale (Llama 3.1 405B) on NVIDIA H100 GPUs over optimized baselines.

[Arxiv](https://arxiv.org/abs/2410.06511)