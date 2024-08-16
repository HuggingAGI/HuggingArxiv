# 视频编码与多模态大型语言模型的邂逅：开创统一视频编码新范式

发布时间：2024年08月15日

`LLM应用` `视频压缩` `多媒体`

> When Video Coding Meets Multimodal Large Language Models: A Unified Paradigm for Video Coding

# 摘要

> 当前的编解码器旨在消除视频的内在冗余，以实现压缩。然而，多模态大型语言模型（MLLMs）的外部先验在视频压缩领域尚未深入探索。为此，我们提出了一种创新的跨模态视频编码（CMVC）方法，该方法首次尝试在视频编码中融合多模态表示和视频生成技术。在编码阶段，视频被分解为空间内容和运动元素，并通过MLLMs转换为不同模态，以实现高度紧凑的表示。解码时，结合先前编码的元素和视频生成模型，我们设计了多种编码-解码模式，以满足不同的解码需求，如确保高质量语义重建的TT2V模式和追求卓越感知一致性的IT2V模式。此外，我们通过LoRA调整开发了一个高效的帧插值模型，用于IT2V模式，确保了生成的运动提示流畅且感知质量高。实验结果显示，TT2V有效重建了语义信息，而IT2V则展现了出色的感知一致性，为视频编码的未来研究指明了方向。

> Existing codecs are designed to eliminate intrinsic redundancies to create a compact representation for compression. However, strong external priors from Multimodal Large Language Models (MLLMs) have not been explicitly explored in video compression. Herein, we introduce a unified paradigm for Cross-Modality Video Coding (CMVC), which is a pioneering approach to explore multimodality representation and video generative models in video coding. Specifically, on the encoder side, we disentangle a video into spatial content and motion components, which are subsequently transformed into distinct modalities to achieve very compact representation by leveraging MLLMs. During decoding, previously encoded components and video generation models are leveraged to create multiple encoding-decoding modes that optimize video reconstruction quality for specific decoding requirements, including Text-Text-to-Video (TT2V) mode to ensure high-quality semantic information and Image-Text-to-Video (IT2V) mode to achieve superb perceptual consistency. In addition, we propose an efficient frame interpolation model for IT2V mode via Low-Rank Adaption (LoRA) tuning to guarantee perceptual quality, which allows the generated motion cues to behave smoothly. Experiments on benchmarks indicate that TT2V achieves effective semantic reconstruction, while IT2V exhibits competitive perceptual consistency. These results highlight potential directions for future research in video coding.

[Arxiv](https://arxiv.org/abs/2408.08093)