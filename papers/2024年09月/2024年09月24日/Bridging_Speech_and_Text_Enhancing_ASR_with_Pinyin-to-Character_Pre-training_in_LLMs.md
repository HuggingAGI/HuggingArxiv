# 融合语音与文本：通过拼音到字符的预训练，提升 LLM 中的 ASR 性能

发布时间：2024年09月24日

`LLM应用` `语音识别` `人工智能`

> Bridging Speech and Text: Enhancing ASR with Pinyin-to-Character Pre-training in LLMs

# 摘要

> 将 LLM 与预训练语音模型结合，为 ASR 带来了新机遇。尽管 LLM 在多模态任务中表现优异，但在 ASR 中的应用仍具挑战。本文提出了一种新颖的训练方法，通过在拼音嵌入序列上预训练 LLM，使其能从发音特征生成中文文本，从而在接触真实语音数据前适应 ASR 任务。此外，微调 LoRA 参数以增强 LLM 对语音信息的理解。在 AISHELL-1 语料库中，我们的方法使 ASR 性能提升了 9.5%，而结合辅助文本数据预训练则进一步提升了 19.0%。

> The integration of large language models (LLMs) with pre-trained speech models has opened up new avenues in automatic speech recognition (ASR). While LLMs excel in multimodal understanding tasks, effectively leveraging their capabilities for ASR remains a significant challenge. This paper presents a novel training approach to enhance LLM performance in ASR tasks. We propose pre-training LLMs on Pinyin embedding sequences, which represent pronunciation features, to generate corresponding Chinese characters. This step enables the LLM to adapt to generating text from pronunciation features before encountering real speech data. Furthermore, we fine-tune the LoRA parameters to enhance the LLM's understanding of speech modality information. In AISHELL-1 corpus, our approach yields a 9.5% relative improvement in ASR tasks compared to the baseline without Pinyi-to-Character pre-training. Additionally, incorporating auxiliary text data for Pinyi-to-Character pre-training further boosts performance, achieving a 19.0% relative improvement.

[Arxiv](https://arxiv.org/abs/2409.16005)