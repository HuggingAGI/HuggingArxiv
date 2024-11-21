# FASTNav：用于多点机器人导航的经过微调的自适应小型语言模型

发布时间：2024年11月20日

`LLM应用` `机器人` `边缘计算`

> FASTNav: Fine-tuned Adaptive Small-language-models Trained for Multi-point Robot Navigation

# 摘要

> 随着大型语言模型（LLM）的迅猛发展，机器人开始受益于其带来的新交互方式。鉴于边缘计算能够满足快速响应、隐私保护和网络自主的需求，我们觉得它有利于在各行业广泛部署用于机器人导航的大型模型。为在边缘设备上实现语言模型的本地部署，我们采用了一些模型增强手段。在本文中，我们提出了FASTNav——一种用于增强用于机器人导航的轻量级LLM（即小型语言模型SLM）的方法。该方法包含三个模块：微调、师生迭代以及基于语言的多点机器人导航。我们在模拟和真实机器人场景中用FASTNav训练和评估模型，结果表明能够以低成本、高精度和低响应时间进行部署。和其他模型压缩方法相比，FASTNav在语言模型的本地部署上展现出潜力，有望成为边缘设备上语言引导机器人导航的理想解决方案。

> With the rapid development of large language models (LLM), robots are starting to enjoy the benefits of new interaction methods that large language models bring. Because edge computing fulfills the needs for rapid response, privacy, and network autonomy, we believe it facilitates the extensive deployment of large models for robot navigation across various industries. To enable local deployment of language models on edge devices, we adopt some model boosting methods. In this paper, we propose FASTNav - a method for boosting lightweight LLMs, also known as small language models (SLMs), for robot navigation. The proposed method contains three modules: fine-tuning, teacher-student iteration, and language-based multi-point robot navigation. We train and evaluate models with FASTNav in both simulation and real robots, proving that we can deploy them with low cost, high accuracy and low response time. Compared to other model compression methods, FASTNav shows potential in the local deployment of language models and tends to be a promising solution for language-guided robot navigation on edge devices.

[Arxiv](https://arxiv.org/abs/2411.13262)