# AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。

发布时间：2024年03月23日

`LLM应用` `多轮对话` `缓存系统`

> AttentionStore: Cost-effective Attention Reuse across Multi-turn Conversations in Large Language Model Serving

# 摘要

> 大型语言模型（LLMs）的核心能力之一是与人类进行多轮对话。但目前执行此类对话的LLM服务引擎效率不高，因为它们需要不断重新计算历史对话标记的关键值（KV）缓存，造成高昂的服务成本。为此，我们提出了AttentionStore，这一新注意力机制能够实现多轮对话间的KV缓存重用，大幅降低了重复计算的负担。AttentionStore建立了一个分层的KV缓存系统，巧妙利用高性价比的存储介质保存所有请求的缓存。通过层级预加载和异步保存技术，它还能在GPU计算期间并行处理KV缓存访问，进一步提升效率。此外，AttentionStore通过调度器感知的策略，智能地安排KV缓存的层级位置，确保最快速的访问。为了避免上下文窗口溢出导致缓存失效，它还创新性地解耦了位置编码，并有效截断缓存，保持其有效性。实验证明，AttentionStore能显著提升效率，将首个标记生成时间缩短至原来的12%，多轮对话的提示填充速率提升8.2倍，整体推理成本降低56%。在处理长序列时，其效果更为显著，首个标记生成时间缩短高达95%，提示填充速率飙升22倍。

> Interacting with humans through multi-turn conversations is a fundamental feature of large language models (LLMs). However, existing LLM serving engines for executing multi-turn conversations are inefficient due to the need to repeatedly compute the key-value (KV) caches of historical tokens, incurring high serving costs. To address the problem, this paper proposes AttentionStore, a new attention mechanism that enables the reuse of KV caches (i.e., attention reuse) across multi-turn conversations, significantly reducing the repetitive computation overheads. AttentionStore maintains a hierarchical KV caching system that leverages cost-effective memory/storage mediums to save KV caches for all requests. To reduce KV cache access overheads from slow mediums, AttentionStore employs layer-wise pre-loading and asynchronous saving schemes to overlap the KV cache access with the GPU computation. To ensure that the KV caches to be accessed are placed in the fastest hierarchy, AttentionStore employs scheduler-aware fetching and eviction schemes to consciously place the KV caches in different layers based on the hints from the inference job scheduler. To avoid the invalidation of the saved KV caches incurred by context window overflow, AttentionStore enables the saved KV caches to remain valid via decoupling the positional encoding and effectively truncating the KV caches. Extensive experimental results demonstrate that AttentionStore significantly decreases the time to the first token (TTFT) by up to 88%, improves the prompt prefilling throughput by 8.2$\times$ for multi-turn conversations, and reduces the end-to-end inference cost by up to 56%. For long sequence inference, AttentionStore reduces the TTFT by up to 95% and improves the prompt prefilling throughput by 22$\times$.

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x1.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x2.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x3.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x4.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x5.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x6.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x7.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x8.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x9.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x10.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x11.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x12.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x13.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x14.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x15.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x16.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x17.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x18.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x19.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x20.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x21.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x22.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x23.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x24.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x25.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x26.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x27.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x28.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x29.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x30.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x31.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x32.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x33.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x34.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x35.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x36.png)

![AttentionStore 通过在大型语言模型的多轮对话中实现注意力机制的高效重用，降低了成本。](../../../paper_images/2403.19708/x37.png)

[Arxiv](https://arxiv.org/abs/2403.19708)