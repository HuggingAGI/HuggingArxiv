# InstInfer：通过存储内注意力卸载，实现高效且经济的长上下文 LLM 推理

发布时间：2024年09月08日

`LLM应用` `人工智能` `存储技术`

> InstInfer: In-Storage Attention Offloading for Cost-Effective Long-Context LLM Inference

# 摘要

> 大型语言模型（LLM）的普及标志着生成式 AI 的重大进步。然而，离线推理中不断增长的上下文长度和批量大小使得关键值（KV）缓存的内存需求激增，给 GPU VRAM 带来了沉重负担，尤其是在资源受限的环境中。虽然一些经济高效的方案通过利用主机内存或 SSD 来降低存储成本并提升吞吐量，但由于 PCIe 带宽有限，这些方案在密集的 KV 缓存访问中性能大打折扣。为此，我们推出了 InstInfer，这是一种创新的 LLM 推理系统，它将最关键的计算（如解码阶段的注意力）和数据（如 KV 缓存）卸载到计算存储驱动器（CSD），从而大幅减少 KV 传输开销。InstInfer 还设计了专用的闪存感知存储内注意力引擎，并结合 KV 缓存管理机制，充分利用 CSD 的高内部带宽，而非受限于 PCIe 带宽。此外，GPU 与 CSD 之间的优化 P2P 传输进一步降低了数据迁移开销。实验显示，对于使用 NVIDIA A6000 GPU 的 13B 模型，InstInfer 在长序列推理中的吞吐量比现有基于 SSD 的解决方案（如 FlexGen）提升了高达 11.1 倍。

> The widespread of Large Language Models (LLMs) marks a significant milestone in generative AI. Nevertheless, the increasing context length and batch size in offline LLM inference escalate the memory requirement of the key-value (KV) cache, which imposes a huge burden on the GPU VRAM, especially for resource-constraint scenarios (e.g., edge computing and personal devices). Several cost-effective solutions leverage host memory or SSDs to reduce storage costs for offline inference scenarios and improve the throughput. Nevertheless, they suffer from significant performance penalties imposed by intensive KV cache accesses due to limited PCIe bandwidth. To address these issues, we propose InstInfer, a novel LLM inference system that offloads the most performance-critical computation (i.e., attention in decoding phase) and data (i.e., KV cache) parts to Computational Storage Drives (CSDs), which minimize the enormous KV transfer overheads. InstInfer designs a dedicated flash-aware in-storage attention engine with KV cache management mechanisms to exploit the high internal bandwidths of CSDs instead of being limited by the PCIe bandwidth. The optimized P2P transmission between GPU and CSDs further reduces data migration overheads. Experimental results demonstrate that for a 13B model using an NVIDIA A6000 GPU, InstInfer improves throughput for long-sequence inference by up to 11.1$\times$, compared to existing SSD-based solutions such as FlexGen.

[Arxiv](https://arxiv.org/abs/2409.04992)