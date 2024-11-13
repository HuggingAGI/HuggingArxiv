# ASER：用于大型语言模型量化的激活平滑和错误重建

发布时间：2024年11月12日

`LLM应用` `模型压缩` `语言模型`

> ASER: Activation Smoothing and Error Reconstruction for Large Language Model Quantization

# 摘要

> 量化是大型语言模型（LLM）服务的关键技术，但它带来了重大挑战，特别是在实现有效的低位量化方面。有限的数值映射使量化模型产生了不小的误差，导致无法忍受的性能下降。本文基于模型压缩目标的基本思想，深入研究了 LLM 在训练后量化过程中的逐层误差分布。随后，我们引入了 ASER，这是一种算法，包括（1）误差重建：用通过白化 SVD 构建的 LoRA 风格矩阵对量化误差进行低秩补偿；（2）激活平滑：提取异常值以获得平滑的激活和更好的误差补偿。ASER 能够将典型的 LLM 量化为低位模型，特别是在 W4A8 每通道设置中仍能保持准确性。实验结果表明，ASER 在最先进的量化算法中具有竞争力，对激活量化显示出潜力，且开销较小。

> Quantization stands as a pivotal technique for large language model (LLM) serving, yet it poses significant challenges particularly in achieving effective low-bit quantization. The limited numerical mapping makes the quantized model produce a non-trivial error, bringing out intolerable performance degration. This paper is anchored in the basic idea of model compression objectives, and delves into the layer-wise error distribution of LLMs during post-training quantization. Subsequently, we introduce ASER, an algorithm consisting of (1) Error Reconstruction: low-rank compensation for quantization error with LoRA-style matrices constructed by whitening SVD; (2) Activation Smoothing: outlier extraction to gain smooth activation and better error compensation. ASER is capable of quantizing typical LLMs to low-bit ones, particularly preserving accuracy even in W4A8 per-channel setup. Experimental results show that ASER is competitive among the state-of-the-art quantization algorithms, showing potential to activation quantization, with minor overhead.

[Arxiv](https://arxiv.org/abs/2411.07762)