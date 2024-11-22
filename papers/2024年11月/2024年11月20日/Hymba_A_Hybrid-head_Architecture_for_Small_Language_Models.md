# Hymba：小型语言模型的混合头式架构

发布时间：2024年11月20日

`LLM应用` `模型架构`

> Hymba: A Hybrid-head Architecture for Small Language Models

# 摘要

> 摘要：我们推出了 Hymba 系列小型语言模型，其具备混合头并行架构，融合了 Transformer 注意力机制与状态空间模型（SSMs），以提升效率。注意力头能实现高分辨率回忆，SSM 头可有效进行上下文总结。另外，我们引入了可学习的元标记，置于提示之前，用于存储关键信息，减轻与注意力机制相关的“强制关注”负担。该模型还通过融入跨层键值（KV）共享和部分滑动窗口注意力得以进一步优化，实现了紧凑的缓存大小。在开发期间，我们开展了一项对照研究，在相同设定下对比了各种架构，发现我们所提出的架构优势显著。尤为值得一提的是，Hymba 在小型 LMs 领域取得了顶尖成果：我们的 Hymba-1.5B-Base 模型在性能上超越了所有小于 2B 的公共模型，甚至比 Llama-3.2-3B 的平均准确率高出 1.32%，缓存大小缩减 11.67 倍，吞吐量提升 3.49 倍。

> 
Abstract:We propose Hymba, a family of small language models featuring a hybrid-head parallel architecture that integrates transformer attention mechanisms with state space models (SSMs) for enhanced efficiency. Attention heads provide high-resolution recall, while SSM heads enable efficient context summarization. Additionally, we introduce learnable meta tokens that are prepended to prompts, storing critical information and alleviating the "forced-to-attend" burden associated with attention mechanisms. This model is further optimized by incorporating cross-layer key-value (KV) sharing and partial sliding window attention, resulting in a compact cache size. During development, we conducted a controlled study comparing various architectures under identical settings and observed significant advantages of our proposed architecture. Notably, Hymba achieves state-of-the-art results for small LMs: Our Hymba-1.5B-Base model surpasses all sub-2B public models in performance and even outperforms Llama-3.2-3B with 1.32% higher average accuracy, an 11.67x cache size reduction, and 3.49x throughput.
    

[Arxiv](https://arxiv.org/pdf/2411.13676)