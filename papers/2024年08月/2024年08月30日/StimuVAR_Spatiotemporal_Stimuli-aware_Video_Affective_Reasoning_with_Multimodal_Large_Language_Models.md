# StimuVAR：结合多模态大型语言模型，实现对视频中时空感知刺激的情感推理

发布时间：2024年08月30日

`LLM应用` `社交智能` `视频分析`

> StimuVAR: Spatiotemporal Stimuli-aware Video Affective Reasoning with Multimodal Large Language Models

# 摘要

> 预测视频如何触动人心，对构建社交智能系统至关重要。多模态大型语言模型（MLLMs）虽擅长视频理解，却常忽略情感层面。为此，我们推出StimuVAR框架，专为MLLMs设计，聚焦视频情感推理。该框架通过帧级与令牌级双重感知，精准捕捉情感触发点，并借助VAR指令数据，强化模型情感推理能力。实验证明，StimuVAR不仅能深入解读观众情感，还能提供富有洞见的解释，引领视频情感分析新潮流。

> Predicting and reasoning how a video would make a human feel is crucial for developing socially intelligent systems. Although Multimodal Large Language Models (MLLMs) have shown impressive video understanding capabilities, they tend to focus more on the semantic content of videos, often overlooking emotional stimuli. Hence, most existing MLLMs fall short in estimating viewers' emotional reactions and providing plausible explanations. To address this issue, we propose StimuVAR, a spatiotemporal Stimuli-aware framework for Video Affective Reasoning (VAR) with MLLMs. StimuVAR incorporates a two-level stimuli-aware mechanism: frame-level awareness and token-level awareness. Frame-level awareness involves sampling video frames with events that are most likely to evoke viewers' emotions. Token-level awareness performs tube selection in the token space to make the MLLM concentrate on emotion-triggered spatiotemporal regions. Furthermore, we create VAR instruction data to perform affective training, steering MLLMs' reasoning strengths towards emotional focus and thereby enhancing their affective reasoning ability. To thoroughly assess the effectiveness of VAR, we provide a comprehensive evaluation protocol with extensive metrics. StimuVAR is the first MLLM-based method for viewer-centered VAR. Experiments demonstrate its superiority in understanding viewers' emotional responses to videos and providing coherent and insightful explanations.

[Arxiv](https://arxiv.org/abs/2409.00304)