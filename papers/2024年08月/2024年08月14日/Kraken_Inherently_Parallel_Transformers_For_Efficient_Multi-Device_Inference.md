# Kraken：专为高效多设备推理设计的固有并行变换器

发布时间：2024年08月14日

`LLM应用` `人工智能` `云计算`

> Kraken: Inherently Parallel Transformers For Efficient Multi-Device Inference

# 摘要

> 在追求低延迟以提升用户体验和开启新应用的场景中，大型Transformer网络日益普及。然而，自回归推理的高资源需求迫使其依赖并行化，这不仅成本高昂，还导致硬件资源利用不足。为此，Kraken架构应运而生，它是对标准Transformer的革新，旨在与现有张量并行策略协同，优化多设备系统上的推理效率。通过固定层内模型并行度，Kraken使集体操作与计算并行，有效缩短延迟并提升硬件效能。在OpenWebText训练下，Kraken不仅与标准Transformer困惑度相当，SuperGLUE测试也证实其语言建模能力未减。尤为关键的是，在TensorRT-LLM引擎支持的多GPU环境中，Kraken在各类模型尺寸、上下文长度及张量并行度下，平均提速35.6%，显著缩短了首次令牌生成时间。

> Large Transformer networks are increasingly used in settings where low inference latency can improve the end-user experience and enable new applications. However, autoregressive inference is resource intensive and requires parallelism for efficiency. Parallelism introduces collective communication that is both expensive and represents a phase when hardware resources are underutilized. Towards mitigating this, Kraken is an evolution of the standard Transformer architecture that is designed to complement existing tensor parallelism schemes for efficient inference on multi-device systems. By introducing a fixed degree of intra-layer model parallelism, the architecture allows collective operations to be overlapped with compute, decreasing latency and increasing hardware utilization. When trained on OpenWebText, Kraken models reach a similar perplexity as standard Transformers while also preserving their language modeling capabilities when evaluated on the SuperGLUE benchmark. Importantly, when tested on multi-GPU systems using TensorRT-LLM engines, Kraken speeds up Time To First Token by a mean of 35.6% across a range of model sizes, context lengths, and degrees of tensor parallelism.

[Arxiv](https://arxiv.org/abs/2408.07802)