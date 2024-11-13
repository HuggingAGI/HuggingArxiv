# JanusFlow：协调自回归和整流流以实现统一的多模态理解和生成

发布时间：2024年11月12日

`LLM应用` `视觉语言模型`

> JanusFlow: Harmonizing Autoregression and Rectified Flow for Unified Multimodal Understanding and Generation

# 摘要

> 我们提出了 JanusFlow，一个强大的框架，它在一个单一的模型中统一了图像理解和生成。JanusFlow 引入了一种极简主义的架构，将自回归语言模型与整流流（生成建模中的一种最先进的方法）集成在一起。我们的关键发现表明，整流流可以在大型语言模型框架内直接训练，无需复杂的架构修改。为了进一步提高我们统一模型的性能，我们采用了两个关键策略：（i）将理解和生成编码器解耦，（ii）在统一训练期间对齐它们的表示。大量实验表明，JanusFlow 在各自的领域中达到了与专业模型相当或更优的性能，同时在标准基准测试中显著优于现有的统一方法。这项工作代表了朝着更高效和多功能的视觉语言模型迈出的一步。

> We present JanusFlow, a powerful framework that unifies image understanding and generation in a single model. JanusFlow introduces a minimalist architecture that integrates autoregressive language models with rectified flow, a state-of-the-art method in generative modeling. Our key finding demonstrates that rectified flow can be straightforwardly trained within the large language model framework, eliminating the need for complex architectural modifications. To further improve the performance of our unified model, we adopt two key strategies: (i) decoupling the understanding and generation encoders, and (ii) aligning their representations during unified training. Extensive experiments show that JanusFlow achieves comparable or superior performance to specialized models in their respective domains, while significantly outperforming existing unified approaches across standard benchmarks. This work represents a step toward more efficient and versatile vision-language models.

[Arxiv](https://arxiv.org/abs/2411.07975)