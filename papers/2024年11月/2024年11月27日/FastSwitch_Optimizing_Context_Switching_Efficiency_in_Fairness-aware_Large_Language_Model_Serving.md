# FastSwitch：优化公平感知的大型语言模型服务中的上下文切换效率

发布时间：2024年11月27日

`LLM应用` `语言模型` `服务系统`

> FastSwitch: Optimizing Context Switching Efficiency in Fairness-aware Large Language Model Serving

# 摘要

> 在大型语言模型（LLMs）服务系统中，要同时为众多用户和请求提供服务，就需要具备良好的公平性。如此一来，在相同成本下，系统能够满足更多用户的服务级别目标（SLOs），像首次令牌时间（TTFT）和令牌间隔时间（TBT）等，而不是让少数用户享受到远超 SLOs 的性能。为达更优公平性，基于抢占的调度策略会动态调整每个请求的优先级，以在运行期间维持平衡。然而，现有的系统通常过度侧重吞吐量，忽视了因抢占引发的上下文切换所产生的开销，而这对于通过优先级调整来保障公平性至关重要。在本研究中，我们明确了造成这种开销的三个主要挑战：1. I/O 利用率欠佳；2. GPU 闲置；3. 多轮对话时不必要的 I/O 传输。我们的关键发现是，现有系统中基于块的 KV 缓存内存策略，虽实现了近乎零的内存浪费，却导致了 KV 缓存内存的不连续和粒度不足。为此，我们推出了 FastSwitch，这是一个具有公平感知的服务系统，它不仅与现有的 KV 缓存内存分配策略相符，还能降低上下文切换的开销。我们的评估显示，在不同尾部 TTFT 和 TBT 方面，FastSwitch 比最先进的 LLM 服务系统 vLLM 快 1.4 至 11.2 倍。

> Serving numerous users and requests concurrently requires good fairness in Large Language Models (LLMs) serving system. This ensures that, at the same cost, the system can meet the Service Level Objectives (SLOs) of more users , such as time to first token (TTFT) and time between tokens (TBT), rather than allowing a few users to experience performance far exceeding the SLOs. To achieve better fairness, the preemption-based scheduling policy dynamically adjusts the priority of each request to maintain balance during runtime. However, existing systems tend to overly prioritize throughput, overlooking the overhead caused by preemption-induced context switching, which is crucial for maintaining fairness through priority adjustments. In this work, we identify three main challenges that result in this overhead. 1) Inadequate I/O utilization. 2) GPU idleness. 3) Unnecessary I/O transmission during multi-turn conversations. Our key insight is that the block-based KV cache memory policy in existing systems, while achieving near-zero memory waste, leads to discontinuity and insufficient granularity in the KV cache memory. To respond, we introduce FastSwitch, a fairness-aware serving system that not only aligns with existing KV cache memory allocation policy but also mitigates context switching overhead. Our evaluation shows that FastSwitch outperforms the state-of-the-art LLM serving system vLLM with speedups of 1.4-11.2x across different tail TTFT and TBT.

[Arxiv](https://arxiv.org/abs/2411.18424)