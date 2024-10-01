# VideoINSTA：借助 LLM 的时空推理能力，实现零-shot 长视频理解

发布时间：2024年09月30日

`LLM应用` `视频分析` `人工智能`

> VideoINSTA: Zero-shot Long Video Understanding via Informative Spatial-Temporal Reasoning with LLMs

# 摘要

> 在视频与语言的交叉领域，利用零-shot 大型语言模型（LLM）进行视频理解的新方法，正逐渐超越传统的端到端模型。然而，长视频理解因其跨越长时间段的复杂推理，对零-shot LLM 方法提出了特殊挑战。长视频中的信息冗余问题，促使我们思考：LLM 需要哪些关键信息，以及如何利用这些信息进行复杂的时空推理？为此，我们推出了 VideoINSTA 框架，即 INformative Spatial-TemporAl Reasoning，专为零-shot 长视频理解设计。VideoINSTA 不仅构建了一个基于 LLM 的长视频理解零-shot 框架，还引入了基于事件的时间推理和基于内容的空间推理方法，使 LLM 能够有效处理视频中的时空信息。此外，我们还设计了一种自反信息推理方案，通过平衡信息充分性和预测信心来优化时间因素。实验证明，VideoINSTA 在 EgoSchema、NextQA、IntentQA 和 ActivityNetQA 等多个长视频问答基准上，均取得了显著的性能提升。代码现已公开，详见：https://github.com/mayhugotong/VideoINSTA。

> In the video-language domain, recent works in leveraging zero-shot Large Language Model-based reasoning for video understanding have become competitive challengers to previous end-to-end models. However, long video understanding presents unique challenges due to the complexity of reasoning over extended timespans, even for zero-shot LLM-based approaches. The challenge of information redundancy in long videos prompts the question of what specific information is essential for large language models (LLMs) and how to leverage them for complex spatial-temporal reasoning in long-form video analysis. We propose a framework VideoINSTA, i.e. INformative Spatial-TemporAl Reasoning for zero-shot long-form video understanding. VideoINSTA contributes (1) a zero-shot framework for long video understanding using LLMs; (2) an event-based temporal reasoning and content-based spatial reasoning approach for LLMs to reason over spatial-temporal information in videos; (3) a self-reflective information reasoning scheme balancing temporal factors based on information sufficiency and prediction confidence. Our model significantly improves the state-of-the-art on three long video question-answering benchmarks: EgoSchema, NextQA, and IntentQA, and the open question answering dataset ActivityNetQA. The code is released here: https://github.com/mayhugotong/VideoINSTA.

[Arxiv](https://arxiv.org/abs/2409.20365)