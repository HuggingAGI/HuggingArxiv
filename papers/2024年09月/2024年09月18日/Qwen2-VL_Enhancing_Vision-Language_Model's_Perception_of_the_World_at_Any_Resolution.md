# Qwen2-VL：提升视觉-语言模型在任意分辨率下的世界感知能力

发布时间：2024年09月18日

`LLM应用` `计算机视觉` `人工智能`

> Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution

# 摘要

> 我们发布了 Qwen2-VL 系列，这是 Qwen-VL 的升级版，革新了视觉处理的传统固定分辨率方法。Qwen2-VL 采用朴素动态分辨率机制，能灵活处理不同分辨率的图像，生成更贴近人类感知的视觉表示。此外，模型融合了多模态旋转位置嵌入（M-RoPE），有效整合文本、图像和视频的位置信息。通过统一处理图像和视频，Qwen2-VL 大幅提升了视觉感知能力。我们还研究了大型视觉语言模型（LVLMs）的扩展规律，通过扩大模型规模（2B、8B 和 72B 参数版本）和训练数据量，Qwen2-VL 系列性能卓越。特别是 Qwen2-VL-72B 在多模态基准测试中表现出色，媲美 GPT-4o 和 Claude3.5-Sonnet，超越其他通用模型。代码已开源，详见 \url{https://github.com/QwenLM/Qwen2-VL}。

> We present the Qwen2-VL Series, an advanced upgrade of the previous Qwen-VL models that redefines the conventional predetermined-resolution approach in visual processing. Qwen2-VL introduces the Naive Dynamic Resolution mechanism, which enables the model to dynamically process images of varying resolutions into different numbers of visual tokens. This approach allows the model to generate more efficient and accurate visual representations, closely aligning with human perceptual processes. The model also integrates Multimodal Rotary Position Embedding (M-RoPE), facilitating the effective fusion of positional information across text, images, and videos. We employ a unified paradigm for processing both images and videos, enhancing the model's visual perception capabilities. To explore the potential of large multimodal models, Qwen2-VL investigates the scaling laws for large vision-language models (LVLMs). By scaling both the model size-with versions at 2B, 8B, and 72B parameters-and the amount of training data, the Qwen2-VL Series achieves highly competitive performance. Notably, the Qwen2-VL-72B model achieves results comparable to leading models such as GPT-4o and Claude3.5-Sonnet across various multimodal benchmarks, outperforming other generalist models. Code is available at \url{https://github.com/QwenLM/Qwen2-VL}.

[Arxiv](https://arxiv.org/abs/2409.12191)