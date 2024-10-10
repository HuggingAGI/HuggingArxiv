# 探索因素偏好，优化人机对齐

发布时间：2024年10月09日

`LLM理论` `人工智能`

> Uncovering Factor Level Preferences to Improve Human-Model Alignment

# 摘要

> 尽管 LLM 对齐技术有所进步，但理解其偏好背后的原因仍至关重要。LLM 常表现出与人类偏好不符的偏见，如偏好特定写作风格或产生冗长输出。当前评估方法缺乏可解释性，依赖粗粒度比较。为此，我们推出 PROFILE 框架，揭示并量化驱动偏好的特定因素。PROFILE 通过因素级分析，解释了人类与模型对齐或未对齐的原因，为改进提供方向。我们将其应用于摘要生成、响应生成和问答三个任务，发现生成任务中人类与 LLM 偏好差异显著，而评估任务中 LLM 与人类偏好高度一致。通过利用因素级见解，如解决未对齐因素或利用生成-评估差距，可改善对齐。这项工作强调了可解释偏好分析的重要性，并展示了 PROFILE 提供宝贵训练信号的潜力，推动人类与模型对齐的进一步改进。

> Despite advancements in Large Language Model (LLM) alignment, understanding the reasons behind LLM preferences remains crucial for bridging the gap between desired and actual behavior. LLMs often exhibit biases or tendencies that diverge from human preferences, such as favoring certain writing styles or producing overly verbose outputs. However, current methods for evaluating preference alignment often lack explainability, relying on coarse-grained comparisons. To address this, we introduce PROFILE (PRObing Factors of InfLuence for Explainability), a novel framework that uncovers and quantifies the influence of specific factors driving preferences. PROFILE's factor level analysis explains the 'why' behind human-model alignment and misalignment, offering insights into the direction of model improvement. We apply PROFILE to analyze human and LLM preferences across three tasks: summarization, helpful response generation, and document-based question-answering. Our factor level analysis reveals a substantial discrepancy between human and LLM preferences in generation tasks, whereas LLMs show strong alignment with human preferences in evaluation tasks. We demonstrate how leveraging factor level insights, including addressing misaligned factors or exploiting the generation-evaluation gap, can improve alignment with human preferences. This work underscores the importance of explainable preference analysis and highlights PROFILE's potential to provide valuable training signals, driving further improvements in human-model alignment.

[Arxiv](https://arxiv.org/abs/2410.06965)