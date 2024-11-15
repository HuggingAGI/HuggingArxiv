# 压缩注意力：加快长上下文长度的大型语言模型的推理速度

发布时间：2024年11月14日

`LLM应用` `模型优化`

> Squeezed Attention: Accelerating Long Context Length LLM Inference

# 摘要

> 新兴的大型语言模型（LLM）应用需要长输入提示来完成诸如文档分析、代码生成之类的复杂下游任务。对于这些长上下文长度的应用，输入提示的长度在推理效率上是个大难题，因为推理成本会随序列长度线性增长。不过，在很多这类应用中，提示里的大部分上下文在不同用户输入中是固定的，这就提供了进行离线优化的契机，能在收到用户输入时快速处理。在本研究中，我们提出压缩注意力机制来加速大部分输入提示固定的 LLM 应用。首先，我们离线运用 K 均值聚类，依据语义相似性对固定上下文的键分组，并用单个质心值代表每个簇。在推理时，我们把用户输入的查询令牌和质心作比较，预测固定上下文中哪些键在语义上相关且推理时需要加载。接着，仅用来自固定上下文的这些重要键计算精确注意力，从而降低带宽和计算成本。我们还拓展了方法，使用分层质心查找来识别重要键，能将注意力的复杂度相对于上下文长度从线性降至对数。我们为质心比较和带有重要键的稀疏 FlashAttention 实现了优化的 Triton 内核，在长上下文推理的预填充和生成阶段实现了 4 倍以上的加速。此外，我们在包括 LongBench 在内的各种长上下文基准上对我们的方法进行了广泛评估，在不损失准确性的情况下，实现了 KV 缓存预算减少 3 倍，对于各种模型，在准确性差距小于 0.5 点时最多减少 8 倍。

> Emerging Large Language Model (LLM) applications require long input prompts to perform complex downstream tasks like document analysis and code generation. For these long context length applications, the length of the input prompt poses a significant challenge in terms of inference efficiency since the inference costs increase linearly with sequence length. However, for many of these applications, much of the context in the prompt is fixed across different user inputs, thereby providing the opportunity to perform offline optimizations to process user inputs quickly, as they are received. In this work, we propose Squeezed Attention as a mechanism to accelerate LLM applications where a large portion of the input prompt is fixed. We first leverage K-means clustering offline to group the keys for the fixed context based on semantic similarity and represent each cluster with a single centroid value. During inference, we compare query tokens from the user input with the centroids to predict which of the keys from the fixed context are semantically relevant and need to be loaded during inference. We then compute exact attention using only these important keys from the fixed context, thereby reducing bandwidth and computational costs. We also extend our method to use a hierarchical centroid lookup to identify important keys, which can reduce the complexity of attention from linear to logarithmic with respect to the context length. We implement optimized Triton kernels for centroid comparison and sparse FlashAttention with important keys, achieving more than 4x speedups during both the prefill and generation phases for long-context inference. Furthermore, we have extensively evaluated our method on various long-context benchmarks including LongBench, where it achieves a 3x reduction in KV cache budget without accuracy loss and up to an 8x reduction with <0.5 point accuracy gap for various models.

[Arxiv](https://arxiv.org/abs/2411.09688)