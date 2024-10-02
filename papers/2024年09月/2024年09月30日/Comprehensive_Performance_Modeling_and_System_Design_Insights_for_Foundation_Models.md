# 深入探讨基础模型的性能建模与系统设计

发布时间：2024年09月30日

`LLM理论` `高性能计算` `人工智能`

> Comprehensive Performance Modeling and System Design Insights for Foundation Models

# 摘要

> 生成式 AI，尤其是大型变压器模型，正逐渐成为科学和工业中 HPC 系统设计的核心驱动力。我们深入分析了这些模型的性能特征，探讨了它们对变压器类型、并行策略及 HPC 系统特性的敏感性。通过一个性能模型，我们得以探索这一复杂设计领域，并揭示其核心要素。研究发现，不同变压器模型在不同训练阶段对并行性和系统特性的需求各异。大型语言模型在 3D 并行下表现出色，仅在预训练阶段对网络需求有所增加，且对加速器容量和带宽的依赖性降低。而代表科学基础模型的长序列变压器，则对网络和容量有更均衡的需求，并需借助 4D 并行性。我们的分析强调，针对不同变压器类型进行更精细的性能建模至关重要，同时展示了实现这一目标的路径。我们的代码已开源，供大家参考。

> Generative AI, in particular large transformer models, are increasingly driving HPC system design in science and industry. We analyze performance characteristics of such transformer models and discuss their sensitivity to the transformer type, parallelization strategy, and HPC system features (accelerators and interconnects). We utilize a performance model that allows us to explore this complex design space and highlight its key components. We find that different transformer types demand different parallelism and system characteristics at different training regimes. Large Language Models are performant with 3D parallelism and amplify network needs only at pre-training scales with reduced dependence on accelerator capacity and bandwidth. On the other hand, long-sequence transformers, representative of scientific foundation models, place a more uniform dependence on network and capacity with necessary 4D parallelism. Our analysis emphasizes the need for closer performance modeling of different transformer types keeping system features in mind and demonstrates a path towards this. Our code is available as open-source.

[Arxiv](https://arxiv.org/abs/2410.00273)