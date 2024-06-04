# BELLS：构建未来验证的基准，精准评估大型语言模型安全措施的框架

发布时间：2024年06月03日

`LLM应用

理由：这篇论文主要关注的是大型语言模型（LLMs）的安全措施评估，特别是推出了一个评估基准（BELLS），并针对不同类型的安全措施进行了测试，包括针对复杂架构如LLM代理和多代理系统的测试。这些内容主要涉及LLM在实际应用中的安全性能评估和改进，因此属于LLM应用的范畴。` `安全措施评估` `人工智能安全`

> BELLS: A Framework Towards Future Proof Benchmarks for the Evaluation of LLM Safeguards

# 摘要

> 输入输出安全措施用于检测大型语言模型（LLMs）系统中的异常跟踪。这些检测器在实时监控、跟踪离线评估和内容审核等关键安全应用中至关重要。然而，缺乏公认的评估方法。为此，我们推出了LLM安全措施评估基准（BELLS），包含三类测试：（1）基于现有基准的成熟故障测试，旨在比较安全措施性能；（2）新兴故障测试，鼓励开发更通用的安全措施；（3）下一代架构测试，针对复杂架构，如LLM代理和多代理系统，旨在开发能适应未来应用的安全措施。我们还实施了首个下一代架构测试，并提供了MACHIAVELLI环境下的数据集交互式可视化。

> Input-output safeguards are used to detect anomalies in the traces produced by Large Language Models (LLMs) systems. These detectors are at the core of diverse safety-critical applications such as real-time monitoring, offline evaluation of traces, and content moderation. However, there is no widely recognized methodology to evaluate them. To fill this gap, we introduce the Benchmarks for the Evaluation of LLM Safeguards (BELLS), a structured collection of tests, organized into three categories: (1) established failure tests, based on already-existing benchmarks for well-defined failure modes, aiming to compare the performance of current input-output safeguards; (2) emerging failure tests, to measure generalization to never-seen-before failure modes and encourage the development of more general safeguards; (3) next-gen architecture tests, for more complex scaffolding (such as LLM-agents and multi-agent systems), aiming to foster the development of safeguards that could adapt to future applications for which no safeguard currently exists. Furthermore, we implement and share the first next-gen architecture test, using the MACHIAVELLI environment, along with an interactive visualization of the dataset.

![BELLS：构建未来验证的基准，精准评估大型语言模型安全措施的框架](../../../paper_images/2406.01364/x1.png)

![BELLS：构建未来验证的基准，精准评估大型语言模型安全措施的框架](../../../paper_images/2406.01364/x2.png)

![BELLS：构建未来验证的基准，精准评估大型语言模型安全措施的框架](../../../paper_images/2406.01364/x3.png)

![BELLS：构建未来验证的基准，精准评估大型语言模型安全措施的框架](../../../paper_images/2406.01364/x4.png)

![BELLS：构建未来验证的基准，精准评估大型语言模型安全措施的框架](../../../paper_images/2406.01364/x5.png)

![BELLS：构建未来验证的基准，精准评估大型语言模型安全措施的框架](../../../paper_images/2406.01364/visualisation.png)

[Arxiv](https://arxiv.org/abs/2406.01364)