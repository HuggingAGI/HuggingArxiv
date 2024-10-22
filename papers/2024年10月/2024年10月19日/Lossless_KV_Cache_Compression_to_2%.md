# 无损 KV 缓存压缩率高达 98%

发布时间：2024年10月19日

`LLM理论` `数据处理` `人工智能`

> Lossless KV Cache Compression to 2%

# 摘要

> 大型语言模型在数据处理领域大放异彩，尤其在处理复杂上下文推理方面表现卓越。为了提升推理速度，KV 缓存内存不可或缺。然而，随着需求的增长，高效实现 KV 缓存变得愈发困难。为此，我们推出了跨层潜在注意力 (CLLA) 架构，旨在将 KV 缓存压缩至原大小的 2% 以下，同时保持性能。CLLA 集成了多种压缩技术，包括注意力头和维度的减少、层共享及量化方法。实验证明，CLLA 在多数任务中实现无损性能，极大地推动了 KV 缓存压缩技术的发展。

> Large language models have revolutionized data processing in numerous domains, with their ability to handle extended context reasoning receiving notable recognition. To speed up inference, maintaining a key-value (KV) cache memory is essential. Nonetheless, the growing demands for KV cache memory create significant hurdles for efficient implementation. This work introduces a novel architecture, Cross-Layer Latent Attention (CLLA), aimed at compressing the KV cache to less than 2% of its original size while maintaining comparable performance levels. CLLA integrates multiple aspects of KV cache compression, including attention head/dimension reduction, layer sharing, and quantization techniques, into a cohesive framework. Our extensive experiments demonstrate that CLLA achieves lossless performance on most tasks while utilizing minimal KV cache, marking a significant advancement in practical KV cache compression.

[Arxiv](https://arxiv.org/abs/2410.15252)