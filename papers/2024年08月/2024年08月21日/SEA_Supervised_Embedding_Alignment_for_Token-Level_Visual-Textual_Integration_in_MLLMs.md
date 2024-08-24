# SEA：多模态大型语言模型中标记级视觉与文本整合的监督嵌入对齐技术

发布时间：2024年08月21日

`LLM应用` `人工智能` `计算机视觉`

> SEA: Supervised Embedding Alignment for Token-Level Visual-Textual Integration in MLLMs

# 摘要

> 多模态大型语言模型 (MLLMs) 近期在感知和推理方面表现出色，通常由视觉编码器、适配器和大型语言模型 (LLM) 组成。适配器在视觉与语言之间起着关键桥梁作用。然而，图像级监督训练常导致适配器与 LLM 之间严重不对齐，限制了多模态 LLM 的潜力。为此，我们提出监督嵌入对齐 (SEA)，利用 CLIP 等预训练模型通过对比学习实现视觉令牌与 LLM 嵌入空间的对齐。SEA 确保了视觉与语言表示的更紧密结合，提升了多模态 LLM 的性能与可解释性，同时保留其固有能力。实验证明，SEA 对 MLLMs 尤其是小型模型有显著改进，且无需额外数据或计算。SEA 还为开发更通用、适应性强的多模态系统增强方案奠定了基础。

> Multimodal Large Language Models (MLLMs) have recently demonstrated remarkable perceptual and reasoning abilities, typically comprising a Vision Encoder, an Adapter, and a Large Language Model (LLM). The adapter serves as the critical bridge between the visual and language components. However, training adapters with image-level supervision often results in significant misalignment, undermining the LLMs' capabilities and limiting the potential of Multimodal LLMs. To address this, we introduce Supervised Embedding Alignment (SEA), a token-level alignment method that leverages vision-language pre-trained models, such as CLIP, to align visual tokens with the LLM's embedding space through contrastive learning. This approach ensures a more coherent integration of visual and language representations, enhancing the performance and interpretability of multimodal LLMs while preserving their inherent capabilities. Extensive experiments show that SEA effectively improves MLLMs, particularly for smaller models, without adding extra data or inference computation. SEA also lays the groundwork for developing more general and adaptable solutions to enhance multimodal systems.

[Arxiv](https://arxiv.org/abs/2408.11813)