# LUT Tensor Core：通过查找表，实现低比特 LLM 推理的高效加速

发布时间：2024年08月12日

`LLM应用` `半导体` `人工智能`

> LUT Tensor Core: Lookup Table Enables Efficient Low-Bit LLM Inference Acceleration

# 摘要

> 随着LLM推理对资源的需求不断攀升，采用低比特权重以缩减内存占用和提升推理效率的趋势正迅速兴起。然而，这一趋势也催生了混合精度矩阵乘法（mpGEMM）的需求，这是一种关键但尚未深入探索的操作，涉及低精度权重与高精度激活的乘法。遗憾的是，现有硬件并不直接支持mpGEMM，导致其实现依赖于间接且低效的反量化方法。为应对这一挑战，我们探索了基于查找表（LUT）的mpGEMM方法。但传统LUT实现未能充分释放其潜能。为此，我们推出了LUT Tensor Core，这一软硬件协同设计旨在优化低比特LLM的推理性能。我们通过软件层面的算子融合与表对称化技术，分别优化了表的预计算与存储。在硬件层面，LUT Tensor Core采用了独特的延长分块形状设计以提升表的重用率，并引入了比特串行设计以灵活支持mpGEMM中的多种精度组合。此外，我们还构建了一套端到端的编译系统，为基于LUT的mpGEMM引入新指令，从而实现LLM的高效编译与优化。在BitNet、LLAMA等低比特LLM上的实测结果表明，LUT Tensor Core在计算密度与能效方面均实现了显著提升。

> As large language model (LLM) inference demands ever-greater resources, there is a rapid growing trend of using low-bit weights to shrink memory usage and boost inference efficiency. However, these low-bit LLMs introduce the need for mixed-precision matrix multiplication (mpGEMM), which is a crucial yet under-explored operation that involves multiplying lower-precision weights with higher-precision activations. Unfortunately, current hardware does not natively support mpGEMM, resulting in indirect and inefficient dequantization-based implementations.
  To address the mpGEMM requirements in low-bit LLMs, we explored the lookup table (LUT)-based approach for mpGEMM. However, a conventional LUT implementation falls short of its potential. To fully harness the power of LUT-based mpGEMM, we introduce LUT Tensor Core, a software-hardware co-design optimized for low-bit LLM inference. Specifically, we introduce software-based operator fusion and table symmetrization techniques to optimize table precompute and table storage, respectively. Then, LUT Tensor Core proposes the hardware design featuring an elongated tiling shape design to enhance table reuse and a bit-serial design to support various precision combinations in mpGEMM. Moreover, we design an end-to-end compilation stack with new instructions for LUT-based mpGEMM, enabling efficient LLM compilation and optimizations. The evaluation on low-bit LLMs (e.g., BitNet, LLAMA) shows that LUT Tensor Core achieves more than a magnitude of improvements on both compute density and energy efficiency.

[Arxiv](https://arxiv.org/abs/2408.06003)