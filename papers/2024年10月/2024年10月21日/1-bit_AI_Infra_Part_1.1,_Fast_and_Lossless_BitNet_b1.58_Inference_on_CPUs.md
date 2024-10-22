# 1-bit AI 基础设施：第 1.1 部分，CPU 上的 BitNet b1.58 快速无损推理

发布时间：2024年10月21日

`LLM应用` `软件开发` `嵌入式系统`

> 1-bit AI Infra: Part 1.1, Fast and Lossless BitNet b1.58 Inference on CPUs

# 摘要

> 近期，1-bit大型语言模型（如BitNet和BitNet b1.58）的进步，为提升LLM的速度和能效提供了新途径，并支持在多种设备上本地部署。我们推出了bitnet.cpp，一个专为1-bit LLM设计的软件栈，旨在最大化其性能。特别地，我们开发了支持CPU上快速无损推断三元BitNet b1.58的内核。实验显示，bitnet.cpp在x86和ARM CPU上分别实现了2.37x至6.17x和1.37x至5.07x的速度提升。代码已开放，访问地址为https://github.com/microsoft/BitNet。

> Recent advances in 1-bit Large Language Models (LLMs), such as BitNet and BitNet b1.58, present a promising approach to enhancing the efficiency of LLMs in terms of speed and energy consumption. These developments also enable local LLM deployment across a broad range of devices. In this work, we introduce bitnet.cpp, a tailored software stack designed to unlock the full potential of 1-bit LLMs. Specifically, we develop a set of kernels to support fast and lossless inference of ternary BitNet b1.58 LLMs on CPUs. Extensive experiments demonstrate that bitnet.cpp achieves significant speedups, ranging from 2.37x to 6.17x on x86 CPUs and from 1.37x to 5.07x on ARM CPUs, across various model sizes. The code is available at https://github.com/microsoft/BitNet.

[Arxiv](https://arxiv.org/abs/2410.16144)