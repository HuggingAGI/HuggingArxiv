# Grounding-IQA：用于图像质量评估的多模态语言落地模型

发布时间：2024年11月26日

`LLM应用` `图像质量评估` `多模态`

> Grounding-IQA: Multimodal Language Grounding Model for Image Quality Assessment

# 摘要

> 多模态大型语言模型（MLLMs）的发展让通过自然语言描述来评估图像质量成为可能，这一进步使得评估能够更加详尽。然而，这些基于 MLLM 的图像质量评估（IQA）方法主要依赖通用的上下文描述，有时会限制细粒度的质量评估。为突破这一限制，我们引入了新的图像质量评估（IQA）任务范式——grounding-IQA。此范式将多模态引用和基础与 IQA 相融合，以实现更精细的质量感知。具体来说，grounding-IQA 包含两个子任务：grounding-IQA 描述（GIQA-DES）和视觉问答（GIQA-VQA）。GIQA-DES 涉及带有精确位置（如边界框）的详细描述，而 GIQA-VQA 侧重于局部区域的质量问答。为实现 grounding-IQA，我们通过提出的自动标注管道构建了相应的数据集 GIQA-160K。此外，我们还开发了精心设计的基准 GIQA-Bench。该基准从描述质量、VQA 准确性和基础精度这三个角度全面评估了模型 grounding-IQA 的性能。实验表明，我们提出的任务范式、数据集和基准有助于更精细的 IQA 应用。代码：https://github.com/zhengchen1999/Grounding-IQA。

> The development of multimodal large language models (MLLMs) enables the evaluation of image quality through natural language descriptions. This advancement allows for more detailed assessments. However, these MLLM-based IQA methods primarily rely on general contextual descriptions, sometimes limiting fine-grained quality assessment. To address this limitation, we introduce a new image quality assessment (IQA) task paradigm, grounding-IQA. This paradigm integrates multimodal referring and grounding with IQA to realize more fine-grained quality perception. Specifically, grounding-IQA comprises two subtasks: grounding-IQA-description (GIQA-DES) and visual question answering (GIQA-VQA). GIQA-DES involves detailed descriptions with precise locations (e.g., bounding boxes), while GIQA-VQA focuses on quality QA for local regions. To realize grounding-IQA, we construct a corresponding dataset, GIQA-160K, through our proposed automated annotation pipeline. Furthermore, we develop a well-designed benchmark, GIQA-Bench. The benchmark comprehensively evaluates the model grounding-IQA performance from three perspectives: description quality, VQA accuracy, and grounding precision. Experiments demonstrate that our proposed task paradigm, dataset, and benchmark facilitate the more fine-grained IQA application. Code: https://github.com/zhengchen1999/Grounding-IQA.

[Arxiv](https://arxiv.org/abs/2411.17237)