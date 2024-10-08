# 借助 HCache，LLM 服务中的状态恢复速度大幅提升

发布时间：2024年10月07日

`LLM应用` `云计算` `人工智能`

> Fast State Restoration in LLM Serving with HCache

# 摘要

> 随着 LLM 应用的复杂性增加，如多轮对话和 RAG，上下文状态（KV 缓存）可在用户请求间重复使用。然而，GPU 内存有限，只能缓存少量上下文。现有系统通常通过重新计算或卸载到主机存储来恢复 KV 缓存，这带来大量计算或 I/O 开销。我们提出 HCache，一种从中间激活恢复 LLM 状态的新方法，以低开销利用资源。HCache 结合了无气泡恢复调度器和基于块的存储管理器，优化了计算与 I/O 的平衡，并解决了布局不匹配问题。实测结果显示，HCache 在减少 TTFT 和存储空间方面表现优异，与 KV 卸载相比，TTFT 减少 1.93 倍，存储空间减少 1.92-2.40 倍；与令牌重新计算相比，TTFT 减少 5.73 倍。

> The growing complexity of LLM usage today, e.g., multi-round conversation and retrieval-augmented generation (RAG), makes contextual states (i.e., KV cache) reusable across user requests. Given the capacity constraints of GPU memory, only a limited number of contexts can be cached on GPU for reusing. Existing inference systems typically evict part of the KV cache and restore it by recomputing it from the original tokens or offloading it to host storage for later retrieval, both of which introduce substantial computational or I/O overheads. We propose HCache, a novel LLM state restoration method. Its key idea is to restore LLM states from intermediate activations and thus utilize computational and I/O resources with low overhead. We enhance HCache with two techniques, including i) a bubble-free restoration scheduler that integrates resource-complementary methods to optimize the balance between computation and IO tasks; and ii) a chunk-based storage manager to address the layout mismatch issue (i.e., layer-before-token saving versus token-before-layer restoration). Our evaluations, conducted using real-world tasks, show that HCache reduces the TTFT by up to 1.93X compared to KV offload while consuming 1.92-2.40X less storage space; compared to token recomputation, HCache achieves up to 5.73X reduction in TTFT.

[Arxiv](https://arxiv.org/abs/2410.05004)