# LLM-AD：一种依托于先进大型语言模型的音频描述解决方案

发布时间：2024年05月01日

`LLM应用` `视频内容制作` `自动化系统`

> LLM-AD: Large Language Model based Audio Description System

# 摘要

> 音频描述（AD）的进步极大提升了视频内容的可访问性和包容性。传统AD制作依赖大量专业劳动力，而自动化方案则需大量训练以融合多模态信息，将字幕风格转化为AD风格。本文提出了一个自动化AD生成流程，该流程充分发挥了GPT-4V（视觉）在多模态处理和指令执行方面的强大功能。我们的方法使用了易于获取的组件，避免了额外训练的需要。它生成的AD不仅遵循了标准的自然语言AD制作规范，还通过追踪式角色识别模块，在不同帧之间保持了角色信息的上下文一致性。在MAD数据集上的深入分析显示，我们的方法在自动化AD生产中的表现与基于学习的方法相当，CIDEr得分达到20.5，证明了其效果。

> The development of Audio Description (AD) has been a pivotal step forward in making video content more accessible and inclusive. Traditionally, AD production has demanded a considerable amount of skilled labor, while existing automated approaches still necessitate extensive training to integrate multimodal inputs and tailor the output from a captioning style to an AD style. In this paper, we introduce an automated AD generation pipeline that harnesses the potent multimodal and instruction-following capacities of GPT-4V(ision). Notably, our methodology employs readily available components, eliminating the need for additional training. It produces ADs that not only comply with established natural language AD production standards but also maintain contextually consistent character information across frames, courtesy of a tracking-based character recognition module. A thorough analysis on the MAD dataset reveals that our approach achieves a performance on par with learning-based methods in automated AD production, as substantiated by a CIDEr score of 20.5.

[Arxiv](https://arxiv.org/abs/2405.00983)