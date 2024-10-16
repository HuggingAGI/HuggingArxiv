# VidCompress：通过内存增强的时间压缩技术，提升大型语言模型中的视频理解能力。

发布时间：2024年10月15日

`LLM应用` `视频处理` `人工智能`

> VidCompress: Memory-Enhanced Temporal Compression for Video Understanding in Large Language Models

# 摘要

> Video-LLMs 在视频理解方面潜力巨大，但多数模型将视频简化为帧序列，导致时间-空间交互不足，难以处理长视频。为此，我们推出 VidCompress，一种结合记忆增强时间压缩的 Video-LLM。VidCompress 通过双压缩器策略，一方面利用记忆增强压缩器捕捉视频的短期和长期关系，并通过多尺度变换器压缩视觉标记；另一方面，文本感知压缩器结合时间上下文生成浓缩视觉标记。实验证明，VidCompress 在复杂时间-空间关系建模上表现出色，大幅超越现有 Video-LLMs。

> Video-based multimodal large language models (Video-LLMs) possess significant potential for video understanding tasks. However, most Video-LLMs treat videos as a sequential set of individual frames, which results in insufficient temporal-spatial interaction that hinders fine-grained comprehension and difficulty in processing longer videos due to limited visual token capacity. To address these challenges, we propose VidCompress, a novel Video-LLM featuring memory-enhanced temporal compression. VidCompress employs a dual-compressor approach: a memory-enhanced compressor captures both short-term and long-term temporal relationships in videos and compresses the visual tokens using a multiscale transformer with a memory-cache mechanism, while a text-perceived compressor generates condensed visual tokens by utilizing Q-Former and integrating temporal contexts into query embeddings with cross attention. Experiments on several VideoQA datasets and comprehensive benchmarks demonstrate that VidCompress efficiently models complex temporal-spatial relations and significantly outperforms existing Video-LLMs.

[Arxiv](https://arxiv.org/abs/2410.11417)