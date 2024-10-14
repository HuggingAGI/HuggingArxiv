# 遥感图像分割中的跨模态双向交互模型

发布时间：2024年10月11日

`其他` `地理信息系统`

> Cross-Modal Bidirectional Interaction Model for Referring Remote Sensing Image Segmentation

# 摘要

> 在给定自然语言描述和遥感图像的情况下，参考遥感图像分割 (RRSIS) 旨在生成目标对象的像素级掩码。与自然场景不同，RRSIS 中的描述常涉及复杂的地理空间关系，目标对象在规模和视觉显著性上差异大，增加了分割难度。为此，我们提出了跨模态双向交互模型 (CroBIM)。该模型通过上下文感知提示调制 (CAPM) 模块和语言引导的特征聚合 (LGFA) 模块，分别增强语言特征和视觉特征的整合。最后，通过相互交互解码器 (MID) 实现精确的分割掩码预测。此外，我们还构建了包含 52,472 个三元组的大规模基准数据集 RISBench。实验表明，CroBIM 在多个数据集上均优于现有最先进方法。源代码和数据集将在 GitHub 上公开。

> Given a natural language expression and a remote sensing image, the goal of referring remote sensing image segmentation (RRSIS) is to generate a pixel-level mask of the target object identified by the referring expression. In contrast to natural scenarios, expressions in RRSIS often involve complex geospatial relationships, with target objects of interest that vary significantly in scale and lack visual saliency, thereby increasing the difficulty of achieving precise segmentation. To address the aforementioned challenges, a novel RRSIS framework is proposed, termed the cross-modal bidirectional interaction model (CroBIM). Specifically, a context-aware prompt modulation (CAPM) module is designed to integrate spatial positional relationships and task-specific knowledge into the linguistic features, thereby enhancing the ability to capture the target object. Additionally, a language-guided feature aggregation (LGFA) module is introduced to integrate linguistic information into multi-scale visual features, incorporating an attention deficit compensation mechanism to enhance feature aggregation. Finally, a mutual-interaction decoder (MID) is designed to enhance cross-modal feature alignment through cascaded bidirectional cross-attention, thereby enabling precise segmentation mask prediction. To further forster the research of RRSIS, we also construct RISBench, a new large-scale benchmark dataset comprising 52,472 image-language-label triplets. Extensive benchmarking on RISBench and two other prevalent datasets demonstrates the superior performance of the proposed CroBIM over existing state-of-the-art (SOTA) methods. The source code for CroBIM and the RISBench dataset will be publicly available at https://github.com/HIT-SIRS/CroBIM

[Arxiv](https://arxiv.org/abs/2410.08613)