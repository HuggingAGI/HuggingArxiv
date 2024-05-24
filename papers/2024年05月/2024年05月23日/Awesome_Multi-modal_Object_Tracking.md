# 精彩纷呈的多模态追踪技术

发布时间：2024年05月23日

`Agent

理由：这篇论文摘要主要讨论了多模态物体跟踪（MMOT）技术的发展，包括其应用、技术进展和数据集。虽然这项技术涉及多种模态数据的处理，但其核心在于构建能够适应不同模态数据的跟踪模型，这在本质上是一种智能代理（Agent）的行为，因为它涉及到在复杂环境中（如自动驾驶和智能监控）对物体的识别和跟踪。因此，将其归类为Agent更为合适。` `自动驾驶` `智能监控`

> Awesome Multi-modal Object Tracking

# 摘要

> 多模态物体跟踪（MMOT）领域正蓬勃发展，它融合了视觉、深度、热红外等多种数据源，以精准追踪视频中的物体。这一技术对自动驾驶和智能监控等应用至关重要。尽管MMOT日益受到重视，但多数算法仍局限于两种模态的结合。近期，研究者们开始探索构建一个能适应任何模态的统一跟踪模型，并建立了包含多种模态的大规模基准，如WebUAV-3M和UniMod1K。本报告深入探讨了MMOT的最新进展，将其任务细分为五大类，并分析了主流技术和数据集。我们还维护了一个持续更新的MMOT论文列表，网址为https://github.com/983632847/Awesome-Multimodal-Object-Tracking。

> Multi-modal object tracking (MMOT) is an emerging field that combines data from various modalities, \eg vision (RGB), depth, thermal infrared, event, language and audio, to estimate the state of an arbitrary object in a video sequence. It is of great significance for many applications such as autonomous driving and intelligent surveillance. In recent years, MMOT has received more and more attention. However, existing MMOT algorithms mainly focus on two modalities (\eg RGB+depth, RGB+thermal infrared, and RGB+language). To leverage more modalities, some recent efforts have been made to learn a unified visual object tracking model for any modality. Additionally, some large-scale multi-modal tracking benchmarks have been established by simultaneously providing more than two modalities, such as vision-language-audio (\eg WebUAV-3M) and vision-depth-language (\eg UniMod1K). To track the latest progress in MMOT, we conduct a comprehensive investigation in this report. Specifically, we first divide existing MMOT tasks into five main categories, \ie RGBL tracking, RGBE tracking, RGBD tracking, RGBT tracking, and miscellaneous (RGB+X), where X can be any modality, such as language, depth, and event. Then, we analyze and summarize each MMOT task, focusing on widely used datasets and mainstream tracking algorithms based on their technical paradigms (\eg self-supervised learning, prompt learning, knowledge distillation, generative models, and state space models). Finally, we maintain a continuously updated paper list for MMOT at https://github.com/983632847/Awesome-Multimodal-Object-Tracking.

[Arxiv](https://arxiv.org/abs/2405.14200)