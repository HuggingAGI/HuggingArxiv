# 利用大型语言模型，我们正致力于提升多说话者场景下的自动语音识别性能。

发布时间：2024年08月30日

`LLM应用` `语音识别` `人工智能`

> Advancing Multi-talker ASR Performance with Large Language Models

# 摘要

> 在对话场景中识别多说话者的重叠语音是ASR的一大难题。传统的序列化输出训练（SOT）方法通过连接不同说话者的转录进行训练，但严重依赖长上下文建模。相比之下，我们提出了一种基于大型语言模型（LLM）的新方法，利用预训练解码器的能力，更适合处理这类复杂场景。实验证明，我们的方法在LibriMix模拟数据集上超越了传统AED方法，并在AMI真实数据集上达到顶尖性能，甚至优于使用大量监督数据训练的AED模型。

> Recognizing overlapping speech from multiple speakers in conversational scenarios is one of the most challenging problem for automatic speech recognition (ASR). Serialized output training (SOT) is a classic method to address multi-talker ASR, with the idea of concatenating transcriptions from multiple speakers according to the emission times of their speech for training. However, SOT-style transcriptions, derived from concatenating multiple related utterances in a conversation, depend significantly on modeling long contexts. Therefore, compared to traditional methods that primarily emphasize encoder performance in attention-based encoder-decoder (AED) architectures, a novel approach utilizing large language models (LLMs) that leverages the capabilities of pre-trained decoders may be better suited for such complex and challenging scenarios. In this paper, we propose an LLM-based SOT approach for multi-talker ASR, leveraging pre-trained speech encoder and LLM, fine-tuning them on multi-talker dataset using appropriate strategies. Experimental results demonstrate that our approach surpasses traditional AED-based methods on the simulated dataset LibriMix and achieves state-of-the-art performance on the evaluation set of the real-world dataset AMI, outperforming the AED model trained with 1000 times more supervised data in previous works.

[Arxiv](https://arxiv.org/abs/2408.17431)