# ShadowKV：为高吞吐量长上下文 LLM 推理服务的影子中的 KV 缓存

发布时间：2024年10月28日

`LLM应用` `人工智能`

> ShadowKV: KV Cache in Shadows for High-Throughput Long-Context LLM Inference

# 摘要

> 随着长上下文大型语言模型（LLMs）的广泛应用，对高效支持高吞吐量推理的需求愈发迫切。然而，随着序列长度的增长，键值（KV）缓存不断扩展，内存占用持续增加，且每个令牌生成时都要访问它，这使得服务长上下文LLMs时的吞吐量较低。尽管已提出多种动态稀疏注意力方法来在保证生成质量的同时加快推理速度，但它们要么难以充分降低GPU内存消耗，要么因将KV缓存卸载到CPU而带来显著的解码延迟。我们推出了ShadowKV，这是一个高吞吐量的长上下文LLM推理系统，它存储低秩键缓存并卸载值缓存，以降低更大批量和更长序列的内存占用。为最大程度减少解码延迟，ShadowKV采用了精准的KV选择策略，能够实时重建最小稀疏KV对。通过在RULER、LongBench、Needle In A Haystack等众多基准测试以及Llama-3.1-8B、Llama-3-8B-1M、GLM-4-9B-1M、Yi-9B-200K、Phi-3-Mini-128K和Qwen2-7B-128K等模型上对ShadowKV进行评估，我们表明它在A100 GPU上能够支持高达6倍的更大批量，将吞吐量提升多达3.04倍，且不损失准确性，甚至超越了在假设GPU内存无限情况下的无限批量性能。代码可在https://github.com/bytedance/ShadowKV获取。

> With the widespread deployment of long-context large language models (LLMs), there has been a growing demand for efficient support of high-throughput inference. However, as the key-value (KV) cache expands with the sequence length, the increasing memory footprint and the need to access it for each token generation both result in low throughput when serving long-context LLMs. While various dynamic sparse attention methods have been proposed to speed up inference while maintaining generation quality, they either fail to sufficiently reduce GPU memory consumption or introduce significant decoding latency by offloading the KV cache to the CPU. We present ShadowKV, a high-throughput long-context LLM inference system that stores the low-rank key cache and offloads the value cache to reduce the memory footprint for larger batch sizes and longer sequences. To minimize decoding latency, ShadowKV employs an accurate KV selection strategy that reconstructs minimal sparse KV pairs on-the-fly. By evaluating ShadowKV on a broad range of benchmarks, including RULER, LongBench, and Needle In A Haystack, and models like Llama-3.1-8B, Llama-3-8B-1M, GLM-4-9B-1M, Yi-9B-200K, Phi-3-Mini-128K, and Qwen2-7B-128K, we demonstrate that it can support up to 6$\times$ larger batch sizes and boost throughput by up to 3.04$\times$ on an A100 GPU without sacrificing accuracy, even surpassing the performance achievable with infinite batch size under the assumption of infinite GPU memory. The code is available at https://github.com/bytedance/ShadowKV.

[Arxiv](https://arxiv.org/abs/2410.21465)