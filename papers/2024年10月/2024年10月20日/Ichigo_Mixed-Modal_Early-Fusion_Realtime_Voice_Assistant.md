# Ichigo：一款结合多种模态、早期融合技术的实时语音助手

发布时间：2024年10月20日

`LLM应用` `语音识别`

> Ichigo: Mixed-Modal Early-Fusion Realtime Voice Assistant

# 摘要

> 大型语言模型 (LLM) 在自然语言处理领域取得了革命性进展，但在处理语音任务时，由于音频与文本模态整合的复杂性，仍面临挑战。本文介绍的 Ichigo 模型，通过混合模态处理，能够无缝衔接语音与文本。Ichigo 采用早期融合的标记化技术，将语音量化为离散标记，并统一使用基于 Transformer 的架构，实现跨模态的联合推理与生成，无需额外适配器。我们提出了一套全面的训练流程，包括多语言语音识别数据集的预训练和精选指令数据集的微调。Ichigo 在语音问答基准测试中表现卓越，超越现有开源模型，与级联系统媲美。其生成首个标记的延迟仅为 111 毫秒，远低于同类模型。这一创新不仅推动了多模态 AI 的发展，还为小型研究团队提供了参与开源语音语言模型开发的框架。

> Large Language Models (LLMs) have revolutionized natural language processing, but their application to speech-based tasks remains challenging due to the complexities of integrating audio and text modalities. This paper introduces Ichigo, a mixed-modal model that seamlessly processes interleaved sequences of speech and text. Utilizing a tokenized early-fusion approach, Ichigo quantizes speech into discrete tokens and employs a uniform transformer-based architecture for both speech and text modalities. This method enables joint reasoning and generation across modalities without the need for separate adapters. We present a comprehensive training methodology, including pre-training on multilingual speech recognition datasets and fine-tuning on a curated instruction dataset. Ichigo demonstrates state-of-the-art performance on speech question-answering benchmarks, outperforming existing open-source speech language models and achieving comparable results to cascaded systems. Notably, Ichigo exhibits a latency of just 111 ms to first token generation, significantly lower than current models. Our approach not only advances the field of multimodal AI but also provides a framework for smaller research teams to contribute effectively to open-source speech-language models.

[Arxiv](https://arxiv.org/abs/2410.15316)