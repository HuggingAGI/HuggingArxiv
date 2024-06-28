# 基于Grounding DINO文本提示，Segment Anything模型在自动化图像数据标注中的应用：一项实证研究

发布时间：2024年06月27日

`Agent

理由：这篇论文主要讨论了如何利用 Grounding DINO 的指称表达理解能力来精准定位目标，并针对 REC 框架在开放集语义分割中易产生误报的问题提出了解决策略。这些内容涉及到使用特定的模型（如 Grounding DINO 和 Segment Anything Model）来改进特定任务（如物体检测和图像分割），并且强调了模型在特定领域（如医学图像分割）的应用。因此，这篇论文更符合Agent分类，因为它关注的是如何通过特定的模型或系统来执行任务，而不是理论研究或广泛的应用场景。` `图像分割`

> Segment Anything Model for automated image data annotation: empirical studies using text prompts from Grounding DINO

# 摘要

> Grounding DINO 与 Segment Anything Model (SAM) 在零-shot 物体检测和图像分割领域表现卓越，二者结合有望革新语义分割和数据标注。但在医学图像分割等专业领域，现有类别无法涵盖所有感兴趣对象。为此，我们借助 Grounding DINO 的指称表达理解能力，通过语言描述精准定位目标。然而，REC 框架在此场景下易产生误报，成为开放集语义分割的瓶颈。通过分析八个公开数据集，我们发现误报模式可预测，并提出简单策略有效减少误报。这些发现不仅优化了 REC 检测和自动化分割，还显著提升了 SAM 在多领域数据集上的分割性能和标注效率。

> Grounding DINO and the Segment Anything Model (SAM) have achieved impressive performance in zero-shot object detection and image segmentation, respectively. Together, they have a great potential in revolutionizing zero-shot semantic segmentation or data annotation. Yet, in specialized domains like medical image segmentation, objects of interest (e.g., organs, tissues, and tumors) may not fall in existing class names. To address this problem, the referring expression comprehension (REC) ability of Grounding DINO is leveraged to detect arbitrary targets by their language descriptions. However, recent studies have highlighted severe limitation of the REC framework in this application setting owing to its tendency to make false positive predictions when the target is absent in the given image. And, while this bottleneck is central to the prospect of open-set semantic segmentation, it is still largely unknown how much improvement can be achieved by studying the prediction errors. To this end, we perform empirical studies on eight publicly available datasets and reveal that these errors consistently follow a predictable pattern and can, thus, be mitigated by a simple strategy. Specifically, we show that these false positive detections with appreciable confidence scores generally occupy large image areas and can usually be filtered by their relative sizes. More importantly, we expect these observations to inspire future research in improving REC-based detection and automated segmentation. Using this technique, we evaluate the performance of SAM on multiple datasets from various specialized domains and report significant improvement in segmentation performance and annotation time savings over manual approaches.

[Arxiv](https://arxiv.org/abs/2406.19057)