# 稀疏自编码器揭示了跨大型语言模型的通用特征空间

发布时间：2024年10月09日

`LLM理论` `人工智能`

> Sparse Autoencoders Reveal Universal Feature Spaces Across Large Language Models

# 摘要

> 我们探讨了 LLM 中的特征普遍性，旨在理解不同模型如何在中间层的潜在空间中相似地表示概念。展示这种普遍性有助于跨模型泛化潜在表示的发现。然而，由于多义性，比较 LLM 间的特征颇具挑战，因为单个神经元常对应多个特征。为解决这一难题，我们采用字典学习，通过稀疏自编码器 (SAE) 将 LLM 激活转换为更具解释性的空间。通过激活相关性匹配特征神经元后，我们运用表示空间相似性度量，如奇异值典型相关分析，分析不同 LLM 间的 SAE 特征。实验结果显示，各种 LLM 的 SAE 特征空间存在显著相似性，为特征普遍性提供了新证据。

> We investigate feature universality in large language models (LLMs), a research field that aims to understand how different models similarly represent concepts in the latent spaces of their intermediate layers. Demonstrating feature universality allows discoveries about latent representations to generalize across several models. However, comparing features across LLMs is challenging due to polysemanticity, in which individual neurons often correspond to multiple features rather than distinct ones. This makes it difficult to disentangle and match features across different models. To address this issue, we employ a method known as dictionary learning by using sparse autoencoders (SAEs) to transform LLM activations into more interpretable spaces spanned by neurons corresponding to individual features. After matching feature neurons across models via activation correlation, we apply representational space similarity metrics like Singular Value Canonical Correlation Analysis to analyze these SAE features across different LLMs. Our experiments reveal significant similarities in SAE feature spaces across various LLMs, providing new evidence for feature universality.

[Arxiv](https://arxiv.org/abs/2410.06981)