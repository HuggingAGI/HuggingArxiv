# MuxServe 通过灵活的多路复用技术，为多个大型语言模型（LLM）提供高效服务。

发布时间：2024年04月02日

`LLM应用` `聊天系统`

> MuxServe: Flexible Multiplexing for Efficient Multiple LLM Serving

# 摘要

> 大型语言模型（LLMs）展现出了非凡的性能，众多机构正争先恐后地将各种规模的LLMs作为聊天、编程和搜索等应用场景的服务终端。然而，面对LLMs的流行度差异，现有技术在高效服务多个LLMs方面面临着不小的挑战。本文提出了MuxServe，一个创新的时空多路复用系统，旨在提升多个LLMs的服务效率。核心思想是根据LLMs的流行度进行合理共置，实现内存资源的有效复用，并通过预填充和解码阶段的特性，灵活地将它们分离并共置，以达到计算资源的高效复用。MuxServe系统正式定义了复用问题，并提出了一种创新的放置算法和自适应批量调度策略，旨在寻找最优的共置方案，最大化资源利用率。该系统还设计了一个统一的资源管理器，以支持灵活而高效的多路复用。评估结果显示，MuxServe能够提升高达1.8倍的吞吐量，或在保持99%的服务水平目标（SLO）的同时处理多达2.9倍的请求。

> Large language models (LLMs) have demon- strated remarkable performance, and organiza- tions are racing to serve LLMs of varying sizes as endpoints for use-cases like chat, programming and search. However, efficiently serving multiple LLMs poses significant challenges for existing approaches due to varying popularity of LLMs. In the paper, we present MuxServe, a flexible spatial-temporal multiplexing system for efficient multiple LLM serving. The key insight behind is to colocate LLMs considering their popularity to multiplex memory resources, and leverage the characteristics of prefill and decoding phases to separate and flexibly colocate them to multiplex computation resources. MuxServe formally for- mulates the multiplexing problem, and proposes a novel placement algorithm and adaptive batch scheduling strategy to identify optimal coloca- tions and maximize utilization. MuxServe de- signs a unified resource manager to enable flexi- ble and efficient multiplexing. Evaluation results show that MuxServe can achieves up to $1.8\times$ higher throughput or processes $2.9\times$ more requests within $99\%$ SLO attainment.

[Arxiv](https://arxiv.org/abs/2404.02015)