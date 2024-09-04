# 大型语言模型具备从单张图像中解读深度的能力

发布时间：2024年09月02日

`LLM应用` `计算机视觉` `人工智能`

> Large Language Models Can Understanding Depth from Monocular Images

# 摘要

> 单目深度估计在计算机视觉领域至关重要。本文揭示，大型语言模型 (LLM) 能在极少监督下，凭借高效资源利用和统一神经网络架构，精准解读深度。我们创新推出 LLM-MDE 框架，通过语言理解破解深度之谜。该框架采用跨模态重编程和自适应提示生成两大策略，提升 LLM 的深度感知能力，实现视觉与文本的无缝对接，并智能生成图像提示。实证研究显示，LLM-MDE 在少-/零-shot 任务中独占鳌头，资源消耗极低。源代码现已开放。

> Monocular depth estimation is a critical function in computer vision applications. This paper shows that large language models (LLMs) can effectively interpret depth with minimal supervision, using efficient resource utilization and a consistent neural network architecture. We introduce LLM-MDE, a multimodal framework that deciphers depth through language comprehension. Specifically, LLM-MDE employs two main strategies to enhance the pretrained LLM's capability for depth estimation: cross-modal reprogramming and an adaptive prompt estimation module. These strategies align vision representations with text prototypes and automatically generate prompts based on monocular images, respectively. Comprehensive experiments on real-world MDE datasets confirm the effectiveness and superiority of LLM-MDE, which excels in few-/zero-shot tasks while minimizing resource use. The source code is available.

[Arxiv](https://arxiv.org/abs/2409.01133)