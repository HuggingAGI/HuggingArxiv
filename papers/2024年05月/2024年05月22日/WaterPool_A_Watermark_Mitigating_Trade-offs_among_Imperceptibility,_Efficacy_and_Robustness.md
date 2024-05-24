# WaterPool：平衡水印的隐秘性、效能与稳健性的创新方案

发布时间：2024年05月22日

`LLM应用

这篇论文主要讨论了大型语言模型（LLMs）的水印技术，这是一种应用层面的研究，旨在通过在文本中嵌入特定模式来追踪模型的使用。论文提出了一种新的水印方案，并通过实验证明了其有效性、不可感知性和鲁棒性。这与LLM的理论研究不同，因为它关注的是如何应用技术来解决实际问题，而不是探讨LLM的理论基础或内部机制。同时，这项工作也不属于Agent或RAG的范畴，因为它不涉及智能代理的行为或检索增强生成的方法。因此，最合适的分类是LLM应用。` `信息安全` `人工智能`

> WaterPool: A Watermark Mitigating Trade-offs among Imperceptibility, Efficacy and Robustness

# 摘要

> 随着大型语言模型（LLMs）在日常生活中的普及，其潜在的滥用和社会影响引起了人们的关注。水印技术应运而生，旨在通过在文本中嵌入特定模式来追踪模型的使用。理想的水印技术应做到三点：输出与原始LLM无异（不可感知）、检测率高（有效）、即使文本被篡改也能保持稳定（鲁棒）。然而，现有方法均未能完美兼顾这三者，显示出一种内在的权衡。本文提出了一种以密钥为中心的水印方案，将水印分解为密钥和标记两个模块，首次揭示了密钥模块在解决权衡问题中的关键作用。我们开发的**WaterPool**模块，在保持密钥采样空间完整性的同时，通过语义搜索优化了密钥恢复过程，有效提升了水印技术的性能。实验证明，WaterPool与三种主流水印技术结合后，不仅增强了不可感知性，还大幅提升了有效性和鲁棒性。

> With the increasing use of large language models (LLMs) in daily life, concerns have emerged regarding their potential misuse and societal impact. Watermarking is proposed to trace the usage of specific models by injecting patterns into their generated texts. An ideal watermark should produce outputs that are nearly indistinguishable from those of the original LLM (imperceptibility), while ensuring a high detection rate (efficacy), even when the text is partially altered (robustness). Despite many methods having been proposed, none have simultaneously achieved all three properties, revealing an inherent trade-off. This paper utilizes a key-centered scheme to unify existing watermarking techniques by decomposing a watermark into two distinct modules: a key module and a mark module. Through this decomposition, we demonstrate for the first time that the key module significantly contributes to the trade-off issues observed in prior methods. Specifically, this reflects the conflict between the scale of the key sampling space during generation and the complexity of key restoration during detection. To this end, we introduce \textbf{WaterPool}, a simple yet effective key module that preserves a complete key sampling space required by imperceptibility while utilizing semantics-based search to improve the key restoration process. WaterPool can integrate with most watermarks, acting as a plug-in. Our experiments with three well-known watermarking techniques show that WaterPool significantly enhances their performance, achieving near-optimal imperceptibility and markedly improving efficacy and robustness (+12.73\% for KGW, +20.27\% for EXP, +7.27\% for ITS).

[Arxiv](https://arxiv.org/abs/2405.13517)