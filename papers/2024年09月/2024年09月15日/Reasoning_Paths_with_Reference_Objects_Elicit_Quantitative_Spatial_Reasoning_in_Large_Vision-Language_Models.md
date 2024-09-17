# 借助参考对象的推理路径，大型视觉语言模型能够实现定量空间推理。

发布时间：2024年09月15日

`LLM应用` `计算机视觉` `人工智能`

> Reasoning Paths with Reference Objects Elicit Quantitative Spatial Reasoning in Large Vision-Language Models

# 摘要

> 尽管视觉-语言模型（VLMs）在描述图像复杂关系方面取得了进展，但在定量推理物体大小和距离方面仍显不足。为此，我们推出了Q-Spatial Bench，一个包含271个问题的手动注释基准，旨在测试定量空间推理能力。研究发现，VLMs在推理物体间距离时尤为困难，但不同模型间表现差异显著，最佳模型间差距达40分。有趣的是，当推理路径中自然包含参考物体时，顶级VLM的成功率提升了19分。基于此，我们设计了SpatialPrompt，一种零-shot提示技术，通过引导VLMs使用参考物体，显著提升了Gemini 1.5 Pro、Gemini 1.5 Flash和GPT-4V的成功率，分别提高了40、20和30分，且无需额外数据或模型调整。

> Despite recent advances demonstrating vision-language models' (VLMs) abilities to describe complex relationships in images using natural language, their capability to quantitatively reason about object sizes and distances remains underexplored. In this work, we introduce a manually annotated benchmark, Q-Spatial Bench, with 271 questions across five categories designed for quantitative spatial reasoning and systematically investigate the performance of state-of-the-art VLMs on this task. Our analysis reveals that reasoning about distances between objects is particularly challenging for SoTA VLMs; however, some VLMs significantly outperform others, with an over 40-point gap between the two best performing models. We also make the surprising observation that the success rate of the top-performing VLM increases by 19 points when a reasoning path using a reference object emerges naturally in the response. Inspired by this observation, we develop a zero-shot prompting technique, SpatialPrompt, that encourages VLMs to answer quantitative spatial questions using reference objects as visual cues. By instructing VLMs to use reference objects in their reasoning paths via SpatialPrompt, Gemini 1.5 Pro, Gemini 1.5 Flash, and GPT-4V improve their success rates by over 40, 20, and 30 points, respectively. We emphasize that these significant improvements are obtained without needing more data, model architectural modifications, or fine-tuning.

[Arxiv](https://arxiv.org/abs/2409.09788)