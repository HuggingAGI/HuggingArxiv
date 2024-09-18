# 乌尔都语 ASR 模型基准测试：WER 我们站

发布时间：2024年09月17日

`LLM应用` `语音识别` `低资源语言`

> WER We Stand: Benchmarking Urdu ASR Models

# 摘要

> 本文全面评估了乌尔都语自动语音识别（ASR）模型。我们分析了Whisper、MMS和Seamless-M4T三个模型家族的性能，通过词错误率（WER）以及常见错误词和错误类型（插入、删除、替换）的详细检查。我们使用了朗读和对话两种语音数据集，并首次推出了专为乌尔都语ASR模型设计的对话语音数据集。结果显示，seamless-large在朗读语音数据集上表现最佳，而whisper-large在对话语音数据集上表现最佳。此外，评估还揭示了仅凭定量指标评估低资源语言ASR模型的复杂性，强调了建立乌尔都语文本规范化系统的重要性。我们的研究为开发乌尔都语等低资源语言的强大ASR系统提供了重要见解。

> This paper presents a comprehensive evaluation of Urdu Automatic Speech Recognition (ASR) models. We analyze the performance of three ASR model families: Whisper, MMS, and Seamless-M4T using Word Error Rate (WER), along with a detailed examination of the most frequent wrong words and error types including insertions, deletions, and substitutions. Our analysis is conducted using two types of datasets, read speech and conversational speech. Notably, we present the first conversational speech dataset designed for benchmarking Urdu ASR models. We find that seamless-large outperforms other ASR models on the read speech dataset, while whisper-large performs best on the conversational speech dataset. Furthermore, this evaluation highlights the complexities of assessing ASR models for low-resource languages like Urdu using quantitative metrics alone and emphasizes the need for a robust Urdu text normalization system. Our findings contribute valuable insights for developing robust ASR systems for low-resource languages like Urdu.

[Arxiv](https://arxiv.org/abs/2409.11252)