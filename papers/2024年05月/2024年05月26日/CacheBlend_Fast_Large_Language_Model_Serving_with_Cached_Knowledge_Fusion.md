# CacheBlend：融合缓存知识，加速大型语言模型服务

发布时间：2024年05月26日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）中预计算的KV缓存的有效重用问题，特别是在输入包含多个文本块时的应用。提出的CacheBlend方案旨在优化KV缓存的重复使用，以减少首次令牌时间（TTFT）和提升推理吞吐量，同时保持生成质量。这种研究直接应用于LLM的实际操作和性能优化，属于LLM应用的范畴。` `机器学习`

> CacheBlend: Fast Large Language Model Serving with Cached Knowledge Fusion

# 摘要

> 大型语言模型（LLMs）常通过整合多个文本片段来提供必要上下文。为了加速长LLM输入的预填充，可以预先计算文本的KV缓存，并在上下文重复使用时重新利用。但当重复的文本块并非输入前缀时，预计算的KV缓存因未考虑与前文的交叉注意力而无法直接使用，导致KV缓存重复使用的优势未能充分发挥。本研究聚焦于一个问题：如何在LLM输入包含多个文本块时，快速整合其预计算的KV缓存，以保持与完全预填充相同的生成质量？我们提出的CacheBlend方案，无论文本块是否为前缀，均能有效重用KV缓存，并通过选择性重新计算少数令牌的KV值来部分更新缓存。此过程中，重新计算的微小延迟可与KV缓存的检索并行处理，使得CacheBlend能在存储容量更大的慢速设备上存储KV缓存，而不会增加推理延迟。通过与三种不同大小的开源LLM及四种不同任务的流行基准数据集上的最先进KV缓存重复使用方案比较，我们发现CacheBlend显著减少了首次令牌时间（TTFT）2.2-3.3倍，提升了推理吞吐量2.8-5倍，同时保持了生成质量且未增加额外存储成本。

> Large language models (LLMs) often incorporate multiple text chunks in their inputs to provide the necessary contexts. To speed up the prefill of the long LLM inputs, one can pre-compute the KV cache of a text and re-use the KV cache when the context is reused as the prefix of another LLM input. However, the reused text chunks are not always the input prefix, and when they are not, their precomputed KV caches cannot be directly used since they ignore the text's cross-attention with the preceding text in the LLM input. Thus, the benefits of reusing KV caches remain largely unrealized.
  This paper tackles just one question: when an LLM input contains multiple text chunks, how to quickly combine their precomputed KV caches in order to achieve the same generation quality as the expensive full prefill (i.e., without reusing KV cache)? We present CacheBlend, a scheme that reuses the pre-computed KV caches, regardless prefix or not, and selectively recomputes the KV values of a small subset of tokens to partially update each reused KV cache. In the meantime,the small extra delay for recomputing some tokens can be pipelined with the retrieval of KV caches within the same job,allowing CacheBlend to store KV caches in slower devices with more storage capacity while retrieving them without increasing the inference delay. By comparing CacheBlend with the state-of-the-art KV cache reusing schemes on three open-source LLMs of various sizes and four popular benchmark datasets of different tasks, we show that CacheBlend reduces time-to-first-token (TTFT) by 2.2-3.3X and increases the inference throughput by 2.8-5X, compared with full KV recompute, without compromising generation quality or incurring more storage cost.

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x1.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x2.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x3.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x4.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x5.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x6.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x7.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x8.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x9.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x10.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x11.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x12.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x13.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x14.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x15.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x16.png)

![CacheBlend：融合缓存知识，加速大型语言模型服务](../../../paper_images/2405.16444/x17.png)

[Arxiv](https://arxiv.org/abs/2405.16444)