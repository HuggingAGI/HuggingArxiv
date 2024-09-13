# WhisperNER：融合开放命名实体与语音识别的统一平台

发布时间：2024年09月12日

`LLM应用` `语音识别`

> WhisperNER: Unified Open Named Entity and Speech Recognition

# 摘要

> 结合 NER 与 ASR 能大幅提升转录质量。本文介绍的 WhisperNER 模型，不仅能转录音频，还能识别其中的实体。WhisperNER 支持开放式 NER，能灵活应对各种实体变化。我们利用合成语音扩充数据集，训练模型在转录时自动标记实体。为验证效果，我们生成了合成语音并注释了现有数据集。实验显示，WhisperNER 在开放 NER 和微调任务中均表现优异。

> Integrating named entity recognition (NER) with automatic speech recognition (ASR) can significantly enhance transcription accuracy and informativeness. In this paper, we introduce WhisperNER, a novel model that allows joint speech transcription and entity recognition. WhisperNER supports open-type NER, enabling recognition of diverse and evolving entities at inference. Building on recent advancements in open NER research, we augment a large synthetic dataset with synthetic speech samples. This allows us to train WhisperNER on a large number of examples with diverse NER tags. During training, the model is prompted with NER labels and optimized to output the transcribed utterance along with the corresponding tagged entities. To evaluate WhisperNER, we generate synthetic speech for commonly used NER benchmarks and annotate existing ASR datasets with open NER tags. Our experiments demonstrate that WhisperNER outperforms natural baselines on both out-of-domain open type NER and supervised finetuning.

[Arxiv](https://arxiv.org/abs/2409.08107)