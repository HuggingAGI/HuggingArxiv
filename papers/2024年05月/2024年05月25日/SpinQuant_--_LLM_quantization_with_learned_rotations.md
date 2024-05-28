# SpinQuant - 利用学习旋转技术优化大型语言模型的量化过程

发布时间：2024年05月25日

`LLM理论

理由：这篇论文主要探讨了后训练量化（PTQ）技术在大型语言模型（LLMs）中的应用，特别是在处理权重、激活和KV缓存时的量化误差问题。论文提出了一种新的方法SpinQuant，通过旋转参数化来优化量化效果，并详细讨论了其性能和效果。这些内容更多地涉及LLM的理论和内部机制优化，而不是直接的应用或Agent行为，因此归类为LLM理论。` `人工智能` `量化技术`

> SpinQuant -- LLM quantization with learned rotations

# 摘要

> 后训练量化（PTQ）技术通过处理权重、激活和KV缓存，大幅降低了大型语言模型（LLMs）的内存需求、延迟和能耗，但当数据中出现异常值时，可能会引发显著的量化误差。近期研究表明，通过旋转激活或权重矩阵可以有效剔除异常值，从而优化量化效果。在本研究中，我们发现了一系列适用于旋转参数化的方法，这些方法在全精度Transformer模型中能产生一致的输出结果。我们进一步发现，某些随机旋转策略在量化效果上远超其他策略，导致下游零-shot推理性能差距可达13分。基于此，我们开发了SpinQuant，一种通过在小验证集上应用Cayley优化来学习最佳旋转矩阵的方法。SpinQuant通过4位量化处理权重、激活和KV缓存，成功将零-shot推理任务上的全精度精度差距缩小至2.9分，在LLaMA-2 7B模型上超越了LLM-QAT 19.1分和SmoothQuant 25.0分。此外，SpinQuant在性能上也优于同时期的QuaRot方法，后者通过随机旋转来处理异常值。尤其对于量化难度较大的LLaMA-2 7B和LLaMA-3 8B模型，SpinQuant相比QuaRot分别将全精度差距降低了30.2%和34.1%。

> Post-training quantization (PTQ) techniques applied to weights, activations, and the KV cache greatly reduce memory usage, latency, and power consumption of Large Language Models (LLMs), but may lead to large quantization errors when outliers are present. Recent findings suggest that rotating activation or weight matrices helps remove outliers and benefits quantization. In this work, we identify a collection of applicable rotation parameterizations that lead to identical outputs in full-precision Transformer architectures, and find that some random rotations lead to much better quantization than others, with an up to 13 points difference in downstream zero-shot reasoning performance. As a result, we propose SpinQuant that optimizes (or learns) the rotation matrices with Cayley optimization on a small validation set. With 4-bit quantization of weight, activation, and KV-cache, SpinQuant narrows the accuracy gap on zero-shot reasoning tasks with full precision to merely 2.9 points on the LLaMA-2 7B model, surpassing LLM-QAT by 19.1 points and SmoothQuant by 25.0 points. SpinQuant also outperforms concurrent work QuaRot, which applies random rotations to remove outliers. In particular, for LLaMA-2 7B/LLaMA-3 8B models that are hard to quantize, SpinQuant reduces the gap to full precision by 30.2%/34.1% relative to QuaRot.

[Arxiv](https://arxiv.org/abs/2405.16406)