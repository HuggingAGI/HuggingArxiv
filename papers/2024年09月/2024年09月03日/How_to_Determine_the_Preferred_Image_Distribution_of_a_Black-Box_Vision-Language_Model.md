# 怎样找出黑箱视觉-语言模型偏好的图像分布？

发布时间：2024年09月03日

`LLM应用` `制造业` `计算机辅助设计`

> How to Determine the Preferred Image Distribution of a Black-Box Vision-Language Model?

# 摘要

> 尽管大型基础模型已革新了领域，但在特定视觉任务的多模态模型优化上仍存挑战。我们创新性地提出一种方法，通过分析不同输入下的输出一致性，来识别视觉-语言模型（VLM）的理想图像分布。此方法应用于3D对象的不同渲染类型，证明了其在需精准解析复杂结构的多个领域中的有效性，特别是以CAD为例。此外，我们利用人类反馈的上下文学习优化VLM输出，大幅提升了解释质量。为填补特定领域基准的空白，我们创建了CAD-VQA数据集，用于评估VLM在CAD视觉问答任务上的表现。通过在CAD-VQA上对顶尖VLM的评估，我们设定了性能基线，为在各领域中提升VLM在复杂视觉推理任务的能力奠定了框架。数据集和评估代码已发布于\url{https://github.com/asgsaeid/cad_vqa}。

> Large foundation models have revolutionized the field, yet challenges remain in optimizing multi-modal models for specialized visual tasks. We propose a novel, generalizable methodology to identify preferred image distributions for black-box Vision-Language Models (VLMs) by measuring output consistency across varied input prompts. Applying this to different rendering types of 3D objects, we demonstrate its efficacy across various domains requiring precise interpretation of complex structures, with a focus on Computer-Aided Design (CAD) as an exemplar field. We further refine VLM outputs using in-context learning with human feedback, significantly enhancing explanation quality. To address the lack of benchmarks in specialized domains, we introduce CAD-VQA, a new dataset for evaluating VLMs on CAD-related visual question answering tasks. Our evaluation of state-of-the-art VLMs on CAD-VQA establishes baseline performance levels, providing a framework for advancing VLM capabilities in complex visual reasoning tasks across various fields requiring expert-level visual interpretation. We release the dataset and evaluation codes at \url{https://github.com/asgsaeid/cad_vqa}.

[Arxiv](https://arxiv.org/abs/2409.02253)