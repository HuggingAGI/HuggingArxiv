# MacST：利用文本音译实现多口音转换的语音合成技术

发布时间：2024年09月14日

`LLM应用` `语音技术` `语言学`

> MacST: Multi-Accent Speech Synthesis via Text Transliteration for Accent Conversion

# 摘要

> 在口音转换中，我们旨在改变语音口音，同时保持说话者身份和语义内容不变。本研究提出了一种新颖的方法，通过文本音译生成同一说话者的多口音语音样本，用于训练口音转换系统。首先，我们利用大型语言模型生成音译文本，再通过多语言 TTS 模型合成带口音的英语语音。作为对比，我们还构建了一个基于合成平行语料库的序列到序列模型。实验证明，该方法对母语和非母语英语说话者均有效。主观和客观评估进一步确认了数据集在口音转换研究中的实用性。

> In accented voice conversion or accent conversion, we seek to convert the accent in speech from one another while preserving speaker identity and semantic content. In this study, we formulate a novel method for creating multi-accented speech samples, thus pairs of accented speech samples by the same speaker, through text transliteration for training accent conversion systems. We begin by generating transliterated text with Large Language Models (LLMs), which is then fed into multilingual TTS models to synthesize accented English speech. As a reference system, we built a sequence-to-sequence model on the synthetic parallel corpus for accent conversion. We validated the proposed method for both native and non-native English speakers. Subjective and objective evaluations further validate our dataset's effectiveness in accent conversion studies.

[Arxiv](https://arxiv.org/abs/2409.09352)