# 百川-Omni 技术报告

发布时间：2024年10月11日

`LLM应用` `人工智能` `多媒体`

> Baichuan-Omni Technical Report

# 摘要

> GPT-4o 在多模态应用中的卓越表现虽引人注目，但高性能的开源替代品却付之阙如。为此，我们推出了 Baichuan-Omni，首个开源的 7B 多模态大型语言模型，能同时处理图像、视频、音频和文本，提供卓越的交互体验和强劲性能。我们设计了一套两阶段的多模态训练方案，从 7B 模型起步，通过多模态对齐和多任务微调，使模型能高效处理视觉与音频数据。在多项全模态和多模态测试中表现优异，我们期望 Baichuan-Omni 能成为开源社区在多模态理解和实时交互领域的有力基石。

> The salient multimodal capabilities and interactive experience of GPT-4o highlight its critical role in practical applications, yet it lacks a high-performing open-source counterpart. In this paper, we introduce Baichuan-Omni, the first open-source 7B Multimodal Large Language Model (MLLM) adept at concurrently processing and analyzing modalities of image, video, audio, and text, while delivering an advanced multimodal interactive experience and strong performance. We propose an effective multimodal training schema starting with 7B model and proceeding through two stages of multimodal alignment and multitask fine-tuning across audio, image, video, and text modal. This approach equips the language model with the ability to handle visual and audio data effectively. Demonstrating strong performance across various omni-modal and multimodal benchmarks, we aim for this contribution to serve as a competitive baseline for the open-source community in advancing multimodal understanding and real-time interaction.

[Arxiv](https://arxiv.org/abs/2410.08565)