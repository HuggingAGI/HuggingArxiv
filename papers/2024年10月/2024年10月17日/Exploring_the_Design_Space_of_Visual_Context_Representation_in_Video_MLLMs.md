# 探索视频MLLMs中视觉上下文表示的设计空间

发布时间：2024年10月17日

`LLM应用` `视频分析` `人工智能`

> Exploring the Design Space of Visual Context Representation in Video MLLMs

# 摘要

> 视频多模态大型语言模型 (MLLM) 在理解视频语义方面表现出色，但关于视觉上下文表示的系统研究仍显不足。本文探讨了视觉上下文表示的设计空间，旨在通过更有效的表示方案提升视频 MLLM 的性能。我们首先将视觉上下文表示任务建模为约束优化问题，并分析了帧数和每帧标记数对语言建模损失的影响。接着，通过大量实验，我们分别研究了帧选择和标记选择的缩放效应，并验证了典型策略的有效性。最后，我们推导出帧选择和标记选择的最佳组合公式，发现其与实验结果高度吻合。代码和模型详见：https://github.com/RUCAIBox/Opt-Visor。

> Video Multimodal Large Language Models (MLLMs) have shown remarkable capability of understanding the video semantics on various downstream tasks. Despite the advancements, there is still a lack of systematic research on visual context representation, which refers to the scheme to select frames from a video and further select the tokens from a frame. In this paper, we explore the design space for visual context representation, and aim to improve the performance of video MLLMs by finding more effective representation schemes. Firstly, we formulate the task of visual context representation as a constrained optimization problem, and model the language modeling loss as a function of the number of frames and the number of embeddings (or tokens) per frame, given the maximum visual context window size. Then, we explore the scaling effects in frame selection and token selection respectively, and fit the corresponding function curve by conducting extensive empirical experiments. We examine the effectiveness of typical selection strategies and present empirical findings to determine the two factors. Furthermore, we study the joint effect of frame selection and token selection, and derive the optimal formula for determining the two factors. We demonstrate that the derived optimal settings show alignment with the best-performed results of empirical experiments. Our code and model are available at: https://github.com/RUCAIBox/Opt-Visor.

[Arxiv](https://arxiv.org/abs/2410.13694)