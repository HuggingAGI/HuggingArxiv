# MIREncoder：一种基于多模态信息检索的预训练嵌入技术，旨在实现性能优化。

发布时间：2024年07月02日

`LLM应用` `高性能计算` `软件工程`

> MIREncoder: Multi-modal IR-based Pretrained Embeddings for Performance Optimizations

# 摘要

> 在高性能计算领域，提升并行任务性能是研究焦点。当前，深度学习在源代码优化中常通过LLVM中间表示（IRs）提取特征。多数研究聚焦特定任务或依赖预设启发式规则。尽管预训练模型在此领域尚属罕见，但其潜力已引发广泛探讨，尤其是模仿大型语言模型（LLMs）的方案，尽管训练成本高昂。本文提出MIREncoder，一种基于多模态IR的自编码器，预训练后可生成嵌入空间，助力机器学习下游任务。多模态策略强化了从可编译程序中提取特征的能力，优化了代码语法、语义和结构的建模。在代码性能优化中，这些特征至关重要。预训练模型隐含支持迁移学习，减少对特定任务模型的依赖。此外，用于性能优化的预训练模型应低开销且易用。基于此，我们设计了一种兼顾代码理解、迁移学习支持及轻量易用性的建模方法。评估表明，该方法在降低开销的同时，性能超越了现有技术。

> One of the primary areas of interest in High Performance Computing is the improvement of performance of parallel workloads. Nowadays, compilable source code-based optimization tasks that employ deep learning often exploit LLVM Intermediate Representations (IRs) for extracting features from source code. Most such works target specific tasks, or are designed with a pre-defined set of heuristics. So far, pre-trained models are rare in this domain, but the possibilities have been widely discussed. Especially approaches mimicking large-language models (LLMs) have been proposed. But these have prohibitively large training costs. In this paper, we propose MIREncoder, a M}ulti-modal IR-based Auto-Encoder that can be pre-trained to generate a learned embedding space to be used for downstream tasks by machine learning-based approaches. A multi-modal approach enables us to better extract features from compilable programs. It allows us to better model code syntax, semantics and structure. For code-based performance optimizations, these features are very important while making optimization decisions. A pre-trained model/embedding implicitly enables the usage of transfer learning, and helps move away from task-specific trained models. Additionally, a pre-trained model used for downstream performance optimization should itself have reduced overhead, and be easily usable. These considerations have led us to propose a modeling approach that i) understands code semantics and structure, ii) enables use of transfer learning, and iii) is small and simple enough to be easily re-purposed or reused even with low resource availability. Our evaluations will show that our proposed approach can outperform the state of the art while reducing overhead.

[Arxiv](https://arxiv.org/abs/2407.02238)