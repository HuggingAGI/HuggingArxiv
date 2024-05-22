# 利用矩阵分解技术，实现无需原始数据支持的低比特量化，以优化KV缓存压缩效率

发布时间：2024年05月21日

`LLM理论

这篇论文主要探讨了大型语言模型（LLM）中的KV缓存技术及其内存负担问题，并提出了一种新的量化技术——DecoQuant。该技术通过张量分解来优化KV缓存的压缩，同时保持模型的生成质量。这种研究属于对LLM内部机制和优化技术的理论探讨，因此应归类于LLM理论。` `人工智能` `高性能计算`

> Unlocking Data-free Low-bit Quantization with Matrix Decomposition for KV Cache Compression

# 摘要

> KV 缓存技术虽能加速大型语言模型推理，却伴随着显著的内存负担。现有压缩方法往往牺牲精度或依赖额外校准数据，限制了其实际应用。本文推出的 **DecoQuant**，一种基于张量分解的无数据低比特量化技术，有效压缩 KV 缓存。我们通过张量分解调整原始矩阵的异常值分布，将量化难题转移至分解后的局部张量。研究发现，异常值多集中于小张量，而大张量的值域较窄。据此，我们建议对大张量采用低比特量化，小张量则保持高精度。此外，我们还开发了专为 DecoQuant 定制的高效解量化内核，以加速推理。实验证明，DecoQuant 在减少约 75% 内存占用的同时，保持了生成质量。

> Key-value~(KV) caching is an important technique to accelerate the inference of large language models~(LLMs), but incurs significant memory overhead. To compress the size of KV cache, existing methods often compromise precision or require extra data for calibration, limiting their practicality in LLM deployment. In this paper, we introduce \textbf{DecoQuant}, a novel data-free low-bit quantization technique based on tensor decomposition methods, to effectively compress KV cache. Our core idea is to adjust the outlier distribution of the original matrix by performing tensor decomposition, so that the quantization difficulties are migrated from the matrix to decomposed local tensors. Specially, we find that outliers mainly concentrate on small local tensors, while large tensors tend to have a narrower value range. Based on this finding, we propose to apply low-bit quantization to the large tensor, while maintaining high-precision representation for the small tensor. Furthermore, we utilize the proposed quantization method to compress the KV cache of LLMs to accelerate the inference and develop an efficient dequantization kernel tailored specifically for DecoQuant. Through extensive experiments, DecoQuant demonstrates remarkable efficiency gains, showcasing up to a $\sim$75\% reduction in memory footprint while maintaining comparable generation quality.

[Arxiv](https://arxiv.org/abs/2405.12591)