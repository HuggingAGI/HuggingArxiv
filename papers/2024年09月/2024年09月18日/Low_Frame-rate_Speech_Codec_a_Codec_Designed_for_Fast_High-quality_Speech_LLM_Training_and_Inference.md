# 低帧率语音编解码器：专为高效、高质量的语音LLM训练与推理而生

发布时间：2024年09月18日

`LLM应用` `音频处理` `语音技术`

> Low Frame-rate Speech Codec: a Codec Designed for Fast High-quality Speech LLM Training and Inference

# 摘要

> 大型语言模型 (LLM) 通过音频编解码器将音频转换为离散令牌，显著提升了音频处理能力。然而，高帧率导致训练和推理速度缓慢，尤其在自回归模型中。为此，我们推出了低帧率语音编解码器 (LFSC)，利用有限标量量化和大语音语言模型的对抗训练，实现了 1.89 kbps 比特率和 21.5 帧每秒的高质量音频压缩。实验表明，LFSC 不仅使 LLM 文本到语音模型的推理速度提升三倍，还提高了语音清晰度，质量媲美以往模型。

> Large language models (LLMs) have significantly advanced audio processing through audio codecs that convert audio into discrete tokens, enabling the application of language modeling techniques to audio data. However, audio codecs often operate at high frame rates, resulting in slow training and inference, especially for autoregressive models. To address this challenge, we present the Low Frame-rate Speech Codec (LFSC): a neural audio codec that leverages finite scalar quantization and adversarial training with large speech language models to achieve high-quality audio compression with a 1.89 kbps bitrate and 21.5 frames per second. We demonstrate that our novel codec can make the inference of LLM-based text-to-speech models around three times faster while improving intelligibility and producing quality comparable to previous models.

[Arxiv](https://arxiv.org/abs/2409.12117)