# 通过视听训练，旨在提升视频-文本大型语言模型中的基础能力。

发布时间：2024年07月20日

`LLM应用` `视频处理` `音频处理`

> Audio-visual training for improved grounding in video-text LLMs

# 摘要

> 随着多模态 LLM 的最新进展，针对关键视频任务的视频-文本模型应运而生。然而，多数现有模型仅处理视觉信息，忽略了音频。即便有少数模型兼顾音频与视觉，也未专门针对音频数据进行训练。鉴于此，我们设计了一种能明确处理音视频输入的模型架构，并利用视频指令数据集中的音视频数据进行训练。对比仅视觉模型和其他音视频模型，我们的模型在音频数据训练下，响应定位能力显著提升。为更全面评估音视频模型，我们同时发布了一个包含音频感知问答对的人工标注基准数据集。

> Recent advances in multimodal LLMs, have led to several video-text models being proposed for critical video-related tasks. However, most of the previous works support visual input only, essentially muting the audio signal in the video. Few models that support both audio and visual input, are not explicitly trained on audio data. Hence, the effect of audio towards video understanding is largely unexplored. To this end, we propose a model architecture that handles audio-visual inputs explicitly. We train our model with both audio and visual data from a video instruction-tuning dataset. Comparison with vision-only baselines, and other audio-visual models showcase that training on audio data indeed leads to improved grounding of responses. For better evaluation of audio-visual models, we also release a human-annotated benchmark dataset, with audio-aware question-answer pairs.

![通过视听训练，旨在提升视频-文本大型语言模型中的基础能力。](../../../paper_images/2407.15046/chat.png)

![通过视听训练，旨在提升视频-文本大型语言模型中的基础能力。](../../../paper_images/2407.15046/model.png)

[Arxiv](https://arxiv.org/abs/2407.15046)