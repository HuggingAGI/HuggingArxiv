# 用于可扩展的百万令牌推理的上下文并行性

发布时间：2024年11月03日

`LLM应用` `计算机硬件` `人工智能`

> Context Parallelism for Scalable Million-Token Inference

# 摘要

> 我们为长上下文大型语言模型的推理引入了上下文并行机制，在多达 128 个 H100 GPU 跨 16 个节点的情况下，实现了长上下文预填充延迟的近乎线性扩展。特别是，我们的方法能在 77 秒内用 Llama3 405B 模型完成 100 万上下文预填充（并行化效率达 93%，FLOPS 利用率为 63%），3.8 秒内完成 128K 上下文预填充。我们研发了两种无损精确环形注意力变体：pass-KV 和 pass-Q，覆盖了众多使用场景，并具备顶尖性能，包括完全预填充、持久 KV 预填充与解码。在通过 RDMA 和 TCP 相互连接的 H100 GPU 主机上进行的基准测试均显示出长上下文预填充的相似可扩展性，这表明我们的方法在使用具有中低主机间带宽的常见商业数据中心时扩展性良好。

> We present context parallelism for long-context large language model inference, which achieves near-linear scaling for long-context prefill latency with up to 128 H100 GPUs across 16 nodes. Particularly, our method achieves 1M context prefill with Llama3 405B model in 77s (93% parallelization efficiency, 63% FLOPS utilization) and 128K context prefill in 3.8s. We develop two lossless exact ring attention variants: pass-KV and pass-Q to cover a wide range of use cases with the state-of-the-art performance: full prefill, persistent KV prefill and decode. Benchmarks on H100 GPU hosts inter-connected with RDMA and TCP both show similar scalability for long-context prefill, demonstrating that our method scales well using common commercial data center with medium-to-low inter-host bandwidth.

[Arxiv](https://arxiv.org/abs/2411.01783)