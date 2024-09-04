# 探究多模态幻觉现象，通过无参数表示对齐技术深入理解

发布时间：2024年09月02日

`LLM应用` `人工智能` `计算机视觉`

> Understanding Multimodal Hallucination with Parameter-Free Representation Alignment

# 摘要

> 幻觉在多模态大型语言模型中颇为常见，但其成因仍待深入探究。本文聚焦于 MLLM 中引发对象幻觉的组件。为精准分析图像表示，我们设计了无参数的表示对齐度量 Pfram，该工具无需额外训练即可衡量任意两表示系统间的相似度，并能评估神经与人类表示系统的对齐程度。通过与对象注释的对齐评估，Pfram 在众多先进 MLLM 中展现了与对象幻觉的高度一致性。此外，我们利用 Pfram 探讨了图像表示相关的其他关键议题，如模块角色、文本指令影响及视觉编码器的潜在优化。代码已公开于：https://github.com/yellow-binary-tree/Pfram。

> Hallucination is a common issue in Multimodal Large Language Models (MLLMs), yet the underlying principles remain poorly understood. In this paper, we investigate which components of MLLMs contribute to object hallucinations. To analyze image representations while completely avoiding the influence of all other factors other than the image representation itself, we propose a parametric-free representation alignment metric (Pfram) that can measure the similarities between any two representation systems without requiring additional training parameters. Notably, Pfram can also assess the alignment of a neural representation system with the human representation system, represented by ground-truth annotations of images. By evaluating the alignment with object annotations, we demonstrate that this metric shows strong and consistent correlations with object hallucination across a wide range of state-of-the-art MLLMs, spanning various model architectures and sizes. Furthermore, using this metric, we explore other key issues related to image representations in MLLMs, such as the role of different modules, the impact of textual instructions, and potential improvements including the use of alternative visual encoders. Our code is available at: https://github.com/yellow-binary-tree/Pfram.

[Arxiv](https://arxiv.org/abs/2409.01151)