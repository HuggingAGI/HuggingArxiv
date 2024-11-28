# 用于上下文学习的课程演示选择

发布时间：2024年11月27日

`LLM应用` `语言模型` `课程学习`

> Curriculum Demonstration Selection for In-Context Learning

# 摘要

> 大型语言模型（LLMs）凭借少量示例展现出强大的上下文学习（ICL）能力。然而，关键难题在于如何挑选示例来充分挖掘 LLMs 的潜力。本文中，我们提出了课程示例选择（CDS）这一用于 ICL 的全新示例选择方法。CDS 并非单纯依靠相似度，还依据复杂性度量对样本进行划分。遵循课程学习的思路，CDS 由易到难进行示例选择。如此一来，所选示例涵盖了广泛的难度层次，让 LLMs 能够从训练集中的不同复杂程度中学习。实验证明，我们的 CDS 始终优于基线方法，在三个基准测试中的九个 LLMs 上均实现了显著提升。而且，CDS 在增强 LLMs 解决难题的性能方面效果尤为显著。

> Large Language Models (LLMs) have shown strong in-context learning (ICL) abilities with a few demonstrations. However, one critical challenge is how to select demonstrations to elicit the full potential of LLMs. In this paper, we propose Curriculum Demonstration Selection (CDS), a novel demonstration selection method for ICL. Instead of merely using similarity, CDS additionally partitions samples by their complexity measurements. Following curriculum learning, CDS then selects demonstrations from easy to difficult. Thus the selected demonstrations cover a wide range of difficulty levels, enabling LLMs to learn from varied complexities within the training set. Experiments demonstrate that our CDS consistently outperforms baseline methods, achieving notable improvements across nine LLMs on three benchmarks. Moreover, CDS proves especially effective in enhancing LLM performance in solving challenging problems.

[Arxiv](https://arxiv.org/abs/2411.18126)