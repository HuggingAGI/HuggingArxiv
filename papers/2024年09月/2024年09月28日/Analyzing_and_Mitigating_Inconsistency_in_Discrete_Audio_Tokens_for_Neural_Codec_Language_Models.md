# 探究并解决神经编解码语言模型中离散音频标记的不一致问题

发布时间：2024年09月28日

`LLM应用` `音频处理` `语音识别`

> Analyzing and Mitigating Inconsistency in Discrete Audio Tokens for Neural Codec Language Models

# 摘要

> 随着大型语言模型 (LLM) 的发展，音频处理领域对使用离散音频令牌序列进行音频生成任务的训练越来越感兴趣。然而，通过神经音频编解码器直接离散化音频往往会产生与文本序列截然不同的结果。与确定性的文本令牌序列不同，离散音频令牌会因上下文因素而表现出显著的可变性，但仍能生成感知上相同的音频段。这种现象被称为 **离散表示不一致性 (DRI)**。DRI 会导致单个音频段由多个不同的序列表示，从而在神经编解码语言模型中引发混淆，并在语音生成过程中出现遗漏和重复。本文定量分析了 EnCodec 等流行音频分词器中的 DRI 现象，并提出了一种有效缓解 DRI 的方法。在 LibriTTS 和大规模 MLS 数据集（44,000 小时）上的广泛实验表明，我们的方法不仅有效，而且具有广泛的适用性。音频样本的演示可在网上查看~\footnote{\url{https://consistencyinneuralcodec.github.io}}。

> Building upon advancements in Large Language Models (LLMs), the field of audio processing has seen increased interest in training audio generation tasks with discrete audio token sequences. However, directly discretizing audio by neural audio codecs often results in sequences that fundamentally differ from text sequences. Unlike text, where text token sequences are deterministic, discrete audio tokens can exhibit significant variability based on contextual factors, while still producing perceptually identical audio segments. We refer to this phenomenon as \textbf{Discrete Representation Inconsistency (DRI)}. This inconsistency can lead to a single audio segment being represented by multiple divergent sequences, which creates confusion in neural codec language models and results in omissions and repetitions during speech generation. In this paper, we quantitatively analyze the DRI phenomenon within popular audio tokenizers such as EnCodec. Our approach effectively mitigates the DRI phenomenon of the neural audio codec. Furthermore, extensive experiments on the neural codec language model over LibriTTS and large-scale MLS datases (44,000 hours) demonstrate the effectiveness and generality of our method. The demo of audio samples is available online~\footnote{\url{https://consistencyinneuralcodec.github.io}}.

[Arxiv](https://arxiv.org/abs/2409.19283)