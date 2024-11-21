# Hard-Synth：借助零样本 TTS 和 LLM 为 ASR 合成各类困难样本

发布时间：2024年11月20日

`LLM应用` `语音识别` `数据增强`

> Hard-Synth: Synthesizing Diverse Hard Samples for ASR using Zero-Shot TTS and LLM

# 摘要

> 文本到语音（TTS）模型已被广泛用于借助纯文本语料库增强自动语音识别（ASR）系统，由此降低了真实语音数据的标注成本。现有的研究主要运用TTS模型所支持的额外文本数据和预定义的语音风格。在本文中，我们提出了Hard-Synth，这是一种创新的ASR数据增强方法，它借助大型语言模型（LLMs）和先进的零样本TTS。我们的方法通过LLMs重写生成各类域内文本，无需依赖额外的文本数据。我们未采用预定义的语音风格，而是引入了一种结合零样本TTS的硬提示选择方法，来克隆ASR模型难以识别的语音风格。实验表明，Hard-Synth显著提升了Conformer模型的性能，在LibriSpeech的dev / test-other子集中，相对字错误率（WER）分别降低了6.5％和4.4％。此外，我们证明Hard-Synth数据利用效率高，且能够减少ASR中的偏差。

> Text-to-speech (TTS) models have been widely adopted to enhance automatic speech recognition (ASR) systems using text-only corpora, thereby reducing the cost of labeling real speech data. Existing research primarily utilizes additional text data and predefined speech styles supported by TTS models. In this paper, we propose Hard-Synth, a novel ASR data augmentation method that leverages large language models (LLMs) and advanced zero-shot TTS. Our approach employs LLMs to generate diverse in-domain text through rewriting, without relying on additional text data. Rather than using predefined speech styles, we introduce a hard prompt selection method with zero-shot TTS to clone speech styles that the ASR model finds challenging to recognize. Experiments demonstrate that Hard-Synth significantly enhances the Conformer model, achieving relative word error rate (WER) reductions of 6.5\%/4.4\% on LibriSpeech dev/test-other subsets. Additionally, we show that Hard-Synth is data-efficient and capable of reducing bias in ASR.

[Arxiv](https://arxiv.org/abs/2411.13159)