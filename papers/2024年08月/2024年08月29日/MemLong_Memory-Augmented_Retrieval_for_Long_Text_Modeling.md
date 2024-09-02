# MemLong：长文本建模中的记忆增强检索技术

发布时间：2024年08月29日

`LLM应用` `人工智能`

> MemLong: Memory-Augmented Retrieval for Long Text Modeling

# 摘要

> 近期，大型语言模型（LLMs）在多领域取得了显著成就，但处理长文本仍是一大挑战。为此，我们推出了MemLong：一种通过外部检索增强长文本生成能力的内存增强检索方法。MemLong巧妙结合了非微分“ret-mem”模块与部分可训练的解码器模型，并引入了细粒度、可控的检索注意力机制，有效利用语义相关信息。在多项长文本生成基准测试中，MemLong表现卓越，更能在单个3090 GPU上将上下文长度从4k扩展至80k。代码已公开，详见https://github.com/Bui1dMySea/MemLong。

> Recent advancements in Large Language Models (LLMs) have yielded remarkable success across diverse fields. However, handling long contexts remains a significant challenge for LLMs due to the quadratic time and space complexity of attention mechanisms and the growing memory consumption of the key-value cache during generation. This work introduces MemLong: Memory-Augmented Retrieval for Long Text Generation, a method designed to enhance the capabilities of long-context language modeling by utilizing an external retriever for historical information retrieval. MemLong combines a non-differentiable ``ret-mem'' module with a partially trainable decoder-only language model and introduces a fine-grained, controllable retrieval attention mechanism that leverages semantic-level relevant chunks. Comprehensive evaluations on multiple long-context language modeling benchmarks demonstrate that MemLong consistently outperforms other state-of-the-art LLMs. More importantly, MemLong can extend the context length on a single 3090 GPU from 4k up to 80k. Our code is available at https://github.com/Bui1dMySea/MemLong

[Arxiv](https://arxiv.org/abs/2408.16967)