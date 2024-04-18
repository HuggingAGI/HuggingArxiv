# 我们提出了一种无损压缩算法，专为 Llama2 7B 模型的权重设计，压缩比接近1.5:1。此外，我们还开发了一种适用于卷积神经网络和大型语言模型的新型压缩数值数据类型，这些数据类型具备可变精度和可变范围的特性。

发布时间：2024年04月16日

`分类：LLM应用

这篇论文讨论了一种高效的无损压缩技术，用于压缩大型语言模型Llama2 7B的权重。这种技术可以在AMD FPGA上实现，并且能够处理大量的bfloat16数值。此外，论文还探讨了一种基于ANS的硬件实现方案，以及如何利用权重压缩和共享的令牌工厂实例。这些内容都与大型语言模型（LLM）的应用相关，因此这篇论文应该被归类为LLM应用。` `硬件加速`

> From a Lossless (~1.5:1) Compression Algorithm for Llama2 7B Weights to Variable Precision, Variable Range, Compressed Numeric Data Types for CNNs and LLMs

# 摘要

> 本文提出了一种高效的无损压缩技术，将大型语言模型Llama2 7B的权重以1.5:1的比例进行压缩，该技术可在AMD FPGA上实现，通过约200个查找表（LUTs）每秒处理超过8亿个bfloat16数值。该技术框架进一步扩展至支持用户自定义的、包含浮点数和位置数的可变精度和范围的压缩数值数据类型。文章还探讨了一种基于ANS的硬件实现方案，它不仅作为灵活数据格式与计算引擎之间的桥梁，还能有效降低带宽需求。此外，文中还展示了一个利用权重压缩和共享的令牌工厂实例。

> This paper starts with a simple lossless ~1.5:1 compression algorithm for the weights of the Large Language Model (LLM) Llama2 7B [1] that can be implemented in ~200 LUTs in AMD FPGAs, processing over 800 million bfloat16 numbers per second. This framework is then extended to variable precision, variable range, compressed numerical data types that are a user defined super set of both floats and posits [2]. The paper then discusses a simple hardware implementation of such format based on ANS (Asymmetrical Numeral Systems) [3] that acts as a bridge between this flexible data format and a computational engine while, at the same time, achieving bandwidth reduction. An example of a token factory using weight compression and sharing is also given.

[Arxiv](https://arxiv.org/abs/2404.10896)