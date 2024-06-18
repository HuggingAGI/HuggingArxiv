# 基于 Llama.cpp，优化 Armv9 架构下的大型语言模型推理性能在

发布时间：2024年06月16日

`LLM应用

这篇论文主要讨论了通过Int8量化和优化编译脚本来提升Qwen-1.8B模型的推理效率，包括提高预填充和解码速度，减少内存消耗，同时保持精度损失最小化。这些内容属于对大型语言模型（LLM）的具体应用和优化，因此归类为LLM应用。` `人工智能` `高性能计算`

> Optimization of Armv9 architecture general large language model inference performance based on Llama.cpp

# 摘要

> 通过Int8量化、向量化llama.cpp中的部分操作符，并调整编译脚本以增强编译器优化，本文显著提升了Qwen-1.8B模型的推理效率。在Yitian 710平台上，预填充速度提高至原来的1.6倍，解码速度更是飙升至24倍，同时内存消耗减少至原先的1/5，而精度损失微乎其微。

> This article optimizes the inference performance of the Qwen-1.8B model by performing Int8 quantization, vectorizing some operators in llama.cpp, and modifying the compilation script to improve the compiler optimization level. On the Yitian 710 experimental platform, the prefill performance is increased by 1.6 times, the decoding performance is increased by 24 times, the memory usage is reduced to 1/5 of the original, and the accuracy loss is almost negligible.

[Arxiv](https://arxiv.org/abs/2406.10816)