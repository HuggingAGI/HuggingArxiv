# SeedLM：将 LLM 权重压缩为伪随机生成器的种子

发布时间：2024年10月14日

`LLM理论` `半导体` `人工智能`

> SeedLM: Compressing LLM Weights into Seeds of Pseudo-Random Generators

# 摘要

> 大型语言模型（LLM）虽已革新自然语言处理，但其高昂的运行成本却限制了广泛应用。本文提出 SeedLM，一种创新的后训练压缩技术，利用伪随机生成器的种子编码并压缩模型权重。具体而言，每个权重块通过线性反馈移位寄存器（LFSR）生成随机矩阵，再与压缩系数结合，高效重建权重。SeedLM 不仅减少内存访问，还利用空闲计算周期，以计算换取更少内存访问，显著提速内存密集型任务。与依赖校准数据的现有技术不同，SeedLM 无需数据，且在多任务中表现优异。实验显示，SeedLM 在 Llama 3 70B 上，4 位和 3 位精度下，零样本准确性优于现有技术，性能媲美 FP16 基线。FPGA 测试进一步表明，模型增至 70B 时，4 位 SeedLM 速度接近 FP16 基线的 4 倍。

> Large Language Models (LLMs) have transformed natural language processing, but face significant challenges in widespread deployment due to their high runtime cost. In this paper, we introduce SeedLM, a novel post-training compression method that uses seeds of pseudo-random generators to encode and compress model weights. Specifically, for each block of weights, we find a seed that is fed into a Linear Feedback Shift Register (LFSR) during inference to efficiently generate a random matrix. This matrix is then linearly combined with compressed coefficients to reconstruct the weight block. SeedLM reduces memory access and leverages idle compute cycles during inference, effectively speeding up memory-bound tasks by trading compute for fewer memory accesses. Unlike state-of-the-art compression methods that rely on calibration data, our approach is data-free and generalizes well across diverse tasks. Our experiments with Llama 3 70B, which is particularly challenging to compress, show that SeedLM achieves significantly better zero-shot accuracy retention at 4- and 3-bit than state-of-the-art techniques, while maintaining performance comparable to FP16 baselines. Additionally, FPGA-based tests demonstrate that 4-bit SeedLM, as model size increases to 70B, approaches a 4x speed-up over an FP16 Llama 2/3 baseline.

[Arxiv](https://arxiv.org/abs/2410.10714)