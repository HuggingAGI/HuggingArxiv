# VPTQ：为大型语言模型量身定制的极低比特向量后训练量化技术

发布时间：2024年09月25日

`LLM理论` `人工智能` `云计算`

> VPTQ: Extreme Low-bit Vector Post-Training Quantization for Large Language Models

# 摘要

> 随着模型规模的扩大，大型语言模型（LLMs）的部署和推理面临巨大挑战。近期研究通过将权重量化至极低比特（甚至2比特），有效减少了内存需求和成本。然而，传统量化方法难以应对如此极端的低比特要求。最新研究表明，向量量化（VQ）通过压缩向量至索引，展现出极低比特量化的潜力。本文提出向量后训练量化（VPTQ），利用二阶优化解决LLM向量量化问题，并设计了高效的量化算法。我们还通过通道独立的二阶优化，实现了更精细的权重调整。此外，通过优化问题分解，我们设计了简便的码本初始化算法，并扩展了VPTQ以支持残差和异常值量化，进一步提升了模型精度和压缩效果。实验表明，VPTQ在多个模型上显著降低了量化困惑度，提高了准确率，同时大幅提升了推理速度。

> Scaling model size significantly challenges the deployment and inference of Large Language Models (LLMs). Due to the redundancy in LLM weights, recent research has focused on pushing weight-only quantization to extremely low-bit (even down to 2 bits). It reduces memory requirements, optimizes storage costs, and decreases memory bandwidth needs during inference. However, due to numerical representation limitations, traditional scalar-based weight quantization struggles to achieve such extreme low-bit. Recent research on Vector Quantization (VQ) for LLMs has demonstrated the potential for extremely low-bit model quantization by compressing vectors into indices using lookup tables.
  In this paper, we introduce Vector Post-Training Quantization (VPTQ) for extremely low-bit quantization of LLMs. We use Second-Order Optimization to formulate the LLM VQ problem and guide our quantization algorithm design by solving the optimization. We further refine the weights using Channel-Independent Second-Order Optimization for a granular VQ. In addition, by decomposing the optimization problem, we propose a brief and effective codebook initialization algorithm. We also extend VPTQ to support residual and outlier quantization, which enhances model accuracy and further compresses the model. Our experimental results show that VPTQ reduces model quantization perplexity by $0.01$-$0.34$ on LLaMA-2, $0.38$-$0.68$ on Mistral-7B, $4.41$-$7.34$ on LLaMA-3 over SOTA at 2-bit, with an average accuracy improvement of $0.79$-$1.5\%$ on LLaMA-2, $1\%$ on Mistral-7B, $11$-$22\%$ on LLaMA-3 on QA tasks on average. We only utilize $10.4$-$18.6\%$ of the quantization algorithm execution time, resulting in a $1.6$-$1.8\times$ increase in inference throughput compared to SOTA.

[Arxiv](https://arxiv.org/abs/2409.17066)