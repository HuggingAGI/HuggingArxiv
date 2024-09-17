# 本研究探讨了如何利用大型语言模型进行零-shot 非侵入性语音评估。

发布时间：2024年09月15日

`LLM应用` `语音识别`

> A Study on Zero-shot Non-intrusive Speech Assessment using Large Language Models

# 摘要

> 本研究探讨了两种利用大型语言模型进行零-shot非侵入式语音评估的方法。首先，我们测试了GPT-4o的音频分析能力。接着，我们提出了GPT-Whisper，它结合Whisper进行音频转文本，并通过精准的提示工程评估文本的自然度。实验表明，GPT-4o在音频分析上表现不佳，而GPT-Whisper不仅在语音质量和可理解性上显示出中等相关性，还与CER高度相关。与现有的监督式模型相比，GPT-Whisper在CER的Spearman相关性上表现更优。这些结果证实了GPT-Whisper无需额外训练数据即可实现精准零-shot语音评估的可靠性。

> This work investigates two strategies for zero-shot non-intrusive speech assessment leveraging large language models. First, we explore the audio analysis capabilities of GPT-4o. Second, we propose GPT-Whisper, which uses Whisper as an audio-to-text module and evaluates the naturalness of text via targeted prompt engineering. We evaluate assessment metrics predicted by GPT-4o and GPT-Whisper examining their correlations with human-based quality and intelligibility assessments, and character error rate (CER) of automatic speech recognition. Experimental results show that GPT-4o alone is not effective for audio analysis; whereas, GPT-Whisper demonstrates higher prediction, showing moderate correlation with speech quality and intelligibility, and high correlation with CER. Compared to supervised non-intrusive neural speech assessment models, namely MOS-SSL and MTI-Net, GPT-Whisper yields a notably higher Spearman's rank correlation with the CER of Whisper. These findings validate GPT-Whisper as a reliable method for accurate zero-shot speech assessment without requiring additional training data (speech data and corresponding assessment scores).

[Arxiv](https://arxiv.org/abs/2409.09914)