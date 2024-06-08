# PyramidKV：利用金字塔信息汇聚实现动态KV缓存的高效压缩

发布时间：2024年06月04日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）内部基于注意力的信息流，并提出了一种新的KV缓存压缩方法PyramidKV。研究内容涉及LLMs的内部工作机制和优化技术，属于对LLM理论的深入研究。因此，它应该被归类为LLM理论。` `内存优化`

> PyramidKV: Dynamic KV Cache Compression based on Pyramidal Information Funneling

# 摘要

> 本研究探索了大型语言模型（LLMs）内部基于注意力的信息流是否通过显著模式进行长上下文处理的信息聚合。我们发现，LLMs通过金字塔信息汇聚机制聚合信息，注意力在低层广泛分散，逐渐在高层集中于关键令牌。基于此，我们开发了PyramidKV，一种创新的KV缓存压缩方法，它动态调整缓存大小，低层多、高层少。实验表明，PyramidKV在保留12%缓存时性能与全缓存模型相当，大幅节省内存。在内存效率优先的场景中，即使仅保留0.7%缓存，PyramidKV也能超越其他技术，提升TREC精度达20.5。

> In this study, we investigate whether attention-based information flow inside large language models (LLMs) is aggregated through noticeable patterns for long context processing. Our observations reveal that LLMs aggregate information through Pyramidal Information Funneling where attention is scattering widely in lower layers, progressively consolidating within specific contexts, and ultimately focusin on critical tokens (a.k.a massive activation or attention sink) in higher layers. Motivated by these insights, we developed PyramidKV, a novel and effective KV cache compression method. This approach dynamically adjusts the KV cache size across different layers, allocating more cache in lower layers and less in higher ones, diverging from traditional methods that maintain a uniform KV cache size. Our experimental evaluations, utilizing the LongBench benchmark, show that PyramidKV matches the performance of models with a full KV cache while retaining only 12% of the KV cache, thus significantly reducing memory usage. In scenarios emphasizing memory efficiency, where only 0.7% of the KV cache is maintained, PyramidKV surpasses other KV cache compression techniques achieving up to a 20.5 absolute accuracy improvement on TREC.

![PyramidKV：利用金字塔信息汇聚实现动态KV缓存的高效压缩](../../../paper_images/2406.02069/x1.png)

![PyramidKV：利用金字塔信息汇聚实现动态KV缓存的高效压缩](../../../paper_images/2406.02069/x2.png)

![PyramidKV：利用金字塔信息汇聚实现动态KV缓存的高效压缩](../../../paper_images/2406.02069/x3.png)

![PyramidKV：利用金字塔信息汇聚实现动态KV缓存的高效压缩](../../../paper_images/2406.02069/x4.png)

![PyramidKV：利用金字塔信息汇聚实现动态KV缓存的高效压缩](../../../paper_images/2406.02069/x5.png)

[Arxiv](https://arxiv.org/abs/2406.02069)