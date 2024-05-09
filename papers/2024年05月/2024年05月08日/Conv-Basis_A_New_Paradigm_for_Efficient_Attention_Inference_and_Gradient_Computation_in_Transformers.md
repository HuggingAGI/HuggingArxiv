# Conv-Basis：开创Transformer高效注意力推理与梯度计算的新纪元在这项研究中，我们提出了一种名为Conv-Basis的新方法，它为Transformer模型中的注意力推理和梯度计算提供了一种更为高效的处理方式。通过引入这一新范式，我们旨在优化Transformer的计算效率，同时保持其在自然语言处理任务中的卓越性能。

发布时间：2024年05月08日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）中的自注意力机制及其计算成本问题，并提出了一种基于卷积结构的高效近似计算方法。这种方法旨在解决自注意力机制在处理长上下文时的计算瓶颈，通过引入卷积基系统和快速傅里叶变换（FFT）来降低计算复杂度。由于这项工作专注于LLMs的理论层面，特别是其核心机制的优化和改进，因此它属于LLM理论分类。` `机器学习`

> Conv-Basis: A New Paradigm for Efficient Attention Inference and Gradient Computation in Transformers

# 摘要

> 大型语言模型（LLMs）的变革力量源自其自注意力机制，但这一机制的二次计算成本O(n^2)却成为扩展至更长上下文的绊脚石。本研究巧妙地利用了注意力矩阵的卷积结构，提出了一种高效的近似计算方法，通过“conv”基系统将复杂的注意力矩阵分解为多个结构化的卷积矩阵。借助快速傅里叶变换（FFT），我们的算法实现了近线性时间复杂度，大幅降低了计算负担。这一创新不仅避免了显式计算庞大的注意力矩阵，还适用于各种输入矩阵，为变压器在处理更长上下文时提供了加速的新途径。

> Large Language Models (LLMs) have profoundly changed the world. Their self-attention mechanism is the key to the success of transformers in LLMs. However, the quadratic computational cost $O(n^2)$ to the length $n$ input sequence is the notorious obstacle for further improvement and scalability in the longer context. In this work, we leverage the convolution-like structure of attention matrices to develop an efficient approximation method for attention computation using convolution matrices. We propose a $\mathsf{conv}$ basis system, "similar" to the rank basis, and show that any lower triangular (attention) matrix can always be decomposed as a sum of $k$ structured convolution matrices in this basis system. We then design an algorithm to quickly decompose the attention matrix into $k$ convolution matrices. Thanks to Fast Fourier Transforms (FFT), the attention {\it inference} can be computed in $O(knd \log n)$ time, where $d$ is the hidden dimension. In practice, we have $ d \ll n$, i.e., $d=3,072$ and $n=1,000,000$ for Gemma. Thus, when $kd = n^{o(1)}$, our algorithm achieve almost linear time, i.e., $n^{1+o(1)}$. Furthermore, the attention {\it training forward} and {\it backward gradient} can be computed in $n^{1+o(1)}$ as well. Our approach can avoid explicitly computing the $n \times n$ attention matrix, which may largely alleviate the quadratic computational complexity. Furthermore, our algorithm works on any input matrices. This work provides a new paradigm for accelerating attention computation in transformers to enable their application to longer contexts.

[Arxiv](https://arxiv.org/abs/2405.05219)