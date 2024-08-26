# NanoFlow：致力于提升大型语言模型的服务吞吐量至最优水平

发布时间：2024年08月22日

`LLM应用` `信息技术` `高性能计算`

> NanoFlow: Towards Optimal Large Language Model Serving Throughput

# 摘要

> 随着大型语言模型 (LLM) 的广泛应用，全球规模的部署系统需求激增，数万台 GPU 持续服务数亿用户。吞吐量（在合理延迟下）成为衡量系统性能的关键指标。为提升吞吐量，虽已探索多种设备间并行方法，但现有技术未充分利用单设备内资源，导致性能受限。我们提出 NanoFlow，一种创新部署框架，通过操作协同调度，实现单设备内计算、内存和网络资源的重叠使用。NanoFlow 引入两项关键创新：首先，在操作粒度上将请求拆分为纳米批次，打破 LLM 推理中的顺序依赖，实现资源重叠；其次，采用操作级管道与执行单元调度，将设备功能单元分区，同时执行不同操作。NanoFlow 通过参数搜索算法自动配置管道，便于移植至不同模型。我们在 NVIDIA GPU 上实现 NanoFlow，并在多个流行模型上评估端到端吞吐量。在实际工作负载下，NanoFlow 相比顶尖部署系统，吞吐量提升 1.91 倍，达到移植模型中 59% 至 72% 的最优性能。

> The increasing usage of Large Language Models (LLMs) has resulted in a surging demand for planet-scale serving systems, where tens of thousands of GPUs continuously serve hundreds of millions of users. Consequently, throughput (under reasonable latency constraints) has emerged as a key metric that determines serving systems' performance. To boost throughput, various methods of inter-device parallelism (e.g., data, tensor, pipeline) have been explored. However, existing methods do not consider overlapping the utilization of different resources within a single device, leading to underutilization and sub-optimal performance.
  We propose NanoFlow, a novel serving framework that exploits intra-device parallelism, which overlaps the usage of resources including compute, memory, and network within a single device through operation co-scheduling. To exploit intra-device parallelism, NanoFlow introduces two key innovations: First, NanoFlow splits requests into nano-batches at the granularity of operations, which breaks the dependency of sequential operations in LLM inference and enables overlapping; then, to get benefit from overlapping, NanoFlow uses an operation-level pipeline with execution unit scheduling, which partitions the device's functional units and simultaneously executes different operations in each unit. NanoFlow automates the pipeline setup using a parameter search algorithm, which enables easily porting NanoFlow to different models. We implement NanoFlow on NVIDIA GPUs and evaluate end-to-end serving throughput on several popular models such as LLaMA-2-70B, Mixtral 8x7B, LLaMA-3-8B, etc.. With practical workloads, NanoFlow provides 1.91x throughput boost compared to state-of-the-art serving systems achieving 59% to 72% of optimal throughput across ported models.

[Arxiv](https://arxiv.org/abs/2408.12757)