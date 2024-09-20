# 视频-LLMs 插值：无需训练，实现更长序列 LMMs

发布时间：2024年09月19日

`LLM应用` `视频处理` `人工智能`

> Interpolating Video-LLMs: Toward Longer-sequence LMMs in a Training-free Manner

# 摘要

> 随着 LLM 技术的进步，整合视频模态的策略层出不穷。Video-LLMs 通过优化接口将视频编码器与 LLM 结合，成为关键方法。然而，计算与数据限制使得这些模型通常只能处理短视频，难以应对长视频内容。此外，微调模型以处理长视频成本高昂。因此，在无需训练的情况下探索 Video-LLMs 的插值变得尤为重要。本文首先指出插值 Video-LLMs 的两大挑战：固定编码器与投影仪限制了额外帧的整合，而 LLM 的内容长度限制则增加了处理复杂性。为此，我们提出 INTP-Video-LLMs 方法，通过视频令牌重排技术绕过固定限制，并采用无训练的 LLM 上下文扩展方法，使模型能够处理更多视觉令牌。

> Advancements in Large Language Models (LLMs) inspire various strategies for integrating video modalities. A key approach is Video-LLMs, which incorporate an optimizable interface linking sophisticated video encoders to LLMs. However, due to computation and data limitations, these Video-LLMs are typically pre-trained to process only short videos, limiting their broader application for understanding longer video content. Additionally, fine-tuning Video-LLMs to handle longer videos is cost-prohibitive. Consequently, it becomes essential to explore the interpolation of Video-LLMs under a completely training-free setting. In this paper, we first identify the primary challenges in interpolating Video-LLMs: (1) the video encoder and modality alignment projector are fixed, preventing the integration of additional frames into Video-LLMs, and (2) the LLM backbone is limited in its content length capabilities, which complicates the processing of an increased number of video tokens. To address these challenges, we propose a specific INTerPolation method for Video-LLMs (INTP-Video-LLMs). We introduce an alternative video token rearrangement technique that circumvents limitations imposed by the fixed video encoder and alignment projector. Furthermore, we introduce a training-free LLM context window extension method to enable Video-LLMs to understand a correspondingly increased number of visual tokens.

[Arxiv](https://arxiv.org/abs/2409.12963)