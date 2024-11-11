# AndroidLab：安卓自主代理的训练和系统基准测试

发布时间：2024年11月04日

`Agent` `自主代理`

> AndroidLab: Training and Systematic Benchmarking of Android Autonomous Agents

# 摘要

> 自主代理对于与现实世界互动变得越来越重要。特别是安卓代理，最近已成为一个经常被提及的交互方法。然而，现有的用于训练和评估安卓代理的研究在开源和闭源模型上都缺乏系统的研究。在这项工作中，我们提出 AndroidLab 作为一个系统的安卓代理框架。它包括具有不同模态的操作环境、动作空间和可重现的基准。它在同一动作空间中支持大型语言模型（LLM）和多模态模型（LMM）。AndroidLab 基准包括预定义的安卓虚拟设备和在这些设备上构建的九个应用程序中的 138 个任务。通过使用 AndroidLab 环境，我们开发了一个安卓指令数据集，并训练了六个开源的 LLM 和 LMM，将 LLM 的平均成功率从 4.59%提升到 21.50%，将 LMM 的平均成功率从 1.93%提升到 13.28%。AndroidLab 是开源的，可在 https://github.com/THUDM/Android-Lab 公开获取。

> Autonomous agents have become increasingly important for interacting with the real world. Android agents, in particular, have been recently a frequently-mentioned interaction method. However, existing studies for training and evaluating Android agents lack systematic research on both open-source and closed-source models. In this work, we propose AndroidLab as a systematic Android agent framework. It includes an operation environment with different modalities, action space, and a reproducible benchmark. It supports both large language models (LLMs) and multimodal models (LMMs) in the same action space. AndroidLab benchmark includes predefined Android virtual devices and 138 tasks across nine apps built on these devices. By using the AndroidLab environment, we develop an Android Instruction dataset and train six open-source LLMs and LMMs, lifting the average success rates from 4.59% to 21.50% for LLMs and from 1.93% to 13.28% for LMMs. AndroidLab is open-sourced and publicly available at https://github.com/THUDM/Android-Lab.

[Arxiv](https://arxiv.org/abs/2410.24024)