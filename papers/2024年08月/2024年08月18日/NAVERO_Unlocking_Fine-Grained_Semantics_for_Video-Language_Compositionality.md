# NAVERO：揭秘视频与语言组合中的细粒度语义奥秘

发布时间：2024年08月18日

`LLM应用` `视频处理` `人工智能`

> NAVERO: Unlocking Fine-Grained Semantics for Video-Language Compositionality

# 摘要

> 我们探索了视频-语言模型在理解视频中对象、属性、动作及其关系的组合能力。由于视频中的组合关系随时间快速变化，这一任务尤为挑战。为此，我们创建了 AARO 基准，通过生成带有错误动作描述的负样本来评估模型对空间概念上动作组合的理解。同时，我们提出了 NAVERO 训练法，利用负增强的视频-文本数据提升组合理解，并设计了负增强视觉-语言匹配损失以优化模型。实验表明，NAVERO 在组合理解和视频-文本检索方面均显著超越现有技术，且在传统文本-视频检索任务中表现出色。

> We study the capability of Video-Language (VidL) models in understanding compositions between objects, attributes, actions and their relations. Composition understanding becomes particularly challenging for video data since the compositional relations rapidly change over time in videos. We first build a benchmark named AARO to evaluate composition understanding related to actions on top of spatial concepts. The benchmark is constructed by generating negative texts with incorrect action descriptions for a given video and the model is expected to pair a positive text with its corresponding video. Furthermore, we propose a training method called NAVERO which utilizes video-text data augmented with negative texts to enhance composition understanding. We also develop a negative-augmented visual-language matching loss which is used explicitly to benefit from the generated negative text. We compare NAVERO with other state-of-the-art methods in terms of compositional understanding as well as video-text retrieval performance. NAVERO achieves significant improvement over other methods for both video-language and image-language composition understanding, while maintaining strong performance on traditional text-video retrieval tasks.

[Arxiv](https://arxiv.org/abs/2408.09511)