# BlendServe：借助资源感知批处理来优化自回归大型模型的离线推理

发布时间：2024年11月25日

`其他` `批处理`

> BlendServe: Optimizing Offline Inference for Auto-regressive Large Models with Resource-aware Batching

# 摘要

> 离线批处理推理借助请求批处理的灵活性，实现了更高的吞吐量和更低的成本，在对延迟不敏感的应用中愈发流行。与此同时，模型能力和模态的最新进展，让请求在计算和内存需求上变得更加多样，为通过资源重叠提升吞吐量创造了独特契机。然而，旨在最大化资源重叠的请求调度可能与广泛应用的旨在最大化前缀共享（一种性能优化手段）的调度相冲突，致使推理吞吐量欠佳。我们推出了BlendServe系统，它通过资源感知前缀树，将资源重叠和前缀共享的优势相结合，从而实现离线批处理推理资源利用率的最大化。BlendServe利用离线批处理推理中宽松的延迟要求，对资源需求各异的请求进行重新排序和重叠，同时保证高前缀共享。我们在各类合成的多模态工作负载上对BlendServe进行了评估，结果表明，与广泛使用的行业标准vLLM和SGLang相比，它能将吞吐量提升高达1.44倍。

> Offline batch inference, which leverages the flexibility of request batching to achieve higher throughput and lower costs, is becoming more popular for latency-insensitive applications. Meanwhile, recent progress in model capability and modality makes requests more diverse in compute and memory demands, creating unique opportunities for throughput improvement by resource overlapping. However, a request schedule that maximizes resource overlapping can conflict with the schedule that maximizes prefix sharing, a widely-used performance optimization, causing sub-optimal inference throughput. We present BlendServe, a system that maximizes resource utilization of offline batch inference by combining the benefits of resource overlapping and prefix sharing using a resource-aware prefix tree. BlendServe exploits the relaxed latency requirements in offline batch inference to reorder and overlap requests with varied resource demands while ensuring high prefix sharing. We evaluate BlendServe on a variety of synthetic multi-modal workloads and show that it provides up to $1.44\times$ throughput boost compared to widely-used industry standards, vLLM and SGLang.

[Arxiv](https://arxiv.org/abs/2411.16102)