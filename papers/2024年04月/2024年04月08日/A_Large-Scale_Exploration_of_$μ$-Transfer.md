# 本研究进行了对 $μ$-转移的大规模探索，旨在深入理解其在不同情境下的应用和影响。

发布时间：2024年04月08日

`LLM理论` `计算机视觉`

> A Large-Scale Exploration of $μ$-Transfer

# 摘要

> 大型神经网络模型在自然语言处理和计算机视觉领域已成为核心，但其初始化和学习率的设定往往依赖于经验，且可能因文献和模型规模的不同而有所差异。$μ$-参数化（$μ$P）提出了一种可能的解决之道，为模型的初始化和学习率提供了一套缩放准则，并据称能在多种情况下实现超参数的零-shot迁移，从小型模型到大型模型。尽管$μ$P的潜力显而易见，但由于实施的复杂性、多变性以及理论基础的深奥，这一方法尚未普及。本研究通过实证分析，聚焦于普遍应用的变换器架构，试图解答一个关键问题：$μ$-转移在实际应用中是否真的能够带来最佳的学习率？我们从参数量为200万到100亿不等的模型中发现，$μ$-转移在大多数关键场景下都能如预期般发挥作用，同时也揭示了一些出人意料的案例，其中$μ$-转移并未达到最佳效果。

> Large neural network models have become a mainstay of natural language processing and computer vision, yet their initialization and learning rates are set in a largely heuristic fashion, potentially varying from paper to paper and one model size to the next. The $μ$-Parameterization ($μ$P) offers a potential solution to these challenges, yielding scaling rules for model initialization and learning rates, and reportedly enabling zero-shot hyperparameter transfer from small to large models in a variety of cases.
  Despite the evident promise, the $μ$P scaling rules are not yet widely adopted, perhaps due to higher implementation complexity, many variations, or complex theoretical background. This work investigates $μ$P empirically, focusing on the ubiquitous transformer architecture, and aims to answer a simple question: does $μ$-Transfer yield optimal learning rates in practice? From models with 2M to 10B parameters, we show that $μ$-Transfer works as intended for the majority of important cases, but also identify some surprising cases where it may not.

[Arxiv](https://arxiv.org/abs/2404.05728)