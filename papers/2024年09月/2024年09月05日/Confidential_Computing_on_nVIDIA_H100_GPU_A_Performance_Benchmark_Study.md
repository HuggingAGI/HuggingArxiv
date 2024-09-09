# nVIDIA H100 GPU 机密计算性能基准研究

发布时间：2024年09月05日

`LLM应用` `半导体` `人工智能`

> Confidential Computing on nVIDIA H100 GPU: A Performance Benchmark Study

# 摘要

> 本报告探讨了在 NVIDIA H100 GPU 上启用 TEE 对 LLM 推理任务的性能影响。我们通过不同模型和令牌长度测试了 TEE 模式的开销，发现尽管 GPU 内部计算开销微乎其微，但主要性能瓶颈在于数据传输。对于大多数 LLM 查询，开销低于 5%，而大型模型和长序列几乎无额外开销。

> This report evaluates the performance impact of enabling Trusted Execution Environments (TEE) on NVIDIA H100 GPUs for large language model (LLM) inference tasks. We benchmark the overhead introduced by TEE mode across various models and token lengths, focusing on the bottleneck caused by CPU-GPU data transfers via PCIe. Our results show that while there is minimal computational overhead within the GPU, the overall performance penalty is primarily due to data transfer. For most typical LLM queries, the overhead remains below 5%, with larger models and longer sequences experiencing near-zero overhead.

[Arxiv](https://arxiv.org/abs/2409.03992)