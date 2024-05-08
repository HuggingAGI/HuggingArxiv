# KV Cache 以每通道仅1位的精简方式，通过耦合量化技术，为大型语言模型的推理过程带来了前所未有的效率提升。

发布时间：2024年05月06日

`LLM理论

这篇论文探讨了大型语言模型（LLM）中的一个理论问题，即如何通过耦合量化（CQ）技术提高模型部署效率，特别是在处理大规模批量请求时减少KV缓存对GPU内存的消耗和推理速度的限制。论文提出了一种新的量化方法，并通过实验验证了其在保持模型性能方面的有效性。这属于对LLM内部机制和优化技术的理论研究，因此归类为LLM理论。` `模型优化`

> KV Cache is 1 Bit Per Channel: Efficient Large Language Model Inference with Coupled Quantization

# 摘要

> 为了提高大型语言模型的部署效率，批量处理请求是关键。但随着批量和模型规模的增大，KV缓存成为GPU内存的吞噬者和推理速度的瓶颈。量化技术虽能压缩KV缓存，但在极低比特下效果不佳。我们发现，键值嵌入的各个通道间存在紧密联系，联合熵的增长，其速度不及单个熵的总和。因此，我们提出了耦合量化（CQ），通过耦合多个通道，充分利用它们之间的相互依赖，以更高效的方式编码信息。实验证明，CQ在保持模型性能上超越了现有技术，甚至在1比特量化下也能保持模型质量。

> Efficient deployment of Large Language Models (LLMs) requires batching multiple requests together to improve throughput. As the batch size, context length, or model size increases, the size of the key and value (KV) cache can quickly become the main contributor to GPU memory usage and the bottleneck of inference latency. Quantization has emerged as an effective technique for KV cache compression, but existing methods still fail at very low bit widths. We observe that distinct channels of a key/value activation embedding are highly inter-dependent, and the joint entropy of multiple channels grows at a slower rate than the sum of their marginal entropies. Based on this insight, we propose Coupled Quantization (CQ), which couples multiple key/value channels together to exploit their inter-dependency and encode the activations in a more information-efficient manner. Extensive experiments reveal that CQ outperforms or is competitive with existing baselines in preserving model quality. Furthermore, we demonstrate that CQ can preserve model quality with KV cache quantized down to 1-bit.

![KV Cache 以每通道仅1位的精简方式，通过耦合量化技术，为大型语言模型的推理过程带来了前所未有的效率提升。](../../../paper_images/2405.03917/x1.png)

![KV Cache 以每通道仅1位的精简方式，通过耦合量化技术，为大型语言模型的推理过程带来了前所未有的效率提升。](../../../paper_images/2405.03917/x2.png)

![KV Cache 以每通道仅1位的精简方式，通过耦合量化技术，为大型语言模型的推理过程带来了前所未有的效率提升。](../../../paper_images/2405.03917/x3.png)

![KV Cache 以每通道仅1位的精简方式，通过耦合量化技术，为大型语言模型的推理过程带来了前所未有的效率提升。](../../../paper_images/2405.03917/x4.png)

![KV Cache 以每通道仅1位的精简方式，通过耦合量化技术，为大型语言模型的推理过程带来了前所未有的效率提升。](../../../paper_images/2405.03917/x5.png)

![KV Cache 以每通道仅1位的精简方式，通过耦合量化技术，为大型语言模型的推理过程带来了前所未有的效率提升。](../../../paper_images/2405.03917/x6.png)

![KV Cache 以每通道仅1位的精简方式，通过耦合量化技术，为大型语言模型的推理过程带来了前所未有的效率提升。](../../../paper_images/2405.03917/key_emb.png)

![KV Cache 以每通道仅1位的精简方式，通过耦合量化技术，为大型语言模型的推理过程带来了前所未有的效率提升。](../../../paper_images/2405.03917/value_emb.png)

[Arxiv](https://arxiv.org/abs/2405.03917)