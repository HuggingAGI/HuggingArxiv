# 探究稀疏自编码器中的最优推理及可证明的摊销差距

发布时间：2024年11月20日

`LLM应用` `神经网络` `机器学习`

> Compute Optimal Inference and Provable Amortisation Gap in Sparse Autoencoders

# 摘要

> 最近一系列的工作显示，运用稀疏自编码器（SAEs）来揭示神经网络表征中的可解释特征颇具前景。但SAEs中简单的线性-非线性编码机制限制了其进行精准稀疏推理的能力。在本文中，我们借由稀疏编码的视角探究SAEs中的稀疏推理与学习。具体而言，我们指出SAEs通过计算受限的编码器进行摊销式稀疏推理，运用压缩感知理论，我们证实这种映射即便在可解情形下对于精确稀疏推理也是本质上不够的。基于此理论，我们通过实验探寻更复杂的稀疏推理方法优于传统SAE编码器的条件。我们的关键贡献在于将编码与解码过程分离，从而能够对各种稀疏编码策略进行比较。我们从两个维度评估这些策略：与真实底层稀疏特征的一致性以及稀疏代码的正确推理，同时也考虑了训练和推理时的计算成本。我们的成果表明，在计算成本增加极少的情况下能够达成显著的性能提升。我们证明这能推广至应用于大型语言模型（LLMs）的SAEs，其中先进的编码器实现了类似的可解释性。此项工作为理解神经网络表征开辟了新新路，也为改进我们用于分析大型语言模型激活的工具带来了重要启示。

> A recent line of work has shown promise in using sparse autoencoders (SAEs) to uncover interpretable features in neural network representations. However, the simple linear-nonlinear encoding mechanism in SAEs limits their ability to perform accurate sparse inference. In this paper, we investigate sparse inference and learning in SAEs through the lens of sparse coding. Specifically, we show that SAEs perform amortised sparse inference with a computationally restricted encoder and, using compressed sensing theory, we prove that this mapping is inherently insufficient for accurate sparse inference, even in solvable cases. Building on this theory, we empirically explore conditions where more sophisticated sparse inference methods outperform traditional SAE encoders. Our key contribution is the decoupling of the encoding and decoding processes, which allows for a comparison of various sparse encoding strategies. We evaluate these strategies on two dimensions: alignment with true underlying sparse features and correct inference of sparse codes, while also accounting for computational costs during training and inference. Our results reveal that substantial performance gains can be achieved with minimal increases in compute cost. We demonstrate that this generalises to SAEs applied to large language models (LLMs), where advanced encoders achieve similar interpretability. This work opens new avenues for understanding neural network representations and offers important implications for improving the tools we use to analyse the activations of large language models.

[Arxiv](https://arxiv.org/abs/2411.13117)