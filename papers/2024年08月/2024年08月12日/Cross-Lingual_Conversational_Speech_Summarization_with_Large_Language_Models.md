# 大型语言模型在跨语言对话语音摘要中的应用

发布时间：2024年08月12日

`LLM应用` `语音技术`

> Cross-Lingual Conversational Speech Summarization with Large Language Models

# 摘要

> 跨语言对话语音摘要虽重要，却资源稀缺。我们扩展了Fisher和Callhome语料库，新增翻译与GPT-4生成的摘要。任务是在转录和翻译错误下生成相似摘要。我们构建了开源模型级联的基线系统，测试了多种LLM，并分析了错误影响。定制的Mistral-7B模型表现出色，媲美GPT-4。

> Cross-lingual conversational speech summarization is an important problem, but suffers from a dearth of resources. While transcriptions exist for a number of languages, translated conversational speech is rare and datasets containing summaries are non-existent. We build upon the existing Fisher and Callhome Spanish-English Speech Translation corpus by supplementing the translations with summaries. The summaries are generated using GPT-4 from the reference translations and are treated as ground truth. The task is to generate similar summaries in the presence of transcription and translation errors. We build a baseline cascade-based system using open-source speech recognition and machine translation models. We test a range of LLMs for summarization and analyze the impact of transcription and translation errors. Adapting the Mistral-7B model for this task performs significantly better than off-the-shelf models and matches the performance of GPT-4.

[Arxiv](https://arxiv.org/abs/2408.06484)