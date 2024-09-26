# 借助大型语音-文本基础模型，提升语音识别的精准度

发布时间：2024年09月25日

`LLM应用` `语音识别`

> Speech Recognition Rescoring with Large Speech-Text Foundation Models

# 摘要

> 大型语言模型 (LLM) 通过海量文本数据展现了理解人类语言的强大能力。然而，自动语音识别 (ASR) 系统受限于有限的转录数据，因此使用 LLM 进行二次评分能显著提升性能。最近，多模态 LLM，尤其是语音与文本基础模型，在口语理解方面表现出色。这些模型融合了语音与文本中的大量未标记及标记数据，以更全面地建模人类语言。在此研究中，我们创新性地运用多模态 LLM 进行 ASR 评分，并探索判别训练以进一步提升评分效果。实验结果显示，跨模态知识转移在语音-文本 LLM 中尤为有效，相较于 Whisper 大型 ASR 和仅文本 LLM，分别实现了高达 20% 和 15% 的相对性能提升。

> Large language models (LLM) have demonstrated the ability to understand human language by leveraging large amount of text data. Automatic speech recognition (ASR) systems are often limited by available transcribed speech data and benefit from a second pass rescoring using LLM. Recently multi-modal large language models, particularly speech and text foundational models have demonstrated strong spoken language understanding. Speech-Text foundational models leverage large amounts of unlabelled and labelled data both in speech and text modalities to model human language. In this work, we propose novel techniques to use multi-modal LLM for ASR rescoring. We also explore discriminative training to further improve the foundational model rescoring performance. We demonstrate cross-modal knowledge transfer in speech-text LLM can benefit rescoring. Our experiments demonstrate up-to 20% relative improvements over Whisper large ASR and up-to 15% relative improvements over text-only LLM.

[Arxiv](https://arxiv.org/abs/2409.16654)