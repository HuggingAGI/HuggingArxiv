# 少量的上下文也能走很远：通过部分上下文实现高效的长上下文训练和推理

发布时间：2024年10月02日

`LLM理论` `人工智能` `云计算`

> A Little Goes a Long Way: Efficient Long Context Training and Inference with Partial Contexts

# 摘要

> 训练和部署长上下文 LLM 会产生大量开销。为此，通常需要两个步骤：首先通过长上下文数据训练扩展模型上下文长度，然后进行架构调整以减少服务时的 KV 缓存开销。本文提出，将长度扩展与 GPU 友好的 KV 缓存优化架构结合，不仅能减少训练开销，还能提升长上下文性能。基于此，我们提出了 LongGen，在长度扩展过程中将预训练 LLM 微调为高效架构。LongGen 的三大核心见解包括：(1) 稀疏注意力模式（如窗口注意力、注意力下沉和块状稀疏注意力）因其 GPU 友好的内存访问模式，非常适合构建高效长上下文模型；(2) 模型需直接访问所有标记，混合架构（1/3 全注意力层和 2/3 高效层）在效率和性能间取得平衡；(3) 轻量级训练足以将上下文长度从 4K 扩展至 128K。我们在 Llama-2 7B 和 70B 上验证了 LongGen 的有效性。训练时，LongGen 比全注意力基线快 1.55 倍，挂钟时间减少 36%；推理时，KV 缓存内存减少 62%，预填充和解码速度分别提升 1.67 倍和 1.41 倍。

> Training and serving long-context large language models (LLMs) incurs substantial overhead. To address this, two critical steps are often required: a pretrained LLM typically undergoes a separate stage for context length extension by training on long-context data, followed by architectural modifications to reduce the overhead of KV cache during serving. This paper argues that integrating length extension with a GPU-friendly KV cache reduction architecture not only reduces training overhead during length extension, but also achieves better long-context performance. This leads to our proposed LongGen, which finetunes a pretrained LLM into an efficient architecture during length extension. LongGen builds on three key insights: (1) Sparse attention patterns, such as window attention (attending to recent tokens), attention sink (initial ones), and blockwise sparse attention (strided token blocks) are well-suited for building efficient long-context models, primarily due to their GPU-friendly memory access patterns, enabling efficiency gains not just theoretically but in practice as well. (2) It is essential for the model to have direct access to all tokens. A hybrid architecture with 1/3 full attention layers and 2/3 efficient ones achieves a balanced trade-off between efficiency and long-context performance. (3) Lightweight training on 5B long-context data is sufficient to extend the hybrid model's context length from 4K to 128K.
  We evaluate LongGen on both Llama-2 7B and Llama-2 70B, demonstrating its effectiveness across different scales. During training with 128K-long contexts, LongGen achieves 1.55x training speedup and reduces wall-clock time by 36%, compared to a full-attention baseline. During inference, LongGen reduces KV cache memory by 62%, achieving 1.67x prefilling speedup and 1.41x decoding speedup.

[Arxiv](https://arxiv.org/abs/2410.01485)