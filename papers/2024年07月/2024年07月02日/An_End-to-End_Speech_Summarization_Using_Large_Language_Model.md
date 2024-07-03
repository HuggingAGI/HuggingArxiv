# 利用大型语言模型实现端到端语音摘要

发布时间：2024年07月02日

`LLM应用` `语音处理`

> An End-to-End Speech Summarization Using Large Language Model

# 摘要

> 抽象语音摘要（SSum）旨在从口语内容中提炼出类人文本摘要，但处理长语音输入和捕捉跨模态复杂映射仍是一大挑战。本文提出一种端到端SSum模型，通过Q-Former连接音频与文本模态，并借助LLMs直接从语音特征生成摘要。我们采用多阶段训练策略，包括基于LLM的ASR和TSum任务，以对齐特征空间并增强处理长语音的能力。通过课程学习，模型顺利从TSum过渡到SSum，最终在How-2数据集上展现出优异性能。

> Abstractive Speech Summarization (SSum) aims to generate human-like text summaries from spoken content. It encounters difficulties in handling long speech input and capturing the intricate cross-modal mapping between long speech inputs and short text summaries. Research on large language models (LLMs) and multimodal information fusion has provided new insights for addressing these challenges. In this paper, we propose an end-to-end SSum model that utilizes Q-Former as a connector for the audio-text modality and employs LLMs to generate text summaries directly from speech features. We adopt a multi-stage training approach that includes LLM based ASR and Text Summarization (TSum) tasks as auxiliary tasks. ASR tasks are used to align feature spaces and enhance the LLM's ability to handle longer speech. Then, we utilize a curriculum learning strategy to facilitate the model's transition from TSum to SSum. Finally, our model achieves competitive performance on the How-2 dataset.

[Arxiv](https://arxiv.org/abs/2407.02005)