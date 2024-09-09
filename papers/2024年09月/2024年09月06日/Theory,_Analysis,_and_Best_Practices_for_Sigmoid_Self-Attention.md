# 探索 Sigmoid 自注意力机制：理论、分析与最佳实践

发布时间：2024年09月06日

`LLM理论` `人工智能` `机器学习`

> Theory, Analysis, and Best Practices for Sigmoid Self-Attention

# 摘要

> 注意力机制是transformer架构的核心。它通过将每个序列元素转换为值的加权和来实现序列到序列的映射，其中权重通常由键和查询之间的点积的softmax函数计算得出。近期研究探索了transformer中softmax注意力的替代方案，如ReLU和sigmoid激活。我们重新审视了sigmoid注意力，并进行了深入的理论和实证分析。理论上，我们证明了具有sigmoid注意力的transformer是通用函数逼近器，且在规律性上优于softmax注意力。实证分析表明，训练初期大型初始注意力范数的稳定是成功训练sigmoid注意力模型的关键，优于以往尝试。我们还推出了FLASHSIGMOID，一种硬件感知且内存高效的sigmoid注意力实现，在H100 GPU上比FLASHATTENTION2提速17%。跨语言、视觉和语音的实验显示，适当归一化的sigmoid注意力在广泛领域和尺度上与softmax注意力性能相当，这是之前sigmoid注意力尝试未能完全实现的。我们的研究统一了先前技术，并为transformer中作为softmax替代品的sigmoid注意力确立了最佳实践。

> Attention is a key part of the transformer architecture. It is a sequence-to-sequence mapping that transforms each sequence element into a weighted sum of values. The weights are typically obtained as the softmax of dot products between keys and queries. Recent work has explored alternatives to softmax attention in transformers, such as ReLU and sigmoid activations. In this work, we revisit sigmoid attention and conduct an in-depth theoretical and empirical analysis. Theoretically, we prove that transformers with sigmoid attention are universal function approximators and benefit from improved regularity compared to softmax attention. Through detailed empirical analysis, we identify stabilization of large initial attention norms during the early stages of training as a crucial factor for the successful training of models with sigmoid attention, outperforming prior attempts. We also introduce FLASHSIGMOID, a hardware-aware and memory-efficient implementation of sigmoid attention yielding a 17% inference kernel speed-up over FLASHATTENTION2 on H100 GPUs. Experiments across language, vision, and speech show that properly normalized sigmoid attention matches the strong performance of softmax attention on a wide range of domains and scales, which previous attempts at sigmoid attention were unable to fully achieve. Our work unifies prior art and establishes best practices for sigmoid attention as a drop-in softmax replacement in transformers.

[Arxiv](https://arxiv.org/abs/2409.04431)