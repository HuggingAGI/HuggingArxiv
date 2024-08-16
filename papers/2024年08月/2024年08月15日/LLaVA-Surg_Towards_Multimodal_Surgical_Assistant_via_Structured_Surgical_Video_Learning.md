# LLaVA-Surg：借助结构化手术视频学习，打造多模态手术助手

发布时间：2024年08月15日

`LLM应用` `人工智能`

> LLaVA-Surg: Towards Multimodal Surgical Assistant via Structured Surgical Video Learning

# 摘要

> 多模态LLMs在多领域大放异彩，但医学研究多聚焦于单一图像。通用视频多模态模型在手术视频对话理解上仍显不足，主因是缺乏手术领域数据集。本文中，我们推出了Surg-QA，一个包含102,000对手术视频与指令的巨型数据集。为构建此集，我们设计了创新的两阶段问答生成流程，借助LLM从公开手术讲座视频中系统学习手术知识。此流程通过简化生成步骤，让我们能选用性价比更高的本地开源LLM，而非昂贵付费服务，同时降低LLM幻觉风险，提升数据质量。基于Surg-QA，我们训练了LLaVA-Surg，一款能解答手术视频开放式问题的视觉-语言对话助手，并在零-shot手术视频问答任务上展现了其卓越性能，超越以往所有通用模型。我们将公开代码、模型及指令调优数据集。

> Multimodal large language models (LLMs) have achieved notable success across various domains, while research in the medical field has largely focused on unimodal images. Meanwhile, current general-domain multimodal models for videos still lack the capabilities to understand and engage in conversations about surgical videos. One major contributing factor is the absence of datasets in the surgical field. In this paper, we create a new dataset, Surg-QA, consisting of 102,000 surgical video-instruction pairs, the largest of its kind so far. To build such a dataset, we propose a novel two-stage question-answer generation pipeline with LLM to learn surgical knowledge in a structured manner from the publicly available surgical lecture videos. The pipeline breaks down the generation process into two stages to significantly reduce the task complexity, allowing us to use a more affordable, locally deployed open-source LLM than the premium paid LLM services. It also mitigates the risk of LLM hallucinations during question-answer generation, thereby enhancing the overall quality of the generated data. We further train LLaVA-Surg, a novel vision-language conversational assistant capable of answering open-ended questions about surgical videos, on this Surg-QA dataset, and conduct comprehensive evaluations on zero-shot surgical video question-answering tasks. We show that LLaVA-Surg significantly outperforms all previous general-domain models, demonstrating exceptional multimodal conversational skills in answering open-ended questions about surgical videos. We will release our code, model, and the instruction-tuning dataset.

[Arxiv](https://arxiv.org/abs/2408.07981)