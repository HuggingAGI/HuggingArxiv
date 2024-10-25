# 稀疏通用变压器

发布时间：2023年10月11日

`其他` `计算机技术`

> Sparse Universal Transformer

# 摘要

> 摘要：通用变压器（UT）是变压器的一种变体，其各层之间共享参数。经验证据表明，在形式语言任务中，UT 比香草变压器（VT）具有更好的组合泛化能力。参数共享也使它比 VT 具有更好的参数效率。尽管它有许多优点，但扩展 UT 参数比扩展 VT 在计算和内存方面要密集得多。本文提出了稀疏通用变压器（SUT），它利用稀疏专家混合（SMoE）和一种新的基于分拆的动态停止机制来降低 UT 的计算复杂度，同时保持其参数效率和泛化能力。实验表明，SUT 在 WMT'14 上仅使用一半的计算和参数就能达到与强基线模型相同的性能，并在形式语言任务（逻辑推理和 CFQ）上取得了强大的泛化结果。新的停止机制还能在推理过程中使计算量减少约 50％，而在形式语言任务上的性能下降非常小。

> 
Abstract:The Universal Transformer (UT) is a variant of the Transformer that shares parameters across its layers. Empirical evidence shows that UTs have better compositional generalization than Vanilla Transformers (VTs) in formal language tasks. The parameter-sharing also affords it better parameter efficiency than VTs. Despite its many advantages, scaling UT parameters is much more compute and memory intensive than scaling up a VT. This paper proposes the Sparse Universal Transformer (SUT), which leverages Sparse Mixture of Experts (SMoE) and a new stick-breaking-based dynamic halting mechanism to reduce UT's computation complexity while retaining its parameter efficiency and generalization ability. Experiments show that SUT achieves the same performance as strong baseline models while only using half computation and parameters on WMT'14 and strong generalization results on formal language tasks (Logical inference and CFQ). The new halting mechanism also enables around 50\% reduction in computation during inference with very little performance decrease on formal language tasks.
    

[Arxiv](https://arxiv.org/pdf/2310.07096)