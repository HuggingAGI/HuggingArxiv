# 探索多模态幻觉现象，通过无参数表示对齐技术深入解析

发布时间：2024年09月02日

`LLM应用` `计算机视觉` `人工智能`

> Understanding Multimodal Hallucination with Parameter-Free Representation Alignment

# 摘要

> 幻觉在多模态大型语言模型中颇为常见，但其成因仍待深入探究。本文聚焦于 MLLM 中引发对象幻觉的组件。为精准分析图像表示，我们设计了无参数的表示对齐度量 Pfram，它能在不依赖额外训练参数的前提下，衡量任意两表示系统间的相似度。Pfram 还能评估神经网络表示与人类视觉认知（以图像真实标注为基准）的对齐程度。通过与对象标注的对齐评估，我们发现 Pfram 在各类先进 MLLM 中与对象幻觉现象高度相关。此外，该度量还助力我们探讨了 MLLM 中图像表示的其他关键议题，如模块差异、文本指令作用及视觉编码器优化等。相关代码已公开于：https://github.com/yellow-binary-tree/Pfram。

> Hallucination is a common issue in Multimodal Large Language Models (MLLMs), yet the underlying principles remain poorly understood. In this paper, we investigate which components of MLLMs contribute to object hallucinations. To analyze image representations while completely avoiding the influence of all other factors other than the image representation itself, we propose a parametric-free representation alignment metric (Pfram) that can measure the similarities between any two representation systems without requiring additional training parameters. Notably, Pfram can also assess the alignment of a neural representation system with the human representation system, represented by ground-truth annotations of images. By evaluating the alignment with object annotations, we demonstrate that this metric shows strong and consistent correlations with object hallucination across a wide range of state-of-the-art MLLMs, spanning various model architectures and sizes. Furthermore, using this metric, we explore other key issues related to image representations in MLLMs, such as the role of different modules, the impact of textual instructions, and potential improvements including the use of alternative visual encoders. Our code is available at: https://github.com/yellow-binary-tree/Pfram.

[Arxiv](https://arxiv.org/abs/2409.01151)