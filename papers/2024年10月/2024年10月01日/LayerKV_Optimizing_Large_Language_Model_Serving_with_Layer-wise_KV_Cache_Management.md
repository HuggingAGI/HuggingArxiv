# LayerKV：通过逐层 KV 缓存管理，优化大型语言模型的服务性能。

发布时间：2024年10月01日

`LLM理论` `云计算` `人工智能`

> LayerKV: Optimizing Large Language Model Serving with Layer-wise KV Cache Management

# 摘要

> 大型语言模型 (LLM) 的上下文窗口扩展虽然大幅提升了应用能力，但也带来了显著的低延迟挑战，尤其是在首次令牌时间 (TTFT) 方面。本文发现，TTFT 随上下文长度增加而急剧上升，主要源于 GPU 键值 (KV) 缓存分配需求与可用缓存块之间的冲突。为此，我们提出了 LayerKV，一种简单高效的插件方法，无需额外硬件即可显著降低 TTFT，同时保持输出性能，并兼容现有并行策略和调度技术。LayerKV 通过层级 KV 块分配、管理和卸载，结合 SLO 感知的调度器，优化系统内存和整体服务级别目标 (SLO)。在 7B 到 70B 参数的代表性模型上进行的全面评估显示，LayerKV 将 TTFT 延迟提升了 11 倍，SLO 违规率降低了 28.7%，大幅提升了用户体验。

> The expanding context windows in large language models (LLMs) have greatly enhanced their capabilities in various applications, but they also introduce significant challenges in maintaining low latency, particularly in Time to First Token (TTFT). This paper identifies that the sharp rise in TTFT as context length increases is predominantly driven by queuing delays, which are caused by the growing demands for GPU Key-Value (KV) cache allocation clashing with the limited availability of KV cache blocks. To address this issue, we propose LayerKV, a simple yet effective plug-in method that effectively reduces TTFT without requiring additional hardware or compromising output performance, while seamlessly integrating with existing parallelism strategies and scheduling techniques. Specifically, LayerKV introduces layer-wise KV block allocation, management, and offloading for fine-grained control over system memory, coupled with an SLO-aware scheduler to optimize overall Service Level Objectives (SLOs). Comprehensive evaluations on representative models, ranging from 7B to 70B parameters, across various GPU configurations, demonstrate that LayerKV improves TTFT latency up to 11x and reduces SLO violation rates by 28.7\%, significantly enhancing the user experience

[Arxiv](https://arxiv.org/abs/2410.00428)