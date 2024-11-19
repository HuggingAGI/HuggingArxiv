# ViBe：用于评估大型多模态模型幻觉情况的文本到视频基准

发布时间：2024年11月16日

`LLM应用` `多模态模型`

> ViBe: A Text-to-Video Benchmark for Evaluating Hallucination in Large Multimodal Models

# 摘要

> 大型多模态模型（LMMs）的最新进展使其具备了视频理解的能力。具体而言，文本到视频（T2V）模型在质量、理解能力和时长方面进步显著，能够依据简单的文本提示生成视频。不过，它们仍时常产出幻觉内容，让人一眼就能看出是 AI 生成的视频。我们推出了 ViBe：一个针对 T2V 模型所生成幻觉视频的大规模基准。我们明确了五种主要的幻觉类型，即主体消失、数字变异、时间畸形、遗漏错误和物理不一致。借助 10 个开源的 T2V 模型，我们构建了首个大规模的幻觉视频数据集，其中包含 3782 个由人类标注为这五类的视频。ViBe 为评估 T2V 模型的可靠性提供了独特资源，也为改进视频生成中的幻觉检测与缓解奠定了基础。我们将分类设定为基线，并展示了多种集成分类器配置，其中 TimeSFormer + CNN 的组合表现最佳，准确率达 0.345，F1 分数为 0.342。此基准旨在推动开发更强大的 T2V 模型，使其生成的视频能更精准地契合输入提示。

> Latest developments in Large Multimodal Models (LMMs) have broadened their capabilities to include video understanding. Specifically, Text-to-video (T2V) models have made significant progress in quality, comprehension, and duration, excelling at creating videos from simple textual prompts. Yet, they still frequently produce hallucinated content that clearly signals the video is AI-generated. We introduce ViBe: a large-scale Text-to-Video Benchmark of hallucinated videos from T2V models. We identify five major types of hallucination: Vanishing Subject, Numeric Variability, Temporal Dysmorphia, Omission Error, and Physical Incongruity. Using 10 open-source T2V models, we developed the first large-scale dataset of hallucinated videos, comprising 3,782 videos annotated by humans into these five categories. ViBe offers a unique resource for evaluating the reliability of T2V models and provides a foundation for improving hallucination detection and mitigation in video generation. We establish classification as a baseline and present various ensemble classifier configurations, with the TimeSFormer + CNN combination yielding the best performance, achieving 0.345 accuracy and 0.342 F1 score. This benchmark aims to drive the development of robust T2V models that produce videos more accurately aligned with input prompts.

[Arxiv](https://arxiv.org/abs/2411.10867)