# UELLM：为 LLM 推理服务提供了一种既统一又高效的方法。

发布时间：2024年09月23日

`LLM应用` `云计算` `人工智能`

> UELLM: A Unified and Efficient Approach for LLM Inference Serving

# 摘要

> 在 MLaaS 云环境中，LLM 的广泛使用需要高效管理大量查询。实时推理服务面临三大挑战：GPU 过多导致通信开销增加，GPU 不足引发内存错误，部署策略需优化以减少延迟。此外，推理查询的低效编排易导致 SLO 违规。为此，我们提出 UELLM 方法，包含资源分析、批处理调度和 LLM 部署三大组件，有效降低资源开销、推理延迟和 SLO 违规率。与 SOTA 技术相比，UELLM 显著提升性能，推理延迟降低 72.3% 至 90.3%，GPU 利用率提高 1.2 至 4.1 倍，吞吐量提升 1.92 至 4.98 倍，且不违反 SLO。

> In the context of Machine Learning as a Service (MLaaS) clouds, the extensive use of Large Language Models (LLMs) often requires efficient management of significant query loads. When providing real-time inference services, several challenges arise. Firstly, increasing the number of GPUs may lead to a decrease in inference speed due to heightened communication overhead, while an inadequate number of GPUs can lead to out-of-memory errors. Secondly, different deployment strategies need to be evaluated to guarantee optimal utilization and minimal inference latency. Lastly, inefficient orchestration of inference queries can easily lead to significant Service Level Objective (SLO) violations. Lastly, inefficient orchestration of inference queries can easily lead to significant Service Level Objective (SLO) violations. To address these challenges, we propose a Unified and Efficient approach for Large Language Model inference serving (UELLM), which consists of three main components: 1) resource profiler, 2) batch scheduler, and 3) LLM deployer. UELLM minimizes resource overhead, reduces inference latency, and lowers SLO violation rates. Compared with state-of-the-art (SOTA) techniques, UELLM reduces the inference latency by 72.3% to 90.3%, enhances GPU utilization by 1.2X to 4.1X, and increases throughput by 1.92X to 4.98X, it can also serve without violating the inference latency SLO.

[Arxiv](https://arxiv.org/abs/2409.14961)