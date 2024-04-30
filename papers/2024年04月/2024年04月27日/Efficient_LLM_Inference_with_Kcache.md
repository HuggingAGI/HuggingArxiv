# Kcache 助力大型语言模型推理，实现高效能。

发布时间：2024年04月27日

`分类：LLM应用` `人工智能` `内存优化`

> Efficient LLM Inference with Kcache

# 摘要

> 大型语言模型（LLMs）极大地推动了人工智能应用的发展，尤其是在长文本的理解和生成方面。KV缓存技术因其高效生成序列的能力而在业界广受青睐，但它也带来了较大的内存开销。我们发现，KV缓存并非不可或缺，并创新性地提出了KCache技术，以解决LLMs在推理过程中的内存瓶颈。KCache无需训练即可直接用于推理，我们的测试结果表明，它能够将主流LLMs的吞吐量提升40%，同时保持了准确性。

> Large Language Models(LLMs) have had a profound impact on AI applications, particularly in the domains of long-text comprehension and generation. KV Cache technology is one of the most widely used techniques in the industry. It ensures efficient sequence generation by caching previously computed KV states. However, it also introduces significant memory overhead. We discovered that KV Cache is not necessary and proposed a novel KCache technique to alleviate the memory bottleneck issue during the LLMs inference process. KCache can be used directly for inference without any training process, Our evaluations show that KCache improves the throughput of popular LLMs by 40% with the baseline, while keeping accuracy.

[Arxiv](https://arxiv.org/abs/2404.18057)