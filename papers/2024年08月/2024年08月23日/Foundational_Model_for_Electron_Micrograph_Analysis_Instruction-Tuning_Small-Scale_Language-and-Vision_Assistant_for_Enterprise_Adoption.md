# 电子显微镜图像分析的基础模型：专为企业定制的小型语言与视觉助手，通过指令调整实现高效应用

发布时间：2024年08月23日

`LLM应用` `半导体制造`

> Foundational Model for Electron Micrograph Analysis: Instruction-Tuning Small-Scale Language-and-Vision Assistant for Enterprise Adoption

# 摘要

> 在深度学习领域，半导体成像与分析虽至关重要却鲜有深入研究，这限制了半导体制造中的精准控制与优化。为此，我们提出了一种小规模多模态框架MAEMI，通过视觉与语言指令调优来解析半导体电子显微图像。借助大型多模态模型，我们定制了显微图像分析的指令遵循数据集，并通过知识蒸馏技术，将大型模型的知识迁移至小型模型，显著提升了其在视觉问答任务中的准确性。这一创新方法免除了对昂贵专家标注数据集的依赖，企业还能在其专有数据上进一步优化MAEMI，从而在低成本硬件上实现更佳的隐私保护与性能表现。实验证明，MAEMI不仅超越传统方法，还能适应数据分布的变动，并支持高效的高通量筛选。

> Semiconductor imaging and analysis are critical yet understudied in deep learning, limiting our ability for precise control and optimization in semiconductor manufacturing. We introduce a small-scale multimodal framework for analyzing semiconductor electron microscopy images (MAEMI) through vision-language instruction tuning. We generate a customized instruction-following dataset using large multimodal models on microscopic image analysis. We perform knowledge transfer from larger to smaller models through knowledge distillation, resulting in improved accuracy of smaller models on visual question answering (VQA) tasks. This approach eliminates the need for expensive, human expert-annotated datasets for microscopic image analysis tasks. Enterprises can further finetune MAEMI on their intellectual data, enhancing privacy and performance on low-cost consumer hardware. Our experiments show that MAEMI outperforms traditional methods, adapts to data distribution shifts, and supports high-throughput screening.

[Arxiv](https://arxiv.org/abs/2408.13248)