# BitMoD：位串行数据类型混合式的 LLM 加速方案

发布时间：2024年11月18日

`LLM应用` `机器学习` `硬件设计`

> BitMoD: Bit-serial Mixture-of-Datatype LLM Acceleration

# 摘要

> 大型语言模型（LLMs）在各类机器学习任务中表现出色。但 LLMs 庞大的内存占用极大地限制了其部署。本文中，我们借助 BitMoD 提升了 LLMs 的可访问性，这是一种算法与硬件协同设计的解决方案，能在低权重精度下实现高效的 LLM 加速。算法层面，BitMoD 引入了精细的数据类型适配，用不同数值数据类型量化一组（如 128 个）权重。通过精心设计这些新数据类型，BitMoD 能将 LLM 权重量化至极低精度（如 4 位和 3 位），同时保持高准确率。硬件方面，BitMoD 采用位串行处理元件，轻松支持多种数值精度和数据类型；我们的硬件设计有两大关键创新：其一，采用统一表示处理不同权重数据类型，降低硬件成本。其二，采用位串行反量化单元，以最小硬件开销重新缩放每组的部分和。对六个代表性 LLMs 的评估显示，BitMoD 显著优于前沿的 LLM 量化和加速方法。对于判别任务，BitMoD 能将 LLM 权重量化至 4 位，平均精度损失小于 0.5%。对于生成任务，BitMoD 能将 LLM 权重量化至 3 位，同时困惑度优于之前的 LLM 量化方案。结合出色的模型性能和高效的加速器设计，与之前的 LLM 加速器 ANT 和 OliVe 相比，BitMoD 分别实现了平均 1.69 倍和 1.48 倍的加速。

> Large language models (LLMs) have demonstrated remarkable performance across various machine learning tasks. Yet the substantial memory footprint of LLMs significantly hinders their deployment. In this paper, we improve the accessibility of LLMs through BitMoD, an algorithm-hardware co-design solution that enables efficient LLM acceleration at low weight precision. On the algorithm side, BitMoD introduces fine-grained data type adaptation that uses a different numerical data type to quantize a group of (e.g., 128) weights. Through the careful design of these new data types, BitMoD is able to quantize LLM weights to very low precision (e.g., 4 bits and 3 bits) while maintaining high accuracy. On the hardware side, BitMoD employs a bit-serial processing element to easily support multiple numerical precisions and data types; our hardware design includes two key innovations: First, it employs a unified representation to process different weight data types, thus reducing the hardware cost. Second, it adopts a bit-serial dequantization unit to rescale the per-group partial sum with minimal hardware overhead. Our evaluation on six representative LLMs demonstrates that BitMoD significantly outperforms state-of-the-art LLM quantization and acceleration methods. For discriminative tasks, BitMoD can quantize LLM weights to 4-bit with $<\!0.5\%$ accuracy loss on average. For generative tasks, BitMoD is able to quantize LLM weights to 3-bit while achieving better perplexity than prior LLM quantization scheme. Combining the superior model performance with an efficient accelerator design, BitMoD achieves an average of $1.69\times$ and $1.48\times$ speedups compared to prior LLM accelerators ANT and OliVe, respectively.

[Arxiv](https://arxiv.org/abs/2411.11745)