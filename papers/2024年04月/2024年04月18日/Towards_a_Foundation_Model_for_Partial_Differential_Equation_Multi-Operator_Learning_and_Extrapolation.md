# 迈向构建偏微分方程基础模型之路：探究多操作符学习与外推技术

发布时间：2024年04月18日

`分类：LLM应用` `科学计算` `物理建模`

> Towards a Foundation Model for Partial Differential Equation: Multi-Operator Learning and Extrapolation

# 摘要

> 基础模型，如大型语言模型，在处理多种语言和图像处理任务上已取得显著成效。本研究提出了一个名为PROSE-PDE的多模态基础模型，专门针对科学问题。该模型采用双模态学习，通过多操作符学习方法，不仅能够预测时空系统的未来发展，还能同时掌握物理系统的基本原理方程。我们专注于通过训练不同的一维时变非线性常系数偏微分方程来进行多操作符学习，这为物理、地质和生物等多个领域提供了潜在应用。关键的是，我们通过三项外推研究展示了PROSE-PDE如何通过稳健的多操作符训练泛化物理特性，并能够预测在训练阶段未遇到的PDE解决方案。此外，通过一系列系统的数值实验，我们证明了模型中符号模态的使用有效解决了多操作符训练中的适定性问题，显著提升了模型的预测性能。

> Foundation models, such as large language models, have demonstrated success in addressing various language and image processing tasks. In this work, we introduce a multi-modal foundation model for scientific problems, named PROSE-PDE. Our model, designed for bi-modality to bi-modality learning, is a multi-operator learning approach which can predict future states of spatiotemporal systems while concurrently learning the underlying governing equations of the physical system. Specifically, we focus on multi-operator learning by training distinct one-dimensional time-dependent nonlinear constant coefficient partial differential equations, with potential applications to many physical applications including physics, geology, and biology. More importantly, we provide three extrapolation studies to demonstrate that PROSE-PDE can generalize physical features through the robust training of multiple operators and that the proposed model can extrapolate to predict PDE solutions whose models or data were unseen during the training. Furthermore, we show through systematic numerical experiments that the utilization of the symbolic modality in our model effectively resolves the well-posedness problems with training multiple operators and thus enhances our model's predictive capabilities.

![迈向构建偏微分方程基础模型之路：探究多操作符学习与外推技术](../../../paper_images/2404.12355/x1.png)

![迈向构建偏微分方程基础模型之路：探究多操作符学习与外推技术](../../../paper_images/2404.12355/x2.png)

![迈向构建偏微分方程基础模型之路：探究多操作符学习与外推技术](../../../paper_images/2404.12355/x7.png)

![迈向构建偏微分方程基础模型之路：探究多操作符学习与外推技术](../../../paper_images/2404.12355/x8.png)

![迈向构建偏微分方程基础模型之路：探究多操作符学习与外推技术](../../../paper_images/2404.12355/x9.png)

[Arxiv](https://arxiv.org/abs/2404.12355)