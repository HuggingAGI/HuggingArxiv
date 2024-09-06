# TC-LLaVA：通过融入时间维度，重新审视从图像到视频理解的转变。

发布时间：2024年09月04日

`LLM应用` `视频处理` `人工智能`

> TC-LLaVA: Rethinking the Transfer from Image to Video Understanding with Temporal Considerations

# 摘要

> 多模态大型语言模型 (MLLM) 在图像-语言应用中的表现显著提升。近期，将图像预训练的 MLLM 应用于视频任务的研究兴趣日益浓厚。然而，多数研究集中在视觉编码器和投影器的改进，而大型语言模型 (LLM) 的核心部分仍未充分探索。本文提出两种策略，通过优化 LLM 的层间注意力计算，提升模型在视频理解任务中的表现。首先，我们通过时间感知双旋转位置嵌入 (Temporal-Aware Dual RoPE) 增强旋转位置嵌入 (RoPE)，引入时间信息，强化 MLLM 的时间建模能力，同时保持视觉和文本令牌的相对位置关系。其次，采用帧级块因果注意力掩码 (Frame-wise Block Causal Attention Mask)，扩大视频帧内外的视觉令牌交互，同时维持因果推理机制。基于这些方法，我们将 LLaVA 适应于视频理解任务，命名为时间考虑的 LLaVA (TC-LLaVA)。TC-LLaVA 在视频理解基准上通过监督微调 (SFT) 实现了新的最先进性能。

> Multimodal Large Language Models (MLLMs) have significantly improved performance across various image-language applications. Recently, there has been a growing interest in adapting image pre-trained MLLMs for video-related tasks. However, most efforts concentrate on enhancing the vision encoder and projector components, while the core part, Large Language Models (LLMs), remains comparatively under-explored. In this paper, we propose two strategies to enhance the model's capability in video understanding tasks by improving inter-layer attention computation in LLMs. Specifically, the first approach focuses on the enhancement of Rotary Position Embedding (RoPE) with Temporal-Aware Dual RoPE, which introduces temporal position information to strengthen the MLLM's temporal modeling capabilities while preserving the relative position relationships of both visual and text tokens. The second approach involves enhancing the Attention Mask with the Frame-wise Block Causal Attention Mask, a simple yet effective method that broadens visual token interactions within and across video frames while maintaining the causal inference mechanism. Based on these proposed methods, we adapt LLaVA for video understanding tasks, naming it Temporal-Considered LLaVA (TC-LLaVA). Our TC-LLaVA achieves new state-of-the-art performance across various video understanding benchmarks with only supervised fine-tuning (SFT) on video-related datasets.

[Arxiv](https://arxiv.org/abs/2409.03206)