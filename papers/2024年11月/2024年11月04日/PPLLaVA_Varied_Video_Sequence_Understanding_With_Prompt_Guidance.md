# PPLLaVA：具有提示指导的各种视频序列理解

发布时间：2024年11月04日

`LLM应用` `语言模型`

> PPLLaVA: Varied Video Sequence Understanding With Prompt Guidance

# 摘要

> 过去一年见证了基于视频的大型语言模型的显著进步。然而，开发一个既能理解短视频又能理解长视频的统一模型的挑战仍未解决。大多数现有的视频大型语言模型无法处理长达一小时的视频，而专为长视频定制的方法对于较短的视频和图像往往效果不佳。在本文中，我们认为关键问题在于视频中的冗余内容。为了解决这个问题，我们提出了一种新颖的池化策略，同时实现了令牌压缩和指令感知的视觉特征聚合。我们的模型被称为提示引导池化 LLaVA，简称 PPLLaVA。具体来说，PPLLaVA 由三个核心组件组成：基于 CLIP 的视觉提示对齐，用于提取与用户指令相关的视觉信息；提示引导池化，使用卷积式池化将视觉序列压缩到任意规模；以及为视觉对话中常见的冗长提示设计的剪辑上下文扩展。此外，我们的代码库还集成了最先进的视频直接偏好优化（DPO）和视觉交错训练。大量实验验证了我们模型的性能。凭借出色的吞吐量和仅 1024 个视觉上下文，PPLLaVA 作为视频大型语言模型在图像基准测试中取得了更好的结果，同时在各种视频基准测试中达到了最先进的性能，在从字幕生成到多项选择题等任务中表现出色，并且能够处理从几秒到数小时的视频长度。代码已在 https://github.com/farewellthree/PPLLaVA 上可用。

> The past year has witnessed the significant advancement of video-based large language models. However, the challenge of developing a unified model for both short and long video understanding remains unresolved. Most existing video LLMs cannot handle hour-long videos, while methods custom for long videos tend to be ineffective for shorter videos and images. In this paper, we identify the key issue as the redundant content in videos. To address this, we propose a novel pooling strategy that simultaneously achieves token compression and instruction-aware visual feature aggregation. Our model is termed Prompt-guided Pooling LLaVA, or PPLLaVA for short. Specifically, PPLLaVA consists of three core components: the CLIP-based visual-prompt alignment that extracts visual information relevant to the user's instructions, the prompt-guided pooling that compresses the visual sequence to arbitrary scales using convolution-style pooling, and the clip context extension designed for lengthy prompt common in visual dialogue. Moreover, our codebase also integrates the most advanced video Direct Preference Optimization (DPO) and visual interleave training. Extensive experiments have validated the performance of our model. With superior throughput and only 1024 visual context, PPLLaVA achieves better results on image benchmarks as a video LLM, while achieving state-of-the-art performance across various video benchmarks, excelling in tasks ranging from caption generation to multiple-choice questions, and handling video lengths from seconds to hours. Codes have been available at https://github.com/farewellthree/PPLLaVA.

[Arxiv](https://arxiv.org/abs/2411.02327)