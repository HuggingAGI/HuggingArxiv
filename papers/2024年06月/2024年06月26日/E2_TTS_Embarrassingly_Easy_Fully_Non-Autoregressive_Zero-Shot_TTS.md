# E2 TTS：令人尴尬的容易完全非自回归零样本 TTS

发布时间：2024年06月26日

`LLM应用` `语音处理` `文本转语音`

> E2 TTS: Embarrassingly Easy Fully Non-Autoregressive Zero-Shot TTS

# 摘要

> 摘要：本文介绍了令人惊讶的简单文本转语音（E2 TTS），这是一个完全非自回归的零样本文本转语音系统，具有人类水平的自然度以及最先进的说话者相似度和清晰度。在 E2 TTS 框架中，文本输入被转换为带有填充标记的字符序列。然后基于音频填充任务训练基于流匹配的梅尔频谱图生成器。与许多以前的工作不同，它不需要额外的组件（例如，时长模型、字素到音素）或复杂的技术（例如，单调对齐搜索）。尽管它很简单，但 E2 TTS 实现了最先进的零样本 TTS 能力，可与包括 Voicebox 和 NaturalSpeech 3 在内的先前工作相媲美或超越。E2 TTS 的简单性还允许输入表示的灵活性。我们提出了 E2 TTS 的几个变体，以提高推理期间的可用性。有关演示样本，请访问此 https URL。

> 
Abstract:This paper introduces Embarrassingly Easy Text-to-Speech (E2 TTS), a fully non-autoregressive zero-shot text-to-speech system that offers human-level naturalness and state-of-the-art speaker similarity and intelligibility. In the E2 TTS framework, the text input is converted into a character sequence with filler tokens. The flow-matching-based mel spectrogram generator is then trained based on the audio infilling task. Unlike many previous works, it does not require additional components (e.g., duration model, grapheme-to-phoneme) or complex techniques (e.g., monotonic alignment search). Despite its simplicity, E2 TTS achieves state-of-the-art zero-shot TTS capabilities that are comparable to or surpass previous works, including Voicebox and NaturalSpeech 3. The simplicity of E2 TTS also allows for flexibility in the input representation. We propose several variants of E2 TTS to improve usability during inference. See this https URL for demo samples.
    

[Arxiv](https://arxiv.org/pdf/2406.18009)