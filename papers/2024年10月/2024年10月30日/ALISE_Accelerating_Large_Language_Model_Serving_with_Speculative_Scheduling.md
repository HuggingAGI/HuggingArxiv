# ALISE：借助推测性调度加快大型语言模型服务

发布时间：2024年10月30日

`LLM应用` `人工智能` `推理服务`

> ALISE: Accelerating Large Language Model Serving with Speculative Scheduling

# 摘要

> 大型语言模型（LLMs）在当代通用人工智能（AGI）领域掀起了一场革命性的进步浪潮。以 ChatGPT 为例，基于 LLM 的应用要求推理服务具备极小的响应延迟和极大的吞吐量。但由于 LLM 执行的不可预测性，当前 LLM 服务系统所采用的先到先服务（FCFS）调度策略存在队头（HoL）阻塞问题，导致作业响应时间较长。
    本文提出了一个全新的高效 LLM 推理服务框架，名为 ALISE。ALISE 的核心设计模式在于借助一个新颖的推测调度器，通过预估每个作业的执行时间，并利用这些先验知识来确定恰当的作业优先级顺序，从而最大程度减少异构工作负载的潜在排队延迟。此外，为降低中间键值（KV）缓存的内存开销，我们采用了基于优先级的自适应内存管理协议和基于量化的压缩技术。评估显示，在 Alpaca 和 ShareGPT 数据集上相同的延迟限制条件下，与最先进的解决方案 vLLM 相比，ALISE 分别将推理服务的吞吐量提升了多达 1.8 倍和 2.1 倍。

> Large Language Models (LLMs) represent a revolutionary advancement in the contemporary landscape of artificial general intelligence (AGI). As exemplified by ChatGPT, LLM-based applications necessitate minimal response latency and maximal throughput for inference serving. However, due to the unpredictability of LLM execution, the first-come-first-serve (FCFS) scheduling policy employed by current LLM serving systems suffers from head-of-line (HoL) blocking issues and long job response times.
  In this paper, we propose a new efficient LLM inference serving framework, named ALISE. The key design paradigm of ALISE is to leverage a novel speculative scheduler by estimating the execution time for each job and exploiting such prior knowledge to assign appropriate job priority orders, thus minimizing potential queuing delays for heterogeneous workloads. Furthermore, to mitigate the memory overhead of the intermediate key-value (KV) cache, we employ a priority-based adaptive memory management protocol and quantization-based compression techniques. Evaluations demonstrate that in comparison to the state-of-the-art solution vLLM, ALISE improves the throughput of inference serving by up to 1.8x and 2.1x under the same latency constraint on the Alpaca and ShareGPT datasets, respectively.

[Arxiv](https://arxiv.org/abs/2410.23537)