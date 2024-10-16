# QSpec：采用互补量化方案的推测性解码技术

发布时间：2024年10月15日

`LLM理论` `边缘计算` `人工智能`

> QSpec: Speculative Decoding with Complementary Quantization Schemes

# 摘要

> 量化技术广泛应用于加速大型语言模型（LLM）的推理并降低内存消耗。然而，激活-权重联合量化虽通过低精度内核加速推理，但在多步骤推理任务中性能严重下降。为此，我们提出新型量化范式QSPEC，它巧妙融合两种互补量化方案，实现推测性解码。QSPEC利用低成本切换，先用低精度快速量化生成候选令牌，再用高精度仅权重量化验证，兼具两者优势。与高精度方法相比，QSPEC在不牺牲质量的前提下，令牌生成吞吐量提升高达1.80倍，显著优于其他低精度方法。此优势在各类任务、模型大小、量化方法及批量大小中均表现一致。此外，QSPEC无需额外内存开销，且即插即用，无需训练。我们坚信，QSPEC将为未来高保真量化方案，特别是在内存受限场景（如边缘设备）中的部署，带来独特优势。

> Quantization has been substantially adopted to accelerate inference and reduce memory consumption of large language models (LLMs). While activation-weight joint quantization speeds up the inference process through low-precision kernels, we demonstrate that it suffers severe performance degradation on multi-step reasoning tasks, rendering it ineffective. We propose a novel quantization paradigm called QSPEC, which seamlessly integrates two complementary quantization schemes for speculative decoding. Leveraging nearly cost-free execution switching, QSPEC drafts tokens with low-precision, fast activation-weight quantization, and verifies them with high-precision weight-only quantization, effectively combining the strengths of both quantization schemes. Compared to high-precision quantization methods, QSPEC empirically boosts token generation throughput by up to 1.80x without any quality compromise, distinguishing it from other low-precision quantization approaches. This enhancement is also consistent across various serving tasks, model sizes, quantization methods, and batch sizes. Unlike existing speculative decoding techniques, our approach reuses weights and the KV cache, avoiding additional memory overhead. Furthermore, QSPEC offers a plug-and-play advantage without requiring any training. We believe that QSPEC demonstrates unique strengths for future deployment of high-fidelity quantization schemes, particularly in memory-constrained scenarios (e.g., edge devices).

[Arxiv](https://arxiv.org/abs/2410.11305)