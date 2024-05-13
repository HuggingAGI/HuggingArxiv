# SKVQ：大型语言模型的滑动窗口键值缓存量化技术，通过精妙的量化策略，优化了模型的缓存效率，为语言模型的性能提升开辟了新的道路。

发布时间：2024年05月09日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在处理长篇令牌序列时面临的内存消耗问题，并提出了一种名为SKVVQ的策略来解决键值（KV）缓存量化的问题。该研究专注于LLMs的理论层面，特别是在内存管理和量化技术方面的创新，以提高模型的效率和可部署性。因此，它属于LLM理论分类。` `机器学习`

> SKVQ: Sliding-window Key and Value Cache Quantization for Large Language Models

# 摘要

> 大型语言模型（LLMs）已能驾驭长篇令牌序列，让书籍理解和长篇小说创作等复杂任务成为现实。但随之而来的键值（KV）缓存需求却成了内存消耗的巨兽，成为部署的瓶颈。本文提出的SKVVQ策略，即滑动窗口KV缓存量化，巧妙解决了极低比特宽度KV缓存量化的难题。SKVVQ通过重新组织KV缓存通道，增强量化组内通道的相似性，并采用剪裁动态量化技术，确保了最新窗口令牌的高精度保存，从而守护了KV缓存中关键部分的准确性。实验证明，SKVVQ在保持准确性的同时，实现了高压缩比，超越了以往的量化方法，使得2比特键和1.5比特值的KV缓存量化成为可能，且几乎不损失准确性。借助SKVVQ，我们能在80GB内存的GPU上，以7倍的速度，处理7b模型的1M上下文长度。

> Large language models (LLMs) can now handle longer sequences of tokens, enabling complex tasks like book understanding and generating lengthy novels. However, the key-value (KV) cache required for LLMs consumes substantial memory as context length increasing, becoming the bottleneck for deployment. In this paper, we present a strategy called SKVQ, which stands for sliding-window KV cache quantization, to address the issue of extremely low bitwidth KV cache quantization. To achieve this, SKVQ rearranges the channels of the KV cache in order to improve the similarity of channels in quantization groups, and applies clipped dynamic quantization at the group level. Additionally, SKVQ ensures that the most recent window tokens in the KV cache are preserved with high precision. This helps maintain the accuracy of a small but important portion of the KV cache.SKVQ achieves high compression ratios while maintaining accuracy. Our evaluation on LLMs demonstrates that SKVQ surpasses previous quantization approaches, allowing for quantization of the KV cache to 2-bit keys and 1.5-bit values with minimal loss of accuracy. With SKVQ, it is possible to process context lengths of up to 1M on an 80GB memory GPU for a 7b model and up to 7 times faster decoding.

[Arxiv](https://arxiv.org/abs/2405.06219)