# 全面探索 Mamba 架构在医学图像分析中的应用：从分类、分割到恢复及其他领域

发布时间：2024年10月03日

`LLM应用` `图像分析`

> A Comprehensive Survey of Mamba Architectures for Medical Image Analysis: Classification, Segmentation, Restoration and Beyond

# 摘要

> Mamba，作为状态空间模型的一种特殊形式，正逐渐成为医学图像分析中替代传统深度学习方法的热门选择。尽管Transformer架构强大，但其二次计算复杂性和难以有效处理长程依赖的缺点，限制了其在医学成像复杂数据集中的应用。相比之下，Mamba以其线性时间复杂度和无需注意力机制处理长序列的能力，展现出更快的推理速度和更低的内存需求。此外，Mamba在整合多模态数据方面表现出色，显著提升了诊断精度和患者治疗效果。本文通过逐步介绍SSM核心概念、Mamba架构及其优化技术，展示了Mamba在医学成像领域的巨大潜力。我们不仅探讨了纯Mamba、U-Net变体及混合模型，还涵盖了其实际应用、实验结果及未来发展方向。这篇综述旨在揭示Mamba如何突破现有技术瓶颈，推动医学成像领域的创新发展。相关Mamba架构的详细列表已在Github上公开。

> Mamba, a special case of the State Space Model, is gaining popularity as an alternative to template-based deep learning approaches in medical image analysis. While transformers are powerful architectures, they have drawbacks, including quadratic computational complexity and an inability to address long-range dependencies efficiently. This limitation affects the analysis of large and complex datasets in medical imaging, where there are many spatial and temporal relationships. In contrast, Mamba offers benefits that make it well-suited for medical image analysis. It has linear time complexity, which is a significant improvement over transformers. Mamba processes longer sequences without attention mechanisms, enabling faster inference and requiring less memory. Mamba also demonstrates strong performance in merging multimodal data, improving diagnosis accuracy and patient outcomes. The organization of this paper allows readers to appreciate the capabilities of Mamba in medical imaging step by step. We begin by defining core concepts of SSMs and models, including S4, S5, and S6, followed by an exploration of Mamba architectures such as pure Mamba, U-Net variants, and hybrid models with convolutional neural networks, transformers, and Graph Neural Networks. We also cover Mamba optimizations, techniques and adaptations, scanning, datasets, applications, experimental results, and conclude with its challenges and future directions in medical imaging. This review aims to demonstrate the transformative potential of Mamba in overcoming existing barriers within medical imaging while paving the way for innovative advancements in the field. A comprehensive list of Mamba architectures applied in the medical field, reviewed in this work, is available at Github.

[Arxiv](https://arxiv.org/abs/2410.02362)