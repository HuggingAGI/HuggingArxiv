# 文艺复兴：研究视觉语言编码器的预训练

发布时间：2024年11月10日

`LLM应用` `视觉语言` `模型训练`

> Renaissance: Investigating the Pretraining of Vision-Language Encoders

# 摘要

> 在过去的几年里，用于视觉语言任务的可用模型数量激增。不幸的是，文献中仍然存在许多与设计和训练此类模型的最佳实践相关的问题。在本文中，我们试图通过元分析来回答与视觉语言编码器的预训练相关的几个问题。在我们的第一组实验中，我们表明，在预训练期间冻结视觉语言模型的大部分，可以在不影响下游性能的情况下节省大量计算。在我们的第二组实验中，我们研究了基于视觉模型与基于文本模型的 VL 转换器的效果。此外，我们引入了一个名为 Renaissance 的 VL 建模平台，用于进行所有实验。这个程序在创建、训练和评估用于 VL 建模的转换器编码器方面提供了极大的灵活性。Renaissance 的源代码可以在 https://github.com/bsu-slim/renaissance 找到。

> In the past several years there has been an explosion of available models for vision-language tasks. Unfortunately, the literature still leaves open a number of questions related to best practices in designing and training such models. In this paper we seek to answer several questions related to the pretraining of vision-language encoders through meta-analysis. In our first set of experiments, we show that we can save significant compute at no cost to downstream performance, by freezing large parts of vision-language models during pretraining. In our second set of experiments we examine the effect of basing a VL transformer on a vision model versus a text model. Additionally, we introduce a VL modeling platform called Renaissance that we use to conduct all of the experiments. This program offers a great deal of flexibility in creating, training and evaluating transformer encoders for VL modeling. The source code for Renaissance can be found at https://github.com/bsu-slim/renaissance.

[Arxiv](https://arxiv.org/abs/2411.06657)