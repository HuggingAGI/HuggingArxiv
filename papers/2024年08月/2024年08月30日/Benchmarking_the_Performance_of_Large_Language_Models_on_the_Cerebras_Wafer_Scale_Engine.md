# 大型语言模型在 Cerebras Wafer Scale Engine 上的性能基准测试

发布时间：2024年08月30日

`LLM应用` `计算机视觉`

> Benchmarking the Performance of Large Language Models on the Cerebras Wafer Scale Engine

# 摘要

> 基于Transformer的LLMs在NLP和CV领域已达到顶尖水平。这些模型通过MHSA机制捕捉长距离关系，性能远超以往方法。本文评估了LLMs在Cerebras WSE上的表现，该系统拥有2.6万亿晶体管、850,000核心和40 GB片上内存，通过SLAC核心和优化路由，显著提升了计算效率。随着LLMs的普及，我们探讨了Cerebras WSE如何通过其20 PB/s高带宽内存突破传统内存瓶颈，并通过屋顶线模型分析其性能扩展性，以应对高计算密集型任务。

> Transformer based Large Language Models (LLMs) have recently reached state of the art performance in Natural Language Processing (NLP) and Computer Vision (CV) domains. LLMs use the Multi-Headed Self-Attention (MHSA) mechanism to capture long-range global attention relationships among input words or image patches, drastically improving its performance over prior deep learning approaches. In this paper, we evaluate the performance of LLMs on the Cerebras Wafer Scale Engine (WSE). Cerebras WSE is a high performance computing system with 2.6 trillion transistors, 850,000 cores and 40 GB on-chip memory. Cerebras WSE's Sparse Linear Algebra Compute (SLAC) cores eliminates multiply-by-zeros operations and its 40 GB of on-chip memory is uniformly distributed among SLAC cores, enabling fast local access to model parameters. Moreover, Cerebras software configures routing between cores at runtime, optimizing communication overhead among cores. As LLMs are becoming more commonly used, new hardware architectures are needed to accelerate LLMs training and inference. We benchmark the effectiveness of this hardware architecture at accelerating LLMs training and inference. Additionally, we analyze if Cerebras WSE can scale the memory-wall associated with traditionally memory-bound compute tasks using its 20 PB/s high bandwidth memory. Furthermore, we examine the performance scalability of Cerebras WSE through a roofline model. By plotting performance metrics against computational intensity, we aim to assess their effectiveness at handling high compute-intensive LLMs training and inference tasks.

[Arxiv](https://arxiv.org/abs/2409.00287)