# AcceLLM：使用冗余来加速大型语言模型（LLM）推理，以实现负载均衡和数据局部性。

发布时间：2024年11月08日

`LLM应用` `云计算` `人工智能`

> AcceLLM: Accelerating LLM Inference using Redundancy for Load Balancing and Data Locality

# 摘要

> 大型语言模型（LLM）在大规模系统上的推理预计将主导未来的云基础设施。在具有众多人工智能加速器的云环境中进行高效的 LLM 推理具有挑战性，需要进行大量优化以实现最佳性能。当前的系统通过批量预填充和解码来提高吞吐量，但会遇到延迟问题，而其他系统将这些阶段分解，导致资源利用不足。我们提出了 AcceLLM，这是一种受缓存数据管理启发的解决延迟和负载平衡的新方法。它策略性地利用冗余数据，通过负载平衡和优化硬件使用来增强推理。在 Nvidia H100 GPU 和华为 Ascend 910B2 上的模拟评估表明，AcceLLM 在延迟和效率方面比最先进的系统高出多达 30％，能够有效地处理各种工作负载。

> Large Language Model (LLM) inference on large-scale systems is expected to dominate future cloud infrastructures. Efficient LLM inference in cloud environments with numerous AI accelerators is challenging, necessitating extensive optimizations for optimal performance. Current systems batch prefill and decoding to boost throughput but encounter latency issues, while others disaggregate these phases, leading to resource underutilization. We propose AcceLLM, a novel method addressing latency and load balancing, inspired by the cache data management. It strategically utilizes redundant data to enhance inference via load balancing and optimal hardware use. Simulated evaluations on Nvidia H100 GPU and Huawei Ascend 910B2 show AcceLLM surpasses state-of-the-art systems up to 30% in latency and efficiency, handling diverse workloads effectively.

[Arxiv](https://arxiv.org/abs/2411.05555)