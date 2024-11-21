# Video-RAG：视觉对齐的检索增强式长视频理解

发布时间：2024年11月20日

`RAG` `跨模态`

> Video-RAG: Visually-aligned Retrieval-Augmented Long Video Comprehension

# 摘要

> 现有的大型视频语言模型（LVLMs）因上下文受限，难以准确理解长视频。为化解此难题，对长上下文的 LVLMs 进行微调以及运用基于 GPT 的代理已成为颇具前景的解决之策。然而，微调 LVLMs 需大量优质数据和众多 GPU 资源，而基于 GPT 的代理则依赖专有模型（如 GPT-4o）。在本文中，我们提出了视频检索增强生成（Video-RAG），这是一种无需训练且经济高效的流程，它借助视觉对齐的辅助文本，助力促进跨模态对齐，同时提供超越视觉内容的额外信息。具体来说，我们利用开源的外部工具从纯视频数据（比如音频、光学字符和对象检测）中提取视觉对齐的信息，并以即插即用的方式将提取的信息作为辅助文本与视频帧和查询一道纳入现有的 LVLM 中。我们的 Video-RAG 有几大关键优势：（一）因单轮检索，计算开销小，轻巧便捷；（二）易于实现，与任何 LVLM 兼容；（三）在包括 Video-MME、MLVU 和 LongVideoBench 在内的长视频理解基准测试中，性能显著且持续提升。值得一提的是，当与 72B 模型配合使用时，我们的模型性能优于 Gemini-1.5-Pro 和 GPT-4o 等专有模型。

> Existing large video-language models (LVLMs) struggle to comprehend long videos correctly due to limited context. To address this problem, fine-tuning long-context LVLMs and employing GPT-based agents have emerged as promising solutions. However, fine-tuning LVLMs would require extensive high-quality data and substantial GPU resources, while GPT-based agents would rely on proprietary models (e.g., GPT-4o). In this paper, we propose Video Retrieval-Augmented Generation (Video-RAG), a training-free and cost-effective pipeline that employs visually-aligned auxiliary texts to help facilitate cross-modality alignment while providing additional information beyond the visual content. Specifically, we leverage open-source external tools to extract visually-aligned information from pure video data (e.g., audio, optical character, and object detection), and incorporate the extracted information into an existing LVLM as auxiliary texts, alongside video frames and queries, in a plug-and-play manner. Our Video-RAG offers several key advantages: (i) lightweight with low computing overhead due to single-turn retrieval; (ii) easy implementation and compatibility with any LVLM; and (iii) significant, consistent performance gains across long video understanding benchmarks, including Video-MME, MLVU, and LongVideoBench. Notably, our model demonstrates superior performance over proprietary models like Gemini-1.5-Pro and GPT-4o when utilized with a 72B model.

[Arxiv](https://arxiv.org/abs/2411.13093)