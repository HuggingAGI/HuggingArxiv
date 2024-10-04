# 加密友好的大型语言模型架构

发布时间：2024年10月03日

`LLM应用` `隐私保护` `机器学习`

> Encryption-Friendly LLM Architecture

# 摘要

> LLM 通过用户交互提供个性化响应，但这也带来了严重的隐私问题。同态加密 (HE) 为隐私保护机器学习 (PPML) 提供了潜在解决方案，但其计算强度对应用于 LLM 构成挑战。我们提出了一种 HE 友好型变压器架构，重点在于个性化微调后的推理。通过 LoRA 微调和高斯核，我们在保持性能的同时，实现了显著的计算加速——微调加速 6.94 倍，推理加速 2.3 倍。这为在数据保护至关重要的领域提供隐私保护的 LLM 服务提供了可行性证明。

> Large language models (LLMs) offer personalized responses based on user interactions, but this use case raises serious privacy concerns. Homomorphic encryption (HE) is a cryptographic protocol supporting arithmetic computations in encrypted states and provides a potential solution for privacy-preserving machine learning (PPML). However, the computational intensity of transformers poses challenges for applying HE to LLMs. In this work, we propose a modified HE-friendly transformer architecture with an emphasis on inference following personalized (private) fine-tuning. Utilizing LoRA fine-tuning and Gaussian kernels, we achieve significant computational speedups -- 6.94x for fine-tuning and 2.3x for inference -- while maintaining performance comparable to plaintext models. Our findings provide a viable proof of concept for offering privacy-preserving LLM services in areas where data protection is crucial.

[Arxiv](https://arxiv.org/abs/2410.02486)