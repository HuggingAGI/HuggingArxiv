# SF-Speech：小规模数据集上的零-shot 语音克隆直流技术

发布时间：2024年10月16日

`LLM应用` `语音技术` `人工智能`

> SF-Speech: Straightened Flow for Zero-Shot Voice Clone on Small-Scale Dataset

# 摘要

> 大规模语音生成模型在零-shot 语音克隆任务中表现出色，但如何用小数据集实现同样效果也值得探索。本文介绍的 SF-Speech 模型，结合常微分方程与上下文学习，通过多阶段生成策略优化声学特征，显著提升语音克隆效果。经过不到 1000 小时训练，SF-Speech 超越了依赖全局嵌入或大型语言模型的方法。在参数相近时，SF-Speech 在语音清晰度和音色相似度上均优于顶尖的 VoiceBox 模型，甚至在 VoiceBox 参数翻倍时仍保持优势。

> Large-scale speech generation models have achieved impressive performance in the zero-shot voice clone tasks relying on large-scale datasets. However, exploring how to achieve zero-shot voice clone with small-scale datasets is also essential. This paper proposes SF-Speech, a novel state-of-the-art voice clone model based on ordinary differential equations and contextual learning. Unlike the previous works, SF-Speech employs a multi-stage generation strategy to obtain the coarse acoustic feature and utilizes this feature to straighten the curved reverse trajectories caused by training the ordinary differential equation model with flow matching. In addition, we find the difference between the local correlations of different types of acoustic features and demonstrate the potential role of 2D convolution in modeling mel-spectrogram features. After training with less than 1000 hours of speech, SF-Speech significantly outperforms those methods based on global speaker embedding or autoregressive large language models. In particular, SF-Speech also shows a significant advantage over VoiceBox, the best-performing ordinary differential equation model, in speech intelligibility (a relative decrease of 22.4\% on word error rate) and timbre similarity (a relative improvement of 5.6\% on cosine distance) at a similar scale of parameters, and even keep a slight advantage when the parameters of VoiceBox are tripled.

[Arxiv](https://arxiv.org/abs/2410.12399)