# 矩阵乘法中的最优量化

发布时间：2024年10月17日

`LLM理论` `机器学习` `信息论`

> Optimal Quantization for Matrix Multiplication

# 摘要

> 近期，机器学习领域提出了多种大型矩阵有损压缩（量化）方法。这种量化对加速矩阵乘法至关重要，而矩阵乘法是大型语言模型的核心，常受限于内存加载速度。不同于传统向量量化和率失真理论，这些新算法旨在近似矩阵乘积而非矩阵本身。具体而言，给定矩阵 $A,B$，编码器独立压缩每个矩阵，生成每条目 $R$ 比特的描述，解码器据此估计 $A^\top B$。我们为独立同分布高斯矩阵的近似均方误差提供了非渐近下界。算法上，我们基于嵌套格构造了通用量化器，确保任何矩阵对的近似误差仅依赖于 Frobenius 范数。对于高斯矩阵，该量化器达到下界，实现渐近最优。其实际低复杂度版本性能接近最优。信息论上，我们推导了高斯矩阵乘法的率失真函数。

> Recent work in machine learning community proposed multiple methods for performing lossy compression (quantization) of large matrices. This quantization is important for accelerating matrix multiplication (main component of large language models), which is often bottlenecked by the speed of loading these matrices from memory. Unlike classical vector quantization and rate-distortion theory, the goal of these new compression algorithms is to be able to approximate not the matrices themselves, but their matrix product. Specifically, given a pair of real matrices $A,B$ an encoder (compressor) is applied to each of them independently producing descriptions with $R$ bits per entry. These representations subsequently are used by the decoder to estimate matrix product $A^\top B$. In this work, we provide a non-asymptotic lower bound on the mean squared error of this approximation (as a function of rate $R$) for the case of matrices $A,B$ with iid Gaussian entries. Algorithmically, we construct a universal quantizer based on nested lattices with an explicit guarantee of approximation error for any (non-random) pair of matrices $A$, $B$ in terms of only Frobenius norms $\|A\|_F, \|B\|_F$ and $\|A^\top B\|_F$. For iid Gaussian matrices our quantizer achieves the lower bound and is, thus, asymptotically optimal. A practical low-complexity version of our quantizer achieves performance quite close to optimal. In information-theoretic terms we derive rate-distortion function for matrix multiplication of iid Gaussian matrices.

[Arxiv](https://arxiv.org/abs/2410.13780)