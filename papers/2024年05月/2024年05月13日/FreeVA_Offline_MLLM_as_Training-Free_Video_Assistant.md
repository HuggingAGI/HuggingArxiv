# FreeVA：即刻启用的离线视频助手，基于无需额外训练的多模态大型语言模型技术。

发布时间：2024年05月13日

`LLM应用

这篇论文聚焦于多模态大型语言模型（MLLMs）在视频领域的应用，特别是通过FreeVA项目探索了将基于图像的MLLM扩展到视频领域的可能性，并进行了实证研究。论文讨论了零-shot视频问答任务的表现、视频指令调整的效果，以及现有评估指标的局限性。这些内容直接关联到大型语言模型在特定应用场景（即视频助手）的实际应用和评估，因此属于LLM应用类别。` `视频处理` `人工智能`

> FreeVA: Offline MLLM as Training-Free Video Assistant

# 摘要

> 本文对多模态大型语言模型（MLLMs）的最新进展——视频助手进行了深入的实证研究。研究项目FreeVA旨在无需额外训练，将基于图像的MLLM扩展至视频领域。研究不仅确立了关键的基准，还揭示了几个令人瞩目的发现：1）FreeVA仅依赖离线图像基MLLM，在零-shot视频问答任务中表现卓越，超越了那些需要视频指令调整的尖端方法。2）尽管主流视频基MLLMs通常从图像基MLLM出发，再通过视频指令调整进行微调，但研究发现，使用VideoInstruct-100K进行视频指令调整并不比不训练带来更好的效果。3）现有评估指标受到GPT API版本变化的影响，忽视这一点可能导致比较不公和分析失准。MLLMs领域正蓬勃发展，吸引了众多研究者。我们希望这项工作能成为简单有效的基准，推动现有MLLMs在视频领域的直接评估，并促进视频对话模型领域的规范化。同时，我们呼吁研究者反思：当前的视频MLLM方法是否真正超越了图像MLLM的知识边界？相关代码已公开于https://github.com/whwu95/FreeVA。

> This paper undertakes an empirical study to revisit the latest advancements in Multimodal Large Language Models (MLLMs): Video Assistant. This study, namely FreeVA, aims to extend existing image-based MLLM to the video domain in a training-free manner. The study provides an essential, yet must-know baseline, and reveals several surprising findings: 1) FreeVA, leveraging only offline image-based MLLM without additional training, excels in zero-shot video question-answering (e.g., MSVD-QA, ActivityNet-QA, and MSRVTT-QA), even surpassing state-of-the-art methods that involve video instruction tuning. 2) While mainstream video-based MLLMs typically initialize with an image-based MLLM (e.g., LLaVA) and then fine-tune using video instruction tuning, the study indicates that utilizing the widely adopted VideoInstruct-100K for video instruction tuning doesn't actually lead to better performance compared to not training at all. 3) The commonly used evaluation metrics in existing works are significantly influenced by changes in the GPT API version over time. If ignored, this could affect the fairness and uniformity of comparisons between different methods and impact the analysis and judgment of researchers in the field. The advancement of MLLMs is currently thriving, drawing numerous researchers into the field. We aim for this work to serve as a plug-and-play, simple yet effective baseline, encouraging the direct evaluation of existing MLLMs in video domain while also standardizing the field of video conversational models to a certain extent. Also, we encourage researchers to reconsider: Have current video MLLM methods truly acquired knowledge beyond image MLLM? Code is available at https://github.com/whwu95/FreeVA

[Arxiv](https://arxiv.org/abs/2405.07798)