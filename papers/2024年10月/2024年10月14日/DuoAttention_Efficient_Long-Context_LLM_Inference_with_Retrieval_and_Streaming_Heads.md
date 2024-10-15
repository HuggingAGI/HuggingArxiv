# DuoAttention：结合检索与流式处理，实现长上下文 LLM 推理的高效能

发布时间：2024年10月14日

`LLM理论` `人工智能` `云计算`

> DuoAttention: Efficient Long-Context LLM Inference with Retrieval and Streaming Heads

# 摘要

> 部署长上下文 LLM 虽必要，但面临计算与内存挑战。现有 KV 缓存剪枝方法或损害长上下文能力，或效率提升有限。本文发现，仅部分检索头需全注意力处理长上下文，而流头则无需。基于此，我们提出 DuoAttention 框架，仅对检索头应用全 KV 缓存，流头则用轻量级 KV 缓存，从而减少内存与延迟，且不损长上下文能力。DuoAttention 通过优化算法与合成数据精准识别检索头，显著降低内存与加速解码及预填充。结合量化，DuoAttention 使 Llama-3-8B 在单 A100 GPU 上以 330 万上下文长度解码。代码见 https://github.com/mit-han-lab/duo-attention。

> Deploying long-context large language models (LLMs) is essential but poses significant computational and memory challenges. Caching all Key and Value (KV) states across all attention heads consumes substantial memory. Existing KV cache pruning methods either damage the long-context capabilities of LLMs or offer only limited efficiency improvements. In this paper, we identify that only a fraction of attention heads, a.k.a, Retrieval Heads, are critical for processing long contexts and require full attention across all tokens. In contrast, all other heads, which primarily focus on recent tokens and attention sinks--referred to as Streaming Heads--do not require full attention. Based on this insight, we introduce DuoAttention, a framework that only applies a full KV cache to retrieval heads while using a light-weight, constant-length KV cache for streaming heads, which reduces both LLM's decoding and pre-filling memory and latency without compromising its long-context abilities. DuoAttention uses a lightweight, optimization-based algorithm with synthetic data to identify retrieval heads accurately. Our method significantly reduces long-context inference memory by up to 2.55x for MHA and 1.67x for GQA models while speeding up decoding by up to 2.18x and 1.50x and accelerating pre-filling by up to 1.73x and 1.63x for MHA and GQA models, respectively, with minimal accuracy loss compared to full attention. Notably, combined with quantization, DuoAttention enables Llama-3-8B decoding with 3.3 million context length on a single A100 GPU. Code is provided in https://github.com/mit-han-lab/duo-attention.

[Arxiv](https://arxiv.org/abs/2410.10819)