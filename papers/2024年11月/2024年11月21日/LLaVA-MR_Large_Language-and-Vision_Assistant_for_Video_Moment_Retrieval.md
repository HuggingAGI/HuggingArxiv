# LLaVA-MR：用于视频时刻检索的大型语言与视觉助手

发布时间：2024年11月21日

`LLM应用` `语言模型`

> LLaVA-MR: Large Language-and-Vision Assistant for Video Moment Retrieval

# 摘要

> 多模态大型语言模型（MLLMs）在视觉感知、理解与推理方面应用广泛。但因大型语言模型的上下文规模有限以及帧提取粗糙，长视频处理和精确的时刻检索仍困难重重。我们推出了用于时刻检索的大型语言和视觉助手（LLaVA-MR），借助 MLLMs 可在视频中实现精准的时刻检索和上下文定位。LLaVA-MR 融合了用于时空特征提取的密集帧和时间编码（DFTE）、用于捕捉简短视觉和运动模式的信息帧选择（IFS）以及用于应对 LLM 上下文限制的动态令牌压缩（DTC）。在 Charades-STA 和 QVHighlights 等基准测试中的评估显示，LLaVA-MR 胜过 11 种前沿方法，在 QVHighlights 数据集上，R1@0.5 提升了 1.82％，mAP@0.5 提升了 1.29％。我们的实现一经接受将会开源。

> Multimodal Large Language Models (MLLMs) are widely used for visual perception, understanding, and reasoning. However, long video processing and precise moment retrieval remain challenging due to LLMs' limited context size and coarse frame extraction. We propose the Large Language-and-Vision Assistant for Moment Retrieval (LLaVA-MR), which enables accurate moment retrieval and contextual grounding in videos using MLLMs. LLaVA-MR combines Dense Frame and Time Encoding (DFTE) for spatial-temporal feature extraction, Informative Frame Selection (IFS) for capturing brief visual and motion patterns, and Dynamic Token Compression (DTC) to manage LLM context limitations. Evaluations on benchmarks like Charades-STA and QVHighlights demonstrate that LLaVA-MR outperforms 11 state-of-the-art methods, achieving an improvement of 1.82% in R1@0.5 and 1.29% in mAP@0.5 on the QVHighlights dataset. Our implementation will be open-sourced upon acceptance.

[Arxiv](https://arxiv.org/abs/2411.14505)