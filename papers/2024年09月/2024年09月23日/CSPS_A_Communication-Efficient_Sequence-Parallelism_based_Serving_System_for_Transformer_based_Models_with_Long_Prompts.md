# CSPS：一种高效通信的序列并行服务系统，专为处理长提示的Transformer模型设计

发布时间：2024年09月23日

`LLM应用` `互联网` `云计算`

> CSPS: A Communication-Efficient Sequence-Parallelism based Serving System for Transformer based Models with Long Prompts

# 摘要

> 长序列生成的 LLM 应用日益流行。本文通过跟踪实验发现，现有方法因顺序块处理导致高 TTFT，因批量长序列预填充和解码导致长 TBT，因长序列的受限 KVC 导致低吞吐量。为此，我们提出两种 SP 架构，但面临网络通信和计算瓶颈，以及 KV 值分布增加 TBT 的问题。我们提出 CSA 和三阶段流水线，以及基于 SP 的解码，通过移动 Q 值减少通信开销。这些方法构建了 SPS2 系统，显著提升了 TTFT、TBT 和响应时间，以及预填充和解码吞吐量，同时保持准确性。我们已公开源代码。

> Long-sequence generative large-language model (LLM) applications have become increasingly popular. In this paper, through trace-based experiments, we found that the existing method for long sequences results in a high Time-To-First-Token (TTFT) due to sequential chunk processing, long Time-Between-Tokens (TBT) from batching long-sequence prefills and decodes, and low throughput due to constrained key-value cache (KVC) for long sequences. To address these issues, we propose two Sequence-Parallelism (SP) architectures for both tensor parallelism (TP) and non-TP. However, SP introduces two challenges: 1) network communication and computation become performance bottlenecks; 2) the latter two issues above are mitigated but not resolved, and SP's resultant KV value distribution across GPUs still requires communication for decode, increasing TBT. Hence, we propose a Communication-efficient Sparse Attention (CSA) and communication-computation-communication three-phase pipelining. We also propose SP-based decode that processes decode separately from prefill, distributes KV values of a request across different GPUs, and novelly moves Query (Q) values instead of KV values to reduce communication overhead. These methods constitute a communication-efficient Sequence-Parallelism based LLM Serving System (SPS2). Our trace-driven evaluation demonstrates that SPS2 improves the average TTFT, TBT, and response time by up to 7.5x, 1.92x, and 9.8x and improves the prefill and decode throughput by 8.2x and 5.2x while maintaining the accuracy compared to Sarathi-Serve. We distributed our source code.

[Arxiv](https://arxiv.org/abs/2409.15104)