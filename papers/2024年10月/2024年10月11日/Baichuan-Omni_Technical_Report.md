# 百川-Omni 技术报告

发布时间：2024年10月11日

`LLM应用` `人工智能` `开源社区`

> Baichuan-Omni Technical Report

# 摘要

> GPT-4o 的多模态能力和交互体验在实际应用中表现出色，但缺乏高性能的开源替代品。本文介绍了 Baichuan-Omni，首个开源的 7B 多模态大型语言模型，能同时处理图像、视频、音频和文本，提供卓越的交互体验和强大性能。我们设计了从 7B 模型开始的多模态训练方案，通过两阶段对齐和多任务微调，使模型有效处理视觉和音频数据。在全模态和多模态基准测试中表现优异，我们希望这一贡献能成为开源社区在多模态理解和实时交互领域的竞争基线。

> The salient multimodal capabilities and interactive experience of GPT-4o highlight its critical role in practical applications, yet it lacks a high-performing open-source counterpart. In this paper, we introduce Baichuan-Omni, the first open-source 7B Multimodal Large Language Model (MLLM) adept at concurrently processing and analyzing modalities of image, video, audio, and text, while delivering an advanced multimodal interactive experience and strong performance. We propose an effective multimodal training schema starting with 7B model and proceeding through two stages of multimodal alignment and multitask fine-tuning across audio, image, video, and text modal. This approach equips the language model with the ability to handle visual and audio data effectively. Demonstrating strong performance across various omni-modal and multimodal benchmarks, we aim for this contribution to serve as a competitive baseline for the open-source community in advancing multimodal understanding and real-time interaction.

[Arxiv](https://arxiv.org/abs/2410.08565)