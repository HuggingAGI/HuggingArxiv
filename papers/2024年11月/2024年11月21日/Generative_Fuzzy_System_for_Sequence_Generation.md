# 用于序列生成的生成式模糊系统

发布时间：2024年11月21日

`LLM应用` `机器学习` `人工智能`

> Generative Fuzzy System for Sequence Generation

# 摘要

> 生成式模型（GMs），尤其是大型语言模型（LLMs），凭借能学习训练数据的统计特性从而生成类似原始数据的能力，在机器学习和人工智能领域备受瞩目，其应用广泛涵盖各个领域。然而，GMs 复杂的结构和众多的模型参数致使输入输出过程不透明，加大了对输出的理解和控制难度。而且，纯数据驱动的学习机制限制了 GM 获取更广泛知识的能力，GMs 在鲁棒性和泛化能力的提升方面仍潜力巨大。在本研究中，我们把融合数据和知识驱动机制的经典建模方法——模糊系统引入生成任务。我们提出了一个全新的生成式模糊系统框架，名为 GenFS，它将 GM 的深度学习能力与模糊系统的可解释性及双驱动机制相融合。具体而言，我们提出了一个基于端到端 GenFS 的序列生成模型，叫做 FuzzyS2S。针对 12 个数据集开展了一系列实验研究，涵盖机器翻译、代码生成和摘要生成这三类不同的生成任务。结果显示，FuzzyS2S 在准确性和流畅性上优于 Transformer。此外，和最先进的模型 T5 及 CodeT5 相比，它在部分数据集上表现更优。

> Generative Models (GMs), particularly Large Language Models (LLMs), have garnered significant attention in machine learning and artificial intelligence for their ability to generate new data by learning the statistical properties of training data and creating data that resemble the original. This capability offers a wide range of applications across various domains. However, the complex structures and numerous model parameters of GMs make the input-output processes opaque, complicating the understanding and control of outputs. Moreover, the purely data-driven learning mechanism limits GM's ability to acquire broader knowledge. There remains substantial potential for enhancing the robustness and generalization capabilities of GMs. In this work, we introduce the fuzzy system, a classical modeling method that combines data and knowledge-driven mechanisms, to generative tasks. We propose a novel Generative Fuzzy System framework, named GenFS, which integrates the deep learning capabilities of GM with the interpretability and dual-driven mechanisms of fuzzy systems. Specifically, we propose an end-to-end GenFS-based model for sequence generation, called FuzzyS2S. A series of experimental studies were conducted on 12 datasets, covering three distinct categories of generative tasks: machine translation, code generation, and summary generation. The results demonstrate that FuzzyS2S outperforms the Transformer in terms of accuracy and fluency. Furthermore, it exhibits better performance on some datasets compared to state-of-the-art models T5 and CodeT5.

[Arxiv](https://arxiv.org/abs/2411.13867)