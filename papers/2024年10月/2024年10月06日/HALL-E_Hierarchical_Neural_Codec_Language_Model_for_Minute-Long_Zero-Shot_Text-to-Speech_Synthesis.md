# HALL-E：一种分层神经编解码语言模型，专为长时间零-shot 文本到语音合成而设计。

发布时间：2024年10月06日

`LLM应用` `语音合成` `人工智能`

> HALL-E: Hierarchical Neural Codec Language Model for Minute-Long Zero-Shot Text-to-Speech Synthesis

# 摘要

> 近期，基于大型语言模型的文本到语音（TTS）技术备受瞩目，这些模型能将文本转化为离散的音频令牌序列。然而，长篇语音合成仍面临挑战，高帧率导致音频令牌过长，自回归模型难以处理。为此，我们提出了两种创新的后训练方法：多分辨率重新量化（MReQ）和HALL-E。MReQ通过多分辨率残差向量量化模块，降低预训练模型的帧率；HALL-E则是一个基于LLM的TTS模型，专门预测MReQ的分层令牌。我们还推出了MinutesSpeech数据集，包含40k小时语音数据，助力TTS研究。实验表明，我们的方法能将帧率降至8 Hz，实现稳定的一分钟长语音合成。相关资源已公开，详见https://yutonishimura-v2.github.io/HALL-E_DEMO/。

> Recently, Text-to-speech (TTS) models based on large language models (LLMs) that translate natural language text into sequences of discrete audio tokens have gained great research attention, with advances in neural audio codec (NAC) models using residual vector quantization (RVQ). However, long-form speech synthesis remains a significant challenge due to the high frame rate, which increases the length of audio tokens and makes it difficult for autoregressive language models to generate audio tokens for even a minute of speech. To address this challenge, this paper introduces two novel post-training approaches: 1) Multi-Resolution Requantization (MReQ) and 2) HALL-E. MReQ is a framework to reduce the frame rate of pre-trained NAC models. Specifically, it incorporates multi-resolution residual vector quantization (MRVQ) module that hierarchically reorganizes discrete audio tokens through teacher-student distillation. HALL-E is an LLM-based TTS model designed to predict hierarchical tokens of MReQ. Specifically, it incorporates the technique of using MRVQ sub-modules and continues training from a pre-trained LLM-based TTS model. Furthermore, to promote TTS research, we create MinutesSpeech, a new benchmark dataset consisting of 40k hours of filtered speech data for training and evaluating speech synthesis ranging from 3s up to 180s. In experiments, we demonstrated the effectiveness of our approaches by applying our post-training framework to VALL-E. We achieved the frame rate down to as low as 8 Hz, enabling the stable minitue-long speech synthesis in a single inference step. Audio samples, dataset, codes and pre-trained models are available at https://yutonishimura-v2.github.io/HALL-E_DEMO/.

[Arxiv](https://arxiv.org/abs/2410.04380)