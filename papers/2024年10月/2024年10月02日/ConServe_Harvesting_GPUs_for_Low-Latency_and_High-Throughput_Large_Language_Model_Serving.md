# ConServe：高效利用 GPU，实现大型语言模型服务的低延迟与高吞吐量

发布时间：2024年10月02日

`LLM应用` `云计算` `人工智能`

> ConServe: Harvesting GPUs for Low-Latency and High-Throughput Large Language Model Serving

# 摘要

> 许多应用借助大型语言模型（LLM）处理复杂任务，如聊天机器人，要求低延迟和高吞吐量。然而，严格的延迟要求和高负载波动使得服务系统难以实现高 GPU 利用率。当前系统通常为在线和离线推理任务分别设置集群，并专用于在线推理，以避免干扰，但这导致 GPU 资源在低负载时闲置。本文提出利用闲置 GPU 资源进行离线 LLM 推理任务，如文档摘要和基准测试。这些任务通常对延迟要求宽松，适合利用闲置资源。为此，我们构建了 ConServe 系统，包含执行引擎、增量检查点机制和自适应调度器，确保在线任务不受影响的同时高效利用 GPU。评估显示，ConServe 在同时处理在线和离线任务时，不仅实现了强大的性能隔离，还显著提高了 GPU 利用率。在 Llama-2-7B 等模型上，ConServe 的吞吐量比最先进的在线服务系统高出 2.35 倍，服务延迟降低了 84 倍。

> Many applications are leveraging large language models (LLMs) for complex tasks, and they generally demand low inference latency and high serving throughput for interactive online jobs such as chatbots. However, the tight latency requirement and high load variance of applications pose challenges to serving systems in achieving high GPU utilization. Due to the high costs of scheduling and preemption, today's systems generally use separate clusters to serve online and offline inference tasks, and dedicate GPUs for online inferences to avoid interference. This approach leads to underutilized GPUs because one must reserve enough GPU resources for the peak expected load, even if the average load is low.
  This paper proposes to harvest stranded GPU resources for offline LLM inference tasks such as document summarization and LLM benchmarking. Unlike online inferences, these tasks usually run in a batch-processing manner with loose latency requirements, making them a good fit for stranded resources that are only available shortly. To enable safe and efficient GPU harvesting without interfering with online tasks, we built ConServe, an LLM serving system that contains (1) an execution engine that preempts running offline tasks upon the arrival of online tasks, (2) an incremental checkpointing mechanism that minimizes the amount of recomputation required by preemptions, and (3) a scheduler that adaptively batches offline tasks for higher GPU utilization. Our evaluation demonstrates that ConServe achieves strong performance isolation when co-serving online and offline tasks but at a much higher GPU utilization. When colocating practical online and offline workloads on popular models such as Llama-2-7B, ConServe achieves 2.35$\times$ higher throughput than state-of-the-art online serving systems and reduces serving latency by 84$\times$ compared to existing co-serving systems.

[Arxiv](https://arxiv.org/abs/2410.01228)