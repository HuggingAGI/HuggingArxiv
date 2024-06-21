# 注意力感知后训练量化：无需反向传播

发布时间：2024年06月19日

`LLM理论

这篇论文主要关注大型语言模型（LLMs）的量化技术，特别是在资源受限设备上的部署问题。论文提出了一种新的后训练量化（PTQ）算法，该算法通过开发注意力感知的Hessian矩阵来考虑层间依赖性，而不依赖于反向传播。这种研究属于LLM理论范畴，因为它探讨了LLMs内部机制和优化方法，而不是直接应用于特定的Agent或RAG系统，也不是关于LLM的具体应用案例。因此，它被归类为LLM理论。` `边缘计算` `机器学习`

> Attention-aware Post-training Quantization without Backpropagation

# 摘要

> 量化为在资源受限设备上部署大型语言模型（LLMs）提供了一条有希望的途径。然而，现有量化技术，无论是后训练量化（PTQ）还是量化感知训练（QAT），均依赖于基于梯度的优化，这对拥有数十亿参数的超大规模LLMs构成了挑战。近期提出的无需反向传播的PTQ方法虽能减轻这一负担，但其性能因未充分考虑层间依赖性而受限。本文提出了一种创新的PTQ算法，它通过开发注意力感知的Hessian矩阵，在不依赖反向传播的情况下考虑层间依赖性。实验证明，该算法在低比特宽度下显著超越了传统PTQ方法。

> Quantization is a promising solution for deploying large-scale language models (LLMs) on resource-constrained devices. Existing quantization approaches, however, rely on gradient-based optimization, regardless of it being post-training quantization (PTQ) or quantization-aware training (QAT), which becomes problematic for hyper-scale LLMs with billions of parameters. This overhead can be alleviated via recently proposed backpropagation-free PTQ methods; however, their performance is somewhat limited by their lack of consideration of inter-layer dependencies. In this paper, we thus propose a novel PTQ algorithm that considers inter-layer dependencies without relying on backpropagation. The fundamental concept involved is the development of attention-aware Hessian matrices, which facilitates the consideration of inter-layer dependencies within the attention module. Extensive experiments demonstrate that the proposed algorithm significantly outperforms conventional PTQ methods, particularly for low bit-widths.

![注意力感知后训练量化：无需反向传播](../../../paper_images/2406.13474/x1.png)

![注意力感知后训练量化：无需反向传播](../../../paper_images/2406.13474/x2.png)

[Arxiv](https://arxiv.org/abs/2406.13474)