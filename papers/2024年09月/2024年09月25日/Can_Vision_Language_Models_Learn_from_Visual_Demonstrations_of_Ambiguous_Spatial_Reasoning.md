# 视觉语言模型能否从模糊空间推理的视觉演示中汲取知识？

发布时间：2024年09月25日

`LLM应用` `计算机视觉` `机器学习`

> Can Vision Language Models Learn from Visual Demonstrations of Ambiguous Spatial Reasoning?

# 摘要

> VLMs 在计算机视觉任务中表现卓越，ICL 是适应新任务的热门策略。但 VLMs 能否仅凭视觉演示学习新概念，还是仅限于适应 ICL 示例的输出格式？我们提出了 SVAT 基准，挑战 VLMs 在上下文中学习新视觉空间任务。结果显示，VLMs 在零-shot 情况下表现不佳，有时微调后仍失败。不过，通过课程学习添加简单数据，ICL 性能有所提升。

> Large vision-language models (VLMs) have become state-of-the-art for many computer vision tasks, with in-context learning (ICL) as a popular adaptation strategy for new ones. But can VLMs learn novel concepts purely from visual demonstrations, or are they limited to adapting to the output format of ICL examples? We propose a new benchmark we call Spatial Visual Ambiguity Tasks (SVAT) that challenges state-of-the-art VLMs to learn new visuospatial tasks in-context. We find that VLMs fail to do this zero-shot, and sometimes continue to fail after finetuning. However, adding simpler data to the training by curriculum learning leads to improved ICL performance.

[Arxiv](https://arxiv.org/abs/2409.17080)