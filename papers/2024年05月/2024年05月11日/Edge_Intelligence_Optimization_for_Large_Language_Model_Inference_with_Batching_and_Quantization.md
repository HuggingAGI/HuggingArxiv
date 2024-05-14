# 大型语言模型推理的边缘智能优化：通过批处理与量化技术提升效率。

发布时间：2024年05月11日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在边缘智能环境中的推理优化问题，提出了一个针对LLM推理的边缘智能优化方案。它关注的是LLMs在资源受限的边缘设备上的实际应用问题，如模型规模、自回归过程和自注意力机制的优化。论文通过批处理和模型量化技术来构建推理模型，并设计了一种在线树修剪的深度优先树搜索算法来解决资源分配问题。这些内容都是关于LLMs在实际应用中的优化和挑战，因此属于LLM应用分类。` `边缘计算` `人工智能优化`

> Edge Intelligence Optimization for Large Language Model Inference with Batching and Quantization

# 摘要

> 生成式人工智能（GAI）以其卓越的内容创造力引领潮流，大型语言模型（LLMs）更是这场革命的先锋。然而，LLMs对资源的巨大需求往往需要云端支持，这带来了隐私、延迟和使用限制的挑战。尽管边缘智能通过在数据源附近的边缘资源上实现实时AI计算来应对这些挑战，但大多数研究仍聚焦于传统AI模型，忽视了LLM推理的独特性，如庞大的模型规模、自回归过程和自注意力机制。本文针对LLM推理提出了一个边缘智能优化方案。我们通过在资源受限的边缘设备上应用批处理和模型量化技术，为基于变压器解码器的LLMs构建了一个推理模型。我们的方法旨在通过批处理调度和资源联合分配来提升推理吞吐量，同时兼顾边缘资源限制和用户对延迟与精度的不同需求。为了解决这一NP难问题，我们设计了一种在线树修剪的深度优先树搜索算法（DFTSP），该算法在可接受的时序复杂度内运行。模拟结果显示，DFTSP在各种用户场景和量化技术中均优于其他批处理基准，与暴力搜索方法相比，时间复杂度降低了超过45%。

> Generative Artificial Intelligence (GAI) is taking the world by storm with its unparalleled content creation ability. Large Language Models (LLMs) are at the forefront of this movement. However, the significant resource demands of LLMs often require cloud hosting, which raises issues regarding privacy, latency, and usage limitations. Although edge intelligence has long been utilized to solve these challenges by enabling real-time AI computation on ubiquitous edge resources close to data sources, most research has focused on traditional AI models and has left a gap in addressing the unique characteristics of LLM inference, such as considerable model size, auto-regressive processes, and self-attention mechanisms. In this paper, we present an edge intelligence optimization problem tailored for LLM inference. Specifically, with the deployment of the batching technique and model quantization on resource-limited edge devices, we formulate an inference model for transformer decoder-based LLMs. Furthermore, our approach aims to maximize the inference throughput via batch scheduling and joint allocation of communication and computation resources, while also considering edge resource constraints and varying user requirements of latency and accuracy. To address this NP-hard problem, we develop an optimal Depth-First Tree-Searching algorithm with online tree-Pruning (DFTSP) that operates within a feasible time complexity. Simulation results indicate that DFTSP surpasses other batching benchmarks in throughput across diverse user settings and quantization techniques, and it reduces time complexity by over 45% compared to the brute-force searching method.

[Arxiv](https://arxiv.org/abs/2405.07140)