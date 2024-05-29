# I-LLM：全量化低比特大型语言模型的整数推理优化

发布时间：2024年05月28日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的整数量化技术，特别是通过后训练量化（PTQ）技术来加速推理过程。论文中提出的I-LLM框架，包括全平滑块重构（FSBR）、动态整数矩阵乘法（DI-MatMul）以及一系列高效的非线性操作（如DI-ClippedSoftmax、DI-Exp和DI-Normalization），都是为了解决LLMs在量化过程中遇到的挑战，如激活值的波动问题。这些创新方法旨在实现LLMs的整数量化，同时保持模型的精度。因此，这篇论文的内容更偏向于LLMs的理论研究和技术创新，而不是具体的应用或Agent的设计，也不涉及RAG（Retrieval-Augmented Generation）的相关内容。` `边缘计算` `云计算`

> I-LLM: Efficient Integer-Only Inference for Fully-Quantized Low-Bit Large Language Models

# 摘要

> 后训练量化（PTQ）技术极大地加速了大型语言模型（LLMs）的推理过程。尽管如此，现有方法在推理时仍需大量浮点操作，包括量化、去量化及非线性运算如RMSNorm和Softmax，这限制了LLMs在边缘和云设备的应用。本文揭示了LLMs整数量化的主要挑战——激活值在通道和令牌间的剧烈波动。为此，我们创新性地提出了I-LLM框架，专为LLMs量身定制的全量化PTQ方案。首先，我们通过全平滑块重构（FSBR）大幅减少通道间的激活波动；其次，引入动态整数矩阵乘法（DI-MatMul）以应对令牌间的变化；最后，设计了DI-ClippedSoftmax、DI-Exp和DI-Normalization等高效非线性操作，确保精度不受损。实验证明，I-LLM在保持精度的同时，显著优于传统非整数量化方法，如在W4A4配置下几乎无精度损失。我们首次实现了LLMs的整数量化，并将代码公开于anonymous.4open.science，以期推动该领域的发展。

> Post-training quantization (PTQ) serves as a potent technique to accelerate the inference of large language models (LLMs). Nonetheless, existing works still necessitate a considerable number of floating-point (FP) operations during inference, including additional quantization and de-quantization, as well as non-linear operators such as RMSNorm and Softmax. This limitation hinders the deployment of LLMs on the edge and cloud devices. In this paper, we identify the primary obstacle to integer-only quantization for LLMs lies in the large fluctuation of activations across channels and tokens in both linear and non-linear operations. To address this issue, we propose I-LLM, a novel integer-only fully-quantized PTQ framework tailored for LLMs. Specifically, (1) we develop Fully-Smooth Block-Reconstruction (FSBR) to aggressively smooth inter-channel variations of all activations and weights. (2) to alleviate degradation caused by inter-token variations, we introduce a novel approach called Dynamic Integer-only MatMul (DI-MatMul). This method enables dynamic quantization in full-integer matrix multiplication by dynamically quantizing the input and outputs with integer-only operations. (3) we design DI-ClippedSoftmax, DI-Exp, and DI-Normalization, which utilize bit shift to execute non-linear operators efficiently while maintaining accuracy. The experiment shows that our I-LLM achieves comparable accuracy to the FP baseline and outperforms non-integer quantization methods. For example, I-LLM can operate at W4A4 with negligible loss of accuracy. To our knowledge, we are the first to bridge the gap between integer-only quantization and LLMs. We've published our code on anonymous.4open.science, aiming to contribute to the advancement of this field.

[Arxiv](https://arxiv.org/abs/2405.17849)