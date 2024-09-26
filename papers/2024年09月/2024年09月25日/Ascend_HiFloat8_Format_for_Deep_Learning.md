# 深度学习中的 Ascend HiFloat8 格式

发布时间：2024年09月25日

`LLM理论` `人工智能`

> Ascend HiFloat8 Format for Deep Learning

# 摘要

> 本白皮书介绍了一种创新的8位浮点格式HiF8，专为深度学习设计。HiF8采用锥形精度，正常值编码包括7个指数和3位尾数、8个指数和2位尾数、16个指数和1位尾数。对于非正规值，动态范围扩展至38个二进制位（FP16为40个）。HiF8编码所有特殊值，仅正负零共享一位模式。其精度和动态范围的平衡使其适用于AI训练的前后传递。本文详述HiF8的定义、舍入方法及初步训练推理方案，并通过多种神经网络（含LLMs）的模拟结果验证其效能。

> This preliminary white paper proposes a novel 8-bit floating-point data format HiFloat8 (abbreviated as HiF8) for deep learning. HiF8 features tapered precision. For normal value encoding, it provides 7 exponents with 3-bit mantissa, 8 exponents with 2-bit mantissa, and 16 exponents with 1-bit mantissa. For denormal or subnormal value encoding, it extends the dynamic range by 7 extra powers of 2, from 31 to 38 binades (notice that FP16 covers 40 binades). Meanwhile, HiF8 encodes all the special values except that positive zero and negative zero are represented by only one bit-pattern. Thanks to the better balance between precision and dynamic range, HiF8 can be simultaneously used in both forward and backward passes of AI training. In this paper, we will describe the definition and rounding methods of HiF8, as well as the tentative training and inference solutions. To demonstrate the efficacy of HiF8 format, massive simulation results on various neural networks, including traditional neural networks and large language models (LLMs), will also be presented.

[Arxiv](https://arxiv.org/abs/2409.16626)