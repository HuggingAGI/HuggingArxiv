# 通过上下文优化，提升大型语言模型在识别罕见与模糊词汇时的语音识别能力。

发布时间：2024年08月15日

`LLM应用` `语音识别` `人工智能`

> Enhancing Large Language Model-based Speech Recognition by Contextualization for Rare and Ambiguous Words

# 摘要

> 我们构建了一个基于 LLM 的 ASR 系统，通过在文本提示中加入关键词，实现上下文感知。系统采用仅解码器架构，核心是 PLaMo-100B，一款从零开始预训练的 LLM，主要使用日英双语数据集。音频编码器选用预训练的 Whisper，其音频嵌入通过适配层映射到文本空间，并与文本提示的嵌入结合，作为解码器输入。这一设计使得系统无需调整架构，即可通过关键词精准转录含糊词汇。实验证实，关键词的引入大幅提升了对稀有及模糊词汇的识别准确率。

> We develop a large language model (LLM) based automatic speech recognition (ASR) system that can be contextualized by providing keywords as prior information in text prompts. We adopt decoder-only architecture and use our in-house LLM, PLaMo-100B, pre-trained from scratch using datasets dominated by Japanese and English texts as the decoder. We adopt a pre-trained Whisper encoder as an audio encoder, and the audio embeddings from the audio encoder are projected to the text embedding space by an adapter layer and concatenated with text embeddings converted from text prompts to form inputs to the decoder. By providing keywords as prior information in the text prompts, we can contextualize our LLM-based ASR system without modifying the model architecture to transcribe ambiguous words in the input audio accurately. Experimental results demonstrate that providing keywords to the decoder can significantly improve the recognition performance of rare and ambiguous words.

[Arxiv](https://arxiv.org/abs/2408.08027)