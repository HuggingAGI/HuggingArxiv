# LA-RAG：借助检索增强生成技术，提升基于 LLM 的语音识别准确性

发布时间：2024年09月13日

`RAG` `语音识别` `人工智能`

> LA-RAG:Enhancing LLM-based ASR Accuracy with Retrieval-Augmented Generation

# 摘要

> 最新研究将语音信息融入 LLM，大幅提升了 ASR 准确性。然而，现有方法在处理不同口音等声学条件时，常受限于语音编码器的能力。为此，我们创新提出 LA-RAG，一种基于 LLM 的 ASR 检索增强生成模型。LA-RAG 通过细粒度语音数据存储和语音检索机制，借助 LLM 的 in-context learning 能力，显著提升 ASR 准确性。实验结果显示，在普通话及多种方言数据集上，LA-RAG 表现优异，尤其在应对口音变化时更显优势。

> Recent advancements in integrating speech information into large language models (LLMs) have significantly improved automatic speech recognition (ASR) accuracy. However, existing methods often constrained by the capabilities of the speech encoders under varied acoustic conditions, such as accents. To address this, we propose LA-RAG, a novel Retrieval-Augmented Generation (RAG) paradigm for LLM-based ASR. LA-RAG leverages fine-grained token-level speech datastores and a speech-to-speech retrieval mechanism to enhance ASR accuracy via LLM in-context learning (ICL) capabilities. Experiments on Mandarin and various Chinese dialect datasets demonstrate significant improvements in ASR accuracy compared to existing methods, validating the effectiveness of our approach, especially in handling accent variations.

[Arxiv](https://arxiv.org/abs/2409.08597)