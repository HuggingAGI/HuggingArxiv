# MicroEmo 技术：通过捕捉视频对话中的微表情动态，实现时间敏感的多模态情感识别。

发布时间：2024年07月23日

`LLM应用` `情感识别` `视频分析`

> MicroEmo: Time-Sensitive Multimodal Emotion Recognition with Micro-Expression Dynamics in Video Dialogues

# 摘要

> 多模态大型语言模型 (MLLMs) 在整合视频中的视觉、声学和语言线索方面表现出色，有效识别人类情感。然而，现有技术未能充分捕捉微表情的动态面部细节，也未充分利用视频中话语段落的上下文关系，限制了其性能。为此，我们设计了 MicroEmo，一种专注于微表情动态和话语上下文依赖的 MLLM。该模型创新性地结合了全局与局部视觉特征，并通过话语感知机制深化了多尺度上下文理解。初步实验显示，在新的可解释多模态情感识别任务中，MicroEmo 相较于现有技术展现了更佳的情感预测能力。

> Multimodal Large Language Models (MLLMs) have demonstrated remarkable multimodal emotion recognition capabilities, integrating multimodal cues from visual, acoustic, and linguistic contexts in the video to recognize human emotional states. However, existing methods ignore capturing local facial features of temporal dynamics of micro-expressions and do not leverage the contextual dependencies of the utterance-aware temporal segments in the video, thereby limiting their expected effectiveness to a certain extent. In this work, we propose MicroEmo, a time-sensitive MLLM aimed at directing attention to the local facial micro-expression dynamics and the contextual dependencies of utterance-aware video clips. Our model incorporates two key architectural contributions: (1) a global-local attention visual encoder that integrates global frame-level timestamp-bound image features with local facial features of temporal dynamics of micro-expressions; (2) an utterance-aware video Q-Former that captures multi-scale and contextual dependencies by generating visual token sequences for each utterance segment and for the entire video then combining them. Preliminary qualitative experiments demonstrate that in a new Explainable Multimodal Emotion Recognition (EMER) task that exploits multi-modal and multi-faceted clues to predict emotions in an open-vocabulary (OV) manner, MicroEmo demonstrates its effectiveness compared with the latest methods.

[Arxiv](https://arxiv.org/abs/2407.16552)