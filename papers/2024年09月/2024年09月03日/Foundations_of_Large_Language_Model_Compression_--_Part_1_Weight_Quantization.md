# 大型语言模型压缩的基石 —— 第一章：权重量化

发布时间：2024年09月03日

`LLM理论` `计算机科学` `人工智能`

> Foundations of Large Language Model Compression -- Part 1: Weight Quantization

# 摘要

> 近年来，大型语言模型的压缩变得至关重要，旨在让这些模型在资源有限的设备上运行，降低计算成本，并减少对环境的影响。本文从凸优化视角出发，阐述了 LLM 量化的基础，并提出了一种新的量化方法，该方法在性能上超越了以往的技术。我们的量化框架 CVXQ 能够处理包含数千亿参数的模型，并允许用户在训练后灵活地将模型压缩至任意大小。CVXQ 的实现代码已公开，可从 https://github.com/seannz/cvxq 获取。

> In recent years, compression of large language models (LLMs) has emerged as an important problem to allow language model deployment on resource-constrained devices, reduce computational costs, and mitigate the environmental footprint of large-scale AI infrastructure. In this paper, we present the foundations of LLM quantization from a convex optimization perspective and propose a quantization method that builds on these foundations and outperforms previous methods. Our quantization framework, CVXQ, scales to models containing hundreds of billions of weight parameters and provides users with the flexibility to compress models to any specified model size, post-training. A reference implementation of CVXQ can be obtained from https://github.com/seannz/cvxq.

[Arxiv](https://arxiv.org/abs/2409.02026)