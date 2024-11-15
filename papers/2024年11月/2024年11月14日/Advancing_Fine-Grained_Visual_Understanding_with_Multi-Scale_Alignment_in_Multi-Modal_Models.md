# 在多模态模型中通过多尺度对齐来促进细粒度视觉理解

发布时间：2024年11月14日

`LLM应用` `计算机视觉` `多模态`

> Advancing Fine-Grained Visual Understanding with Multi-Scale Alignment in Multi-Modal Models

# 摘要

> 多模态大型语言模型（MLLMs）在一系列任务的细粒度视觉理解领域成就斐然。然而，因细粒度知识对齐欠佳，它们常面临重大挑战，限制了其精准捕捉局部细节和获取全面全局感知的能力。尽管近期进展聚焦于将对象表达式与基础信息对齐，但通常缺少对象图像的明确整合，而对象图像蕴含着远超单纯文本或坐标的丰富信息。为填补这一空缺，我们推出一种新颖的细粒度视觉知识对齐方式，有效对齐并整合了对象的多尺度知识，涵盖文本、坐标和图像。此创新方式以我们的多尺度细粒度增强数据合成管线为依托，该管线提供超 30 万的关键训练数据，以强化对齐并提升整体性能。另外，我们展示了 TinyGroundingGPT，这是一系列为高级对齐优化的紧凑模型。TinyGroundingGPT 约有 30 亿参数，在基础任务中表现出色，在复杂视觉场景中的性能可与更大的 MLLMs 相媲美。

> Multi-modal large language models (MLLMs) have achieved remarkable success in fine-grained visual understanding across a range of tasks. However, they often encounter significant challenges due to inadequate alignment for fine-grained knowledge, which restricts their ability to accurately capture local details and attain a comprehensive global perception. While recent advancements have focused on aligning object expressions with grounding information, they typically lack explicit integration of object images, which contain affluent information beyond mere texts or coordinates. To bridge this gap, we introduce a novel fine-grained visual knowledge alignment method that effectively aligns and integrates multi-scale knowledge of objects, including texts, coordinates, and images. This innovative method is underpinned by our multi-scale fine-grained enhancement data synthesis pipeline, which provides over 300K essential training data to enhance alignment and improve overall performance. Furthermore, we present TinyGroundingGPT, a series of compact models optimized for high-level alignments. With a scale of approximately 3B parameters, TinyGroundingGPT achieves outstanding results in grounding tasks while delivering performance comparable to larger MLLMs in complex visual scenarios.

[Arxiv](https://arxiv.org/abs/2411.09691)