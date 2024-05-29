# I-LLM：高效整数推理，助力全量化低比特大型语言模型

发布时间：2024年05月28日

`LLM应用

这篇论文主要关注的是大型语言模型（LLMs）的整数量化技术，特别是通过后训练量化（PTQ）技术来加速推理过程。论文提出了一种名为I-LLM的框架，该框架通过创新的方法解决了LLMs整数量化的挑战，包括减少激活和权重间的通道差异，以及优化全整数矩阵乘法等。这些技术旨在提高LLMs在边缘和云设备上的应用效率。因此，这篇论文属于LLM应用类别，因为它专注于实际应用中的技术改进和优化。` `边缘计算` `云计算`

> I-LLM: Efficient Integer-Only Inference for Fully-Quantized Low-Bit Large Language Models

# 摘要

> 后训练量化（PTQ）技术极大地加速了大型语言模型（LLMs）的推理过程。尽管如此，现有方法在推理时仍需大量浮点操作，包括量化、去量化及RMSNorm和Softmax等非线性运算，这限制了LLMs在边缘和云设备上的应用。本文揭示了LLMs整数量化的主要挑战——线性和非线性操作中激活值在不同通道和令牌间的剧烈波动。为此，我们创新性地提出了I-LLM框架，一种专为LLMs定制的全整数量化PTQ方案。首先，我们通过全平滑块重建（FSBR）技术，大幅减少激活和权重间的通道差异。其次，针对令牌间的波动问题，我们开发了动态整数矩阵乘法（DI-MatMul），实现输入输出的动态量化，优化全整数矩阵乘法。最后，我们设计了DI-ClippedSoftmax、DI-Exp和DI-Normalization等高效非线性操作，通过位移操作保持运算精度。实验证明，I-LLM在保持与浮点基线相当的精度的同时，超越了非整数量化方法，如在W4A4配置下几乎无精度损失。我们首次成功将整数量化应用于LLMs，并已将代码公开于anonymous.4open.science，以期推动该领域的发展。

> Post-training quantization (PTQ) serves as a potent technique to accelerate the inference of large language models (LLMs). Nonetheless, existing works still necessitate a considerable number of floating-point (FP) operations during inference, including additional quantization and de-quantization, as well as non-linear operators such as RMSNorm and Softmax. This limitation hinders the deployment of LLMs on the edge and cloud devices. In this paper, we identify the primary obstacle to integer-only quantization for LLMs lies in the large fluctuation of activations across channels and tokens in both linear and non-linear operations. To address this issue, we propose I-LLM, a novel integer-only fully-quantized PTQ framework tailored for LLMs. Specifically, (1) we develop Fully-Smooth Block-Reconstruction (FSBR) to aggressively smooth inter-channel variations of all activations and weights. (2) to alleviate degradation caused by inter-token variations, we introduce a novel approach called Dynamic Integer-only MatMul (DI-MatMul). This method enables dynamic quantization in full-integer matrix multiplication by dynamically quantizing the input and outputs with integer-only operations. (3) we design DI-ClippedSoftmax, DI-Exp, and DI-Normalization, which utilize bit shift to execute non-linear operators efficiently while maintaining accuracy. The experiment shows that our I-LLM achieves comparable accuracy to the FP baseline and outperforms non-integer quantization methods. For example, I-LLM can operate at W4A4 with negligible loss of accuracy. To our knowledge, we are the first to bridge the gap between integer-only quantization and LLMs. We've published our code on anonymous.4open.science, aiming to contribute to the advancement of this field.

[Arxiv](https://arxiv.org/abs/2405.17849)