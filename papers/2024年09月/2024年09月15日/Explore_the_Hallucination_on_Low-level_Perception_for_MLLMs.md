# 深入研究 MLLMs 在低层次感知中的幻觉现象

发布时间：2024年09月15日

`LLM应用` `人工智能` `视觉识别`

> Explore the Hallucination on Low-level Perception for MLLMs

# 摘要

> 多模态大型语言模型 (MLLM) 的迅猛发展，不仅在视觉感知和理解方面展现了卓越能力，也深刻影响了工业和日常生活的多个领域。然而，这些模型在低级视觉任务中的幻觉现象，却暴露了其作为 AI 系统的可靠性短板。我们认为，这种幻觉源于模型缺乏明确的自我意识，进而影响了整体性能。本文旨在探讨 MLLM 在低级视觉任务中的自我意识，为此我们推出了 QL-Bench 基准，通过模拟人类对低级视觉的反应，特别是通过视觉问答来评估模型的自我意识。我们构建的 LLSAVisionQA 数据集，包含近三千张图像和近两千对图像，每张图像都附有关于其低级特征的开放式问题。评估结果显示，尽管部分模型在低级视觉任务中表现出色，但其自我意识仍有待提升。有趣的是，模型在回答简单问题时往往更准确，但在应对复杂问题时，自我意识似乎有所增强。我们期待这一基准能够推动更多关于提升 MLLM 自我意识的研究，特别是在低级视觉感知和理解领域。

> The rapid development of Multi-modality Large Language Models (MLLMs) has significantly influenced various aspects of industry and daily life, showcasing impressive capabilities in visual perception and understanding. However, these models also exhibit hallucinations, which limit their reliability as AI systems, especially in tasks involving low-level visual perception and understanding. We believe that hallucinations stem from a lack of explicit self-awareness in these models, which directly impacts their overall performance. In this paper, we aim to define and evaluate the self-awareness of MLLMs in low-level visual perception and understanding tasks. To this end, we present QL-Bench, a benchmark settings to simulate human responses to low-level vision, investigating self-awareness in low-level visual perception through visual question answering related to low-level attributes such as clarity and lighting. Specifically, we construct the LLSAVisionQA dataset, comprising 2,990 single images and 1,999 image pairs, each accompanied by an open-ended question about its low-level features. Through the evaluation of 15 MLLMs, we demonstrate that while some models exhibit robust low-level visual capabilities, their self-awareness remains relatively underdeveloped. Notably, for the same model, simpler questions are often answered more accurately than complex ones. However, self-awareness appears to improve when addressing more challenging questions. We hope that our benchmark will motivate further research, particularly focused on enhancing the self-awareness of MLLMs in tasks involving low-level visual perception and understanding.

[Arxiv](https://arxiv.org/abs/2409.09748)