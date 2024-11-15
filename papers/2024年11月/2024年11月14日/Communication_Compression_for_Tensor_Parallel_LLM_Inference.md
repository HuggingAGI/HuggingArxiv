# 张量并行大语言模型推理中的通信压缩

发布时间：2024年11月14日

`LLM应用` `人工智能` `硬件加速`

> Communication Compression for Tensor Parallel LLM Inference

# 摘要

> 大型语言模型（LLMs）引领了人工智能的前沿发展，但其包含数千亿的参数和操作。为降低推理延迟，LLMs 借助多种模型并行策略部署在多个硬件加速器上。我们的论文深入探究了其中一种策略——张量并行，并提议通过压缩加速器间的通信来减少延迟。我们运用细粒度量化技术，将选定的激活压缩 3.5 至 4.5 倍。我们提出的方法能使首次令牌生成时间（TTFT）最多减少 2 倍，且模型性能的下降微乎其微。

> Large Language Models (LLMs) have pushed the frontier of artificial intelligence but are comprised of hundreds of billions of parameters and operations. For faster inference latency, LLMs are deployed on multiple hardware accelerators through various Model Parallelism strategies. Our paper looks into the details on one such strategy - Tensor Parallel - and proposes to reduce latency by compressing inter-accelerator communication. We leverage fine grained quantization techniques to compress selected activations by 3.5 - 4.5x. Our proposed method leads up to 2x reduction of time-to-first-token (TTFT) with negligible model performance degradation.

[Arxiv](https://arxiv.org/abs/2411.09510)