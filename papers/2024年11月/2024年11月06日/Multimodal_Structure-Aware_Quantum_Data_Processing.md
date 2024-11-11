# 多模态结构感知量子数据处理

发布时间：2024年11月06日

`LLM应用` `量子计算`

> Multimodal Structure-Aware Quantum Data Processing

# 摘要

> 虽然大型语言模型（LLMs）推动了自然语言处理（NLP）领域的发展，但它们的“黑箱”性质掩盖了其决策过程。为了解决这个问题，研究人员使用高阶张量开发了结构化方法。这些方法能够对语言关系进行建模，但由于其规模过大，在经典计算机上训练时会停滞。张量是量子系统的天然组成部分，在量子计算机上进行训练通过将文本转换为变分量子电路提供了一种解决方案。在本文中，我们开发了 MultiQ-NLP：一个用于处理具有多模态文本+图像数据的结构感知数据处理的框架。这里，“结构”指的是语言中的句法和语法关系，以及图像中视觉元素的层次组织。我们通过新的类型和类型同态丰富了翻译，并开发了新的架构来表示结构。在主流图像分类任务（SVO 探测器）上进行测试时，我们的最佳模型与最先进的经典模型表现相当；而且最佳模型是完全结构化的。

> While large language models (LLMs) have advanced the field of natural language processing (NLP), their ``black box'' nature obscures their decision-making processes. To address this, researchers developed structured approaches using higher order tensors. These are able to model linguistic relations, but stall when training on classical computers due to their excessive size. Tensors are natural inhabitants of quantum systems and training on quantum computers provides a solution by translating text to variational quantum circuits. In this paper, we develop MultiQ-NLP: a framework for structure-aware data processing with multimodal text+image data. Here, ``structure'' refers to syntactic and grammatical relationships in language, as well as the hierarchical organization of visual elements in images. We enrich the translation with new types and type homomorphisms and develop novel architectures to represent structure. When tested on a main stream image classification task (SVO Probes), our best model showed a par performance with the state of the art classical models; moreover the best model was fully structured.

[Arxiv](https://arxiv.org/abs/2411.04242)