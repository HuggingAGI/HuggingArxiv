# OmniBench：开启通用全语言模型的新纪元

发布时间：2024年09月23日

`LLM应用` `人工智能` `多模态数据处理`

> OmniBench: Towards The Future of Universal Omni-Language Models

# 摘要

> 多模态大型语言模型 (MLLM) 的最新进展旨在整合和解释跨不同模态的数据。然而，这些模型同时处理和推理多种模态的能力仍然不足，部分原因是缺乏全面的模态基准。我们引入了 OmniBench，这是一个新颖的基准，旨在严格评估模型识别、解释和跨视觉、声学和文本输入同时推理的能力。我们将能够进行这种三模态处理的模型定义为全语言模型 (OLM)。OmniBench 的特点是高质量的人工标注，确保准确响应需要跨所有三种模态的综合理解和推理。我们的主要发现揭示了：i) 开源 OLMs 在三模态上下文中的指令跟随和推理能力方面存在关键限制；ii) 即使提供了图像和音频的替代文本表示，基线模型的表现也很差（低于 50% 的准确率）。这些结果表明，从文本、图像和音频构建一致上下文的能力在现有的 MLLM 训练范式中经常被忽视。我们主张未来的研究应专注于开发更强大的三模态整合技术和训练策略，以提高 OLM 在不同模态中的性能。代码和实时排行榜可以在 https://m-a-p.ai/OmniBench 找到。

> Recent advancements in multimodal large language models (MLLMs) have aimed to integrate and interpret data across diverse modalities. However, the capacity of these models to concurrently process and reason about multiple modalities remains inadequately explored, partly due to the lack of comprehensive modality-wise benchmarks. We introduce OmniBench, a novel benchmark designed to rigorously evaluate models' ability to recognize, interpret, and reason across visual, acoustic, and textual inputs simultaneously. We define models capable of such tri-modal processing as omni-language models (OLMs). OmniBench is distinguished by high-quality human annotations, ensuring that accurate responses require integrated understanding and reasoning across all three modalities. Our main findings reveal that: i) open-source OLMs exhibit critical limitations in instruction-following and reasoning capabilities within tri-modal contexts; and ii) the baseline models perform poorly (below 50% accuracy) even when provided with alternative textual representations of images and audio. These results suggest that the ability to construct a consistent context from text, image, and audio is often overlooked in existing MLLM training paradigms. We advocate for future research to focus on developing more robust tri-modal integration techniques and training strategies to enhance OLM performance across diverse modalities. The codes and live leaderboard could be found at https://m-a-p.ai/OmniBench.

[Arxiv](https://arxiv.org/abs/2409.15272)