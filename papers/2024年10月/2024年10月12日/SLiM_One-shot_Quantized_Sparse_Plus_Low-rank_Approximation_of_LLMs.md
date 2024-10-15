# SLiM：一次量化稀疏加低秩近似 LLM

发布时间：2024年10月12日

`LLM理论` `计算机科学`

> SLiM: One-shot Quantized Sparse Plus Low-rank Approximation of LLMs

# 摘要

> 大型语言模型（LLM）在自然语言处理领域取得了革命性进展，但其庞大的参数规模导致内存消耗大、推理速度慢。传统压缩技术如量化和剪枝虽能缓解这些问题，但需重新训练以保持精度，成本高昂。本文提出 SLiM，一种无需重新训练的 LLM 压缩新方法，结合对称量化与低秩近似，有效减少量化误差并兼容加速硬件。此外，我们设计了高效的微调方案，大幅降低训练开销。实验表明，SLiM 在稀疏模式下精度提升高达 5.4%，微调后更可达 5.8%，性能卓越。这项研究为在内存受限环境中高效部署大型模型提供了新思路，确保精度不受损。

> Large Language Models (LLMs) have revolutionized natural language understanding and generation tasks but suffer from high memory consumption and slow inference times due to their large parameter sizes. Traditional model compression techniques, such as quantization and pruning, mitigate these issues but often require retraining to maintain accuracy, which is computationally expensive. This paper introduces SLiM, a novel approach for compressing LLMs using a one-shot Quantized Sparse Plus Low-rank Approximation. SLiM eliminates the need for costly retraining by combining a symmetric quantization method (SLiM-Quant) with a saliency-based low-rank approximation. Our method reduces quantization error while leveraging sparse representations compatible with accelerated hardware architectures. Additionally, we propose a parameter-efficient fine-tuning recipe that significantly reduces overhead compared to conventional quantization-aware training. SLiM achieves up to a 5.4% improvement in model accuracy for sparsity patterns like 2:4, and the fine-tuning step further enhances accuracy by up to 5.8%, demonstrating state-of-the-art performance. This work provides a pathway for efficiently deploying large models in memory-constrained environments without compromising accuracy.

[Arxiv](https://arxiv.org/abs/2410.09615)