# 提升扩散模型在文本转语音中的频谱图上采样效果：一次实践探索

发布时间：2024年06月07日

`LLM应用

这篇论文主要探讨了自回归语言模型（LM）在文本到语音（TTS）系统中的应用，特别是在使用离散语音令牌和扩散模型来提高语音生成的质量和效率。论文关注的是如何通过改进上采样阶段的扩散模型来优化基于LM的TTS系统，以减少延迟并提高实时语音应用的适用性。因此，这篇论文属于大型语言模型（LLM）的应用范畴。` `语音合成` `人工智能`

> Boosting Diffusion Model for Spectrogram Up-sampling in Text-to-speech: An Empirical Study

# 摘要

> 通过将波形量化为离散语音令牌，自回归语言模型（LM）在扩展文本到语音（TTS）系统至大规模数据集方面取得了显著进展，有效捕捉了人类语音的丰富多样性和表现力。然而，离散语音令牌重建的语音质量，受限于压缩比，仍未达到理想水平。生成扩散模型和连续归一化流模型，在图像和语音生成领域表现卓越。基于LM的TTS系统通常将语音量化为离散令牌，自回归生成，再通过扩散模型将粗粒度令牌上采样至细粒度编解码器特征或梅尔频谱图，最后由声码器转换为波形，这一过程存在高延迟，不适用于实时语音应用。本文系统探讨了上采样阶段的不同扩散模型，这是LM和基于扩散架构流式合成的关键瓶颈，我们提出了模型架构、客观与主观评价指标，以展示其在质量和效率上的改进。

> Scaling text-to-speech (TTS) with autoregressive language model (LM) to large-scale datasets by quantizing waveform into discrete speech tokens is making great progress to capture the diversity and expressiveness in human speech, but the speech reconstruction quality from discrete speech token is far from satisfaction depending on the compressed speech token compression ratio. Generative diffusion models trained with score-matching loss and continuous normalized flow trained with flow-matching loss have become prominent in generation of images as well as speech. LM based TTS systems usually quantize speech into discrete tokens and generate these tokens autoregressively, and finally use a diffusion model to up sample coarse-grained speech tokens into fine-grained codec features or mel-spectrograms before reconstructing into waveforms with vocoder, which has a high latency and is not realistic for real time speech applications. In this paper, we systematically investigate varied diffusion models for up sampling stage, which is the main bottleneck for streaming synthesis of LM and diffusion-based architecture, we present the model architecture, objective and subjective metrics to show quality and efficiency improvement.

[Arxiv](https://arxiv.org/abs/2406.04633)