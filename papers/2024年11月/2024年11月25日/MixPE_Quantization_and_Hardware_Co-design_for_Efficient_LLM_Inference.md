# MixPE：针对高效 LLM 推理的量化与硬件协同设计

发布时间：2024年11月25日

`LLM应用` `计算机硬件` `人工智能`

> MixPE: Quantization and Hardware Co-design for Efficient LLM Inference

# 摘要

> 基于 Transformer 的大型语言模型（LLMs）在模型规模持续扩大的情况下取得了非凡成就，然而因其庞大的计算和内存需求，部署仍困难重重。量化成为颇具前景的解决之法，针对 LLMs 的前沿量化算法引入了混合精度矩阵乘法（mpGEMM）的需求，即低精度权重与高精度激活相乘。尽管有其好处，但当下的硬件加速器，像 GPU 和 TPU 等，对高效的 mpGEMM 缺乏原生支持，致使主顺序循环中的反量化操作效率低下。为突破这一局限，我们推出了 MixPE，这是专为 LLM 推理中的高效低位量化而设计的专用混合精度处理单元。MixPE 借助两项关键创新来降低反量化开销，充分发挥低位量化的潜力。其一，鉴于每个量化组内的比例和零点是共享的，我们提议在每组 mpGEMM 之后进行反量化，大幅减少反量化开销。其二，MixPE 不依赖传统乘法器，而是采用高效的移位和加法操作来实现乘法，优化了计算和能源效率。我们的实验结果显示，MixPE 比最先进的量化加速器速度提升 2.6 倍，能源消耗降低 1.4 倍。

> Transformer-based large language models (LLMs) have achieved remarkable success as model sizes continue to grow, yet their deployment remains challenging due to significant computational and memory demands. Quantization has emerged as a promising solution, and state-of-the-art quantization algorithms for LLMs introduce the need for mixed-precision matrix multiplication (mpGEMM), where lower-precision weights are multiplied with higher-precision activations. Despite its benefits, current hardware accelerators such as GPUs and TPUs lack native support for efficient mpGEMM, leading to inefficient dequantization operations in the main sequential loop. To address this limitation, we introduce MixPE, a specialized mixed-precision processing element designed for efficient low-bit quantization in LLM inference. MixPE leverages two key innovations to minimize dequantization overhead and unlock the full potential of low-bit quantization. First, recognizing that scale and zero point are shared within each quantization group, we propose performing dequantization after per-group mpGEMM, significantly reducing dequantization overhead. Second, instead of relying on conventional multipliers, MixPE utilizes efficient shift\&add operations for multiplication, optimizing both computation and energy efficiency. Our experimental results demonstrate that MixPE surpasses the state-of-the-art quantization accelerators by $2.6\times$ speedup and $1.4\times$ energy reduction.

[Arxiv](https://arxiv.org/abs/2411.16158)