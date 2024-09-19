# 思维链提示在语音翻译中的应用

发布时间：2024年09月17日

`LLM应用` `语音识别` `语音翻译`

> Chain-of-Thought Prompting for Speech Translation

# 摘要

> 大型语言模型 (LLM) 在语言理解和生成方面取得了显著进展。基于文本 LLM 的成功，最新研究将这些模型应用于语音嵌入提示，从而在自动语音识别 (ASR) 和自动语音翻译 (AST) 中表现出色的 Speech-LLM 模型。我们提出了一种新方法，利用 ASR 转录作为基于编码器-解码器文本 LLM 构建的 Speech-LLM 中的 AST 提示。Speech-LLM 模型包含语音编码器和 Megatron-T5 编码器-解码器结构。通过解码语音生成 ASR 转录，并结合编码语音进行提示，我们以两步链式思维 (CoT) 过程指导语音翻译。低秩适应 (LoRA) 用于 T5 LLM 的模型适应，性能优于全模型微调。实验显示，CoT 提示显著提升 AST 性能，在 6 个 En->X 或 X->En AST 任务中平均提高 2.4 BLEU 分。与预测 ASR 和 AST 转录连接序列的 CoT 预测方法相比，我们的方法平均提高 2 BLEU 分。

> Large language models (LLMs) have demonstrated remarkable advancements in language understanding and generation. Building on the success of text-based LLMs, recent research has adapted these models to use speech embeddings for prompting, resulting in Speech-LLM models that exhibit strong performance in automatic speech recognition (ASR) and automatic speech translation (AST). In this work, we propose a novel approach to leverage ASR transcripts as prompts for AST in a Speech-LLM built on an encoder-decoder text LLM. The Speech-LLM model consists of a speech encoder and an encoder-decoder structure Megatron-T5. By first decoding speech to generate ASR transcripts and subsequently using these transcripts along with encoded speech for prompting, we guide the speech translation in a two-step process like chain-of-thought (CoT) prompting. Low-rank adaptation (LoRA) is used for the T5 LLM for model adaptation and shows superior performance to full model fine-tuning. Experimental results show that the proposed CoT prompting significantly improves AST performance, achieving an average increase of 2.4 BLEU points across 6 En->X or X->En AST tasks compared to speech prompting alone. Additionally, compared to a related CoT prediction method that predicts a concatenated sequence of ASR and AST transcripts, our method performs better by an average of 2 BLEU points.

[Arxiv](https://arxiv.org/abs/2409.11538)