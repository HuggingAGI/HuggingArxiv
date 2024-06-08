# 在基于提示的文本转语音合成中，采用上下文感知的对比语言-音频预训练技术，实现了检索增强的生成效果。

发布时间：2024年06月05日

`RAG

理由：这篇论文主要介绍了将检索增强生成（RAG）技术应用于文本转语音（TTS）模型中，通过引入上下文信息来改进语音提示的选择，从而提高生成语音的质量。这与RAG技术的应用直接相关，因此归类为RAG。虽然涉及到了大型语言模型（LLMs），但重点在于RAG技术的应用而非LLM的理论或应用。` `语音合成`

> Retrieval Augmented Generation in Prompt-based Text-to-Speech Synthesis with Context-Aware Contrastive Language-Audio Pretraining

# 摘要

> 基于提示的文本转语音（TTS）模型近期已能通过简短的语音提示复制未知说话者的声音，其强大的上下文模仿能力涵盖了说话者的风格、韵律及情感。因此，语音提示的选择对生成语音的质量至关重要，其重要性不亚于大型语言模型（LLMs）中的提示。然而，现有的TTS模型在选择语音提示时或是人工操作，或是随机选择。为此，本文将大型语言模型中的检索增强生成（RAG）技术引入TTS领域，并创新性地在检索过程中融入上下文信息，开发了上下文感知对比语言-音频预训练（CA-CLAP）模型，以提取与上下文和风格紧密相关的特征。评估结果显示，我们的RAG方法表现优于传统方法，CA-CLAP模型在文本检索方面也取得了更佳效果。

> Recent prompt-based text-to-speech (TTS) models can clone an unseen speaker using only a short speech prompt. They leverage a strong in-context ability to mimic the speech prompts, including speaker style, prosody, and emotion. Therefore, the selection of a speech prompt greatly influences the generated speech, akin to the importance of a prompt in large language models (LLMs). However, current prompt-based TTS models choose the speech prompt manually or simply at random. Hence, in this paper, we adapt retrieval augmented generation (RAG) from LLMs to prompt-based TTS. Unlike traditional RAG methods, we additionally consider contextual information during the retrieval process and present a Context-Aware Contrastive Language-Audio Pre-training (CA-CLAP) model to extract context-aware, style-related features. The objective and subjective evaluations demonstrate that our proposed RAG method outperforms baselines, and our CA-CLAP achieves better results than text-only retrieval methods.

![在基于提示的文本转语音合成中，采用上下文感知的对比语言-音频预训练技术，实现了检索增强的生成效果。](../../../paper_images/2406.03714/RAG3.png)

![在基于提示的文本转语音合成中，采用上下文感知的对比语言-音频预训练技术，实现了检索增强的生成效果。](../../../paper_images/2406.03714/model2.png)

[Arxiv](https://arxiv.org/abs/2406.03714)