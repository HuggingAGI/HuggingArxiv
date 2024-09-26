# INT-FlashAttention：让 INT8 量化也能闪耀光芒

发布时间：2024年09月25日

`LLM理论` `人工智能` `计算机硬件`

> INT-FlashAttention: Enabling Flash Attention for INT8 Quantization

# 摘要

> 自注意力模块作为 LLM 的基础，面临序列长度带来的二次时间和内存复杂度挑战。FlashAttention 通过利用 GPU 内存层次结构，加速计算并减少内存使用。本文提出 INT-FlashAttention，首个与 FlashAttention 前向流程兼容的 INT8 量化架构，显著提升 Ampere GPU 上的推理速度。我们采用完全 INT8 激活和通用矩阵乘法内核，使其成为首个完全 INT8 输入的注意力操作符。INT-FlashAttention 作为通用令牌级后训练量化框架，还兼容 INT4 等数据格式。实验表明，与标准 FlashAttention 相比，INT-FlashAttention 推理速度提升 72%，量化误差减少 82%，使用 FP16 和 FP8 数据格式。

> As the foundation of large language models (LLMs), self-attention module faces the challenge of quadratic time and memory complexity with respect to sequence length. FlashAttention accelerates attention computation and reduces its memory usage by leveraging the GPU memory hierarchy. A promising research direction is to integrate FlashAttention with quantization methods. This paper introduces INT-FlashAttention, the first INT8 quantization architecture compatible with the forward workflow of FlashAttention, which significantly improves the inference speed of FlashAttention on Ampere GPUs. We implement our INT-FlashAttention prototype with fully INT8 activations and general matrix-multiplication (GEMM) kernels, making it the first attention operator with fully INT8 input. As a general token-level post-training quantization framework, INT-FlashAttention is also compatible with other data formats like INT4, etc. Experimental results show INT-FlashAttention achieves 72% faster inference speed and 82% smaller quantization error compared to standard FlashAttention with FP16 and FP8 data format.

[Arxiv](https://arxiv.org/abs/2409.16997)