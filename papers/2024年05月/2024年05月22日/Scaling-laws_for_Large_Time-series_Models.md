# 大型时间序列模型的规模化定律

发布时间：2024年05月22日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的扩展法则及其在时间序列预测中的应用。它研究了基础的仅解码器时间序列变换器模型与LLMs在扩展行为上的相似性，并确立了参数数量、数据集大小和训练计算之间的幂律缩放关系。这些内容属于对LLM理论的深入研究，因此应归类为LLM理论。` `时间序列预测` `数据分析`

> Scaling-laws for Large Time-series Models

# 摘要

> 大型语言模型（LLMs）的扩展法则为训练更大模型提供了指导，以实现可预测的性能提升。时间序列预测与语言结构相似，适合采用大规模变换器架构。我们发现，基础的仅解码器时间序列变换器模型与LLMs在扩展行为上相似，而架构细节（如宽高比和头数）在广泛范围内对性能影响不大。我们构建了一个包含多种时间序列数据的大型数据集，首次确立了参数数量、数据集大小和训练计算之间的幂律缩放关系，覆盖了五个数量级的范围。

> Scaling laws for large language models (LLMs) have provided useful guidance on how to train ever larger models for predictable performance gains. Time series forecasting shares a similar sequential structure to language, and is amenable to large-scale transformer architectures. Here we show that foundational decoder-only time series transformer models exhibit analogous scaling-behavior to LLMs, while architectural details (aspect ratio and number of heads) have a minimal effect over broad ranges. We assemble a large corpus of heterogenous time series data on which to train, and establish, for the first time, power-law scaling relations with respect to parameter count, dataset size, and training compute, spanning five orders of magnitude.

[Arxiv](https://arxiv.org/abs/2405.13867)