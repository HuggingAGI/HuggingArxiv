# 无指令数据，精炼端到端语音助手

发布时间：2024年10月03日

`LLM应用` `语音助手` `人工智能`

> Distilling an End-to-End Voice Assistant Without Instruction Training Data

# 摘要

> 传统的语音助手如Siri和Google Assistant，分别处理音频和文本，导致语音信息丢失和系统复杂性增加。近期，通过监督微调训练的端到端语音LLM虽然有所改进，但仍“遗忘”了仅文本模型的能力。我们提出了一种新方法，利用仅文本LLM对转录文本的响应进行自监督训练语音LLM，无需额外指令数据。这种方法无需标注响应，且我们的Distilled Voice Assistant（DiVA）在口语问答、分类和翻译任务中表现出色。尽管训练计算量大幅减少，DiVA在与Qwen 2 Audio等顶尖模型对比中，用户满意度高达72%。

> Voice assistants, such as Siri and Google Assistant, typically model audio and text separately, resulting in lost speech information and increased complexity. Recent efforts to address this with end-to-end Speech Large Language Models (LLMs) trained with supervised finetuning (SFT)
  have led to models ``forgetting" capabilities from text-only LLMs. Our work proposes an alternative paradigm for training Speech LLMs without instruction data, using the response of a text-only LLM to transcripts as self-supervision. Importantly, this process can be performed without annotated responses. We show that our Distilled Voice Assistant (DiVA) generalizes to Spoken Question Answering, Classification, and Translation. Furthermore, we show that DiVA better meets user preferences, achieving a 72\% win rate compared with state-of-the-art models like Qwen 2 Audio, despite using $>$100x less training compute.

[Arxiv](https://arxiv.org/abs/2410.02678)