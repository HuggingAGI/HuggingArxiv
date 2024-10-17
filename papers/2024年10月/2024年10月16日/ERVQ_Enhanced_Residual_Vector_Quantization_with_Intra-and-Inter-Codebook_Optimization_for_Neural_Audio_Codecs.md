# ERVQ：通过代码本内外的优化，增强残差向量量化，应用于神经音频编解码器

发布时间：2024年10月16日

`LLM应用` `音频处理` `语音识别`

> ERVQ: Enhanced Residual Vector Quantization with Intra-and-Inter-Codebook Optimization for Neural Audio Codecs

# 摘要

> 当前神经音频编解码器常用 RVQ 离散语音信号，但常遇码本崩溃，导致性能不佳。为此，我们推出 ERVQ，通过码本内外的优化，有效缓解崩溃，提升性能。实验显示，ERVQ 在多种条件下显著提升编解码器质量，甚至实现 100% 码本利用率。此外，ERVQ 还能增强语音和文本 LLM，尤其在零-shot 文本转语音任务中，语音自然度显著提升。音频样本可在此获取。

> Current neural audio codecs typically use residual vector quantization (RVQ) to discretize speech signals. However, they often experience codebook collapse, which reduces the effective codebook size and leads to suboptimal performance. To address this problem, we introduce ERVQ, Enhanced Residual Vector Quantization, a novel enhancement strategy for the RVQ framework in neural audio codecs. ERVQ mitigates codebook collapse and boosts codec performance through both intra- and inter-codebook optimization. Intra-codebook optimization incorporates an online clustering strategy and a code balancing loss to ensure balanced and efficient codebook utilization. Inter-codebook optimization improves the diversity of quantized features by minimizing the similarity between successive quantizations. Our experiments show that ERVQ significantly enhances audio codec performance across different models, sampling rates, and bitrates, achieving superior quality and generalization capabilities. It also achieves 100% codebook utilization on one of the most advanced neural audio codecs. Further experiments indicate that audio codecs improved by the ERVQ strategy can improve unified speech-and-text large language models (LLMs). Specifically, there is a notable improvement in the naturalness of generated speech in downstream zero-shot text-to-speech tasks. Audio samples are available here.

[Arxiv](https://arxiv.org/abs/2410.12359)