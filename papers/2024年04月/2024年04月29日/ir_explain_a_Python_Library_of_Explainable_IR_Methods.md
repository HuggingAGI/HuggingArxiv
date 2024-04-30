# ir_explain：一款用于信息检索的可解释性方法的 Python 库

发布时间：2024年04月29日

`LLM应用` `信息检索` `可解释性`

> ir_explain: a Python Library of Explainable IR Methods

# 摘要

> 最新的神经排序模型在性能上取得了显著提升，超越了传统统计检索模型。然而，这也使得信息检索（IR）中的大型神经架构和复杂语言模型的应用变得不那么透明。因此，可解释性和可解释性成为了IR研究中的热点。本文介绍了\irexplain，一个开源的Python库，它为可解释的IR（ExIR）提供了一个统一且可扩展的框架，涵盖了点对点、成对和列表三种标准的事后解释方法。该库旨在简化在标准测试集上复现顶级ExIR基线的过程，并鼓励探索新的IR模型和方法的解释方式。为了促进其应用，\irexplain与流行的工具如Pyserini和\irdatasets实现了良好的集成。

> While recent advancements in Neural Ranking Models have resulted in significant improvements over traditional statistical retrieval models, it is generally acknowledged that the use of large neural architectures and the application of complex language models in Information Retrieval (IR) have reduced the transparency of retrieval methods. Consequently, Explainability and Interpretability have emerged as important research topics in IR. Several axiomatic and post-hoc explanation methods, as well as approaches that attempt to be interpretable-by-design, have been proposed. This article presents \irexplain, an open-source Python library that implements a variety of well-known techniques for Explainable IR (ExIR) within a common, extensible framework. \irexplain supports the three standard categories of post-hoc explanations, namely pointwise, pairwise, and listwise explanations. The library is designed to make it easy to reproduce state-of-the-art ExIR baselines on standard test collections, as well as to explore new approaches to explaining IR models and methods. To facilitate adoption, \irexplain is well-integrated with widely-used toolkits such as Pyserini and \irdatasets.

[Arxiv](https://arxiv.org/abs/2404.18546)