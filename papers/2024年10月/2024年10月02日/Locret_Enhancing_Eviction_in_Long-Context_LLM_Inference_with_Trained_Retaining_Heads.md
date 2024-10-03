# Locret：通过训练保留头，提升长上下文 LLM 推理中的驱逐效果

发布时间：2024年10月02日

`LLM理论` `人工智能` `云计算`

> Locret: Enhancing Eviction in Long-Context LLM Inference with Trained Retaining Heads

# 摘要

> 大型语言模型（LLM）在长上下文理解和处理任务上取得了显著进展。然而，将 LLM 的生成推理扩展到长上下文会带来巨大的计算和内存负担。现有的 KV 缓存压缩方法在长上下文下存在内存瓶颈，而静态缓存策略效率低下。为此，我们提出了 Locret 框架，通过引入保留头评估 KV 缓存单元的因果重要性，实现更精准的缓存管理。Locret 在少量数据上微调后，能够在推理时显著减少 GPU 内存使用。实验表明，Locret 在内存效率和生成质量上优于现有方法，如 InfLLM、量化等，且能与其他优化技术结合。Locret 首次实现了在单个 Nvidia 4090 GPU 上部署 Llama-3.1-8B 模型，进行 128K 长上下文推理，且几乎无需额外系统优化。

> Large language models (LLMs) have shown remarkable advances in supporting long-context comprehension and processing tasks. However, scaling the generation inference of LLMs to such long contexts incurs significant additional computation load, and demands a substantial GPU memory footprint to maintain the key-value (KV) cache of transformer-based LLMs. Existing KV cache compression methods, such as quantization, face memory bottlenecks as context length increases, while static-sized caches, such as eviction, suffer from inefficient policies. These limitations restrict deployment on consumer-grade devices like a single Nvidia 4090 GPU. To overcome this, we propose Locret, a framework for long-context LLM inference that introduces retaining heads to evaluate the causal importance of KV cache units, allowing for more accurate eviction within a fixed cache size. Locret is fine-tuned on top of the frozen backbone LLM using a minimal amount of data from standard long-context SFT datasets. During inference, we evict low-importance cache units along with a chunked prefill pattern, significantly reducing peak GPU memory usage. We conduct an extensive empirical study to evaluate Locret, where the experimental results show that Locret outperforms the recent competitive approaches, including InfLLM, Quantization, SirLLM, and MInference, in terms of memory efficiency and the quality of generated contents -- Locret achieves over a 20x and 8x KV cache compression ratio compared to the full KV cache for Phi-3-mini-128K and Llama-3.1-8B-instruct. Additionally, Locret can be combined with other methods, such as quantization and token merging. To our knowledge, Locret is the first framework capable of deploying Llama-3.1-8B or similar models on a single Nvidia 4090 GPU, enabling 128K long-context inference without compromising generation quality, and requiring little additional system optimizations.

[Arxiv](https://arxiv.org/abs/2410.01805)