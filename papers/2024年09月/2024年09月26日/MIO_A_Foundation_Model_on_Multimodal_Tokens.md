# MIO：多模态令牌的基础模型

发布时间：2024年09月26日

`LLM应用` `人工智能` `多模态学习`

> MIO: A Foundation Model on Multimodal Tokens

# 摘要

> 本文介绍的 MIO 是一种基于多模态标记的新型基础模型，能端到端、自回归地理解和生成语音、文本、图像和视频。尽管 LLM 和 MM-LLM 通过多功能性推动了 AGI 的进步，但仍缺乏真正的任意到任意理解和生成能力。GPT-4o 展示了任意到任意 LLM 在复杂任务中的潜力，支持全方位多模态输入输出，但它是闭源的，不支持多模态交错序列生成。为此，我们提出了 MIO，它通过因果多模态建模在四种模态的混合离散标记上训练。MIO 经历了四个阶段的训练：对齐预训练、交错预训练、语音增强预训练和综合监督微调。实验结果显示，MIO 在性能上与双模态基线、任意到任意模型基线和特定模态基线相比，表现出色，甚至在某些情况下更优。此外，MIO 展示了其任意到任意特性所固有的高级能力，如交错视频-文本生成、视觉思维链推理、视觉指南生成和指导性图像编辑等。

> In this paper, we introduce MIO, a novel foundation model built on multimodal tokens, capable of understanding and generating speech, text, images, and videos in an end-to-end, autoregressive manner. While the emergence of large language models (LLMs) and multimodal large language models (MM-LLMs) propels advancements in artificial general intelligence through their versatile capabilities, they still lack true any-to-any understanding and generation. Recently, the release of GPT-4o has showcased the remarkable potential of any-to-any LLMs for complex real-world tasks, enabling omnidirectional input and output across images, speech, and text. However, it is closed-source and does not support the generation of multimodal interleaved sequences. To address this gap, we present MIO, which is trained on a mixture of discrete tokens across four modalities using causal multimodal modeling. MIO undergoes a four-stage training process: (1) alignment pre-training, (2) interleaved pre-training, (3) speech-enhanced pre-training, and (4) comprehensive supervised fine-tuning on diverse textual, visual, and speech tasks. Our experimental results indicate that MIO exhibits competitive, and in some cases superior, performance compared to previous dual-modal baselines, any-to-any model baselines, and even modality-specific baselines. Moreover, MIO demonstrates advanced capabilities inherent to its any-to-any feature, such as interleaved video-text generation, chain-of-visual-thought reasoning, visual guideline generation, instructional image editing, etc.

[Arxiv](https://arxiv.org/abs/2409.17692)