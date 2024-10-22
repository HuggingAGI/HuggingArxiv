# PAT：一款无需参数的音频与文本对齐工具，旨在提升零-shot 音频分类的性能。

发布时间：2024年10月19日

`LLM应用` `音频处理` `机器学习`

> PAT: Parameter-Free Audio-Text Aligner to Boost Zero-Shot Audio Classification

# 摘要

> 音频-语言模型 (ALM) 在零-shot 音频分类中表现出色。本文介绍的 PAT (无参数音频-文本对齐器)，是一种简单且无需训练的方法，旨在提升类似 CLAP 的 ALM 的零-shot 音频分类性能。我们通过增强音频和语言模态的表示，改善了跨模态交互。具体来说，我们提出了一种提示集合算法，自动选择并组合最相关的提示，并根据其与音频的相关性进行加权，以增强文本表示。同时，根据增强的文本信息重新加权帧级音频特征，以增强音频表示。PAT 无需额外模块或参数，可与任何现有类似 CLAP 的 ALM 结合使用，显著提升零-shot 音频分类性能。实验结果显示，PAT 在 18 个不同数据集和 6 个 ALM 上，性能提升幅度为 0.42%-27.0%。即使在音频受到噪声影响时，PAT 仍能保持稳健性能。代码将在接受后开源。

> Audio-Language Models (ALMs) have demonstrated remarkable performance in zero-shot audio classification. In this paper, we introduce PAT (Parameter-free Audio-Text aligner), a simple and training-free method aimed at boosting the zero-shot audio classification performance of CLAP-like ALMs. To achieve this, we propose to improve the cross-modal interaction between audio and language modalities by enhancing the representations for both modalities using mutual feedback. Precisely, to enhance textual representations, we propose a prompt ensemble algorithm that automatically selects and combines the most relevant prompts from a datastore with a large pool of handcrafted prompts and weighs them according to their relevance to the audio. On the other hand, to enhance audio representations, we reweigh the frame-level audio features based on the enhanced textual information. Our proposed method does not require any additional modules or parameters and can be used with any existing CLAP-like ALM to improve zero-shot audio classification performance. We experiment across 18 diverse benchmark datasets and 6 ALMs and show that the PAT outperforms vanilla zero-shot evaluation with significant margins of 0.42%-27.0%. Additionally, we demonstrate that PAT maintains robust performance even when input audio is degraded by varying levels of noise. Our code will be open-sourced upon acceptance.

[Arxiv](https://arxiv.org/abs/2410.15062)