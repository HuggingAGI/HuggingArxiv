# 基于 LLM 的字素到音素转换：基准测试与案例分析

发布时间：2024年09月13日

`LLM应用` `语音处理` `语音合成`

> LLM-Powered Grapheme-to-Phoneme Conversion: Benchmark and Case Study

# 摘要

> G2P 转换在语音处理中至关重要，尤其是在语音合成领域。G2P 系统需深入理解多音字和上下文相关音素。近期，大型语言模型 (LLM) 在多语言任务中展现出巨大潜力，暗示其语音知识可用于 G2P。本文评估了 LLM 在 G2P 转换中的表现，并提出无需额外训练或标注数据的提示与后处理方法，以提升 LLM 输出。此外，我们设计了一个基准数据集，用于评估波斯语句子级语音挑战中的 G2P 性能。实验结果显示，通过应用这些方法，LLM 在波斯语等代表性不足的语言中也能超越传统 G2P 工具，凸显了 LLM 辅助 G2P 系统的广阔前景。

> Grapheme-to-phoneme (G2P) conversion is critical in speech processing, particularly for applications like speech synthesis. G2P systems must possess linguistic understanding and contextual awareness of languages with polyphone words and context-dependent phonemes. Large language models (LLMs) have recently demonstrated significant potential in various language tasks, suggesting that their phonetic knowledge could be leveraged for G2P. In this paper, we evaluate the performance of LLMs in G2P conversion and introduce prompting and post-processing methods that enhance LLM outputs without additional training or labeled data. We also present a benchmarking dataset designed to assess G2P performance on sentence-level phonetic challenges of the Persian language. Our results show that by applying the proposed methods, LLMs can outperform traditional G2P tools, even in an underrepresented language like Persian, highlighting the potential of developing LLM-aided G2P systems.

[Arxiv](https://arxiv.org/abs/2409.08554)