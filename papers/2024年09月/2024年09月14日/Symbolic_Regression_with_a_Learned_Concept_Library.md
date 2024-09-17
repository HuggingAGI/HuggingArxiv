# 借助学习概念库的符号回归

发布时间：2024年09月14日

`LLM理论` `人工智能` `数据科学`

> Symbolic Regression with a Learned Concept Library

# 摘要

> 我们提出了一种创新的符号回归方法，旨在寻找能够最佳解释数据集的紧凑程序化假设。传统上，这一问题通过遗传算法解决，但我们通过引入抽象文本概念库，显著提升了这些方法的性能。我们的算法 LaSR 利用大型语言模型的零-shot 查询，发现并进化已知高性能假设中的概念。通过结合标准进化步骤和 LLM 引导步骤，我们能够发现新的假设，并将其用于新一轮的概念抽象和进化。实验证明，LaSR 在费曼方程和合成任务等基准测试中，显著超越了现有的最先进方法。此外，LaSR 还揭示了 LLM 的新颖且强大的缩放定律。

> We present a novel method for symbolic regression (SR), the task of searching for compact programmatic hypotheses that best explain a dataset. The problem is commonly solved using genetic algorithms; we show that we can enhance such methods by inducing a library of abstract textual concepts. Our algorithm, called LaSR, uses zero-shot queries to a large language model (LLM) to discover and evolve concepts occurring in known high-performing hypotheses. We discover new hypotheses using a mix of standard evolutionary steps and LLM-guided steps (obtained through zero-shot LLM queries) conditioned on discovered concepts. Once discovered, hypotheses are used in a new round of concept abstraction and evolution. We validate LaSR on the Feynman equations, a popular SR benchmark, as well as a set of synthetic tasks. On these benchmarks, LaSR substantially outperforms a variety of state-of-the-art SR approaches based on deep learning and evolutionary algorithms. Moreover, we show that LaSR can be used to discover a novel and powerful scaling law for LLMs.

[Arxiv](https://arxiv.org/abs/2409.09359)