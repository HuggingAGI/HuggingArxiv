# MInference 1.0 通过动态稀疏注意力机制，加速了长上下文大型语言模型的预填充过程。

发布时间：2024年07月02日

`LLM应用` `人工智能` `高性能计算`

> MInference 1.0: Accelerating Pre-filling for Long-Context LLMs via Dynamic Sparse Attention

# 摘要

> 大型语言模型（LLM）的推理计算挑战，尤其是在提示长度不断增加的情况下，仍是广泛部署的重大障碍。由于注意力计算的二次复杂性，处理1M令牌的提示在单个A100 GPU上需时30分钟。为解决现有方法在长上下文LLM中难以保持准确性与效率的问题，我们推出了MInference，一种专为加速长序列预填充设计的稀疏计算方法。我们识别了三种独特的注意力矩阵模式——A形、垂直斜线和块稀疏，这些模式可用于GPU上的高效稀疏计算。我们离线确定每个注意力头的最佳模式，并在推理时动态构建稀疏索引。通过这些模式和索引，我们利用优化的GPU内核进行高效稀疏注意力计算，显著减少长上下文LLM预填充阶段的延迟。我们的技术可直接应用于现有LLM，无需修改预训练设置或额外微调。通过在多个下游任务和模型中进行评估，我们证明了MInference能有效减少A100上的预填充推理延迟高达10倍，同时保持准确性。代码已公开，可访问https://aka.ms/MInference获取。

> The computational challenges of Large Language Model (LLM) inference remain a significant barrier to their widespread deployment, especially as prompt lengths continue to increase. Due to the quadratic complexity of the attention computation, it takes 30 minutes for an 8B LLM to process a prompt of 1M tokens (i.e., the pre-filling stage) on a single A100 GPU. Existing methods for speeding up prefilling often fail to maintain acceptable accuracy or efficiency when applied to long-context LLMs. To address this gap, we introduce MInference (Milliontokens Inference), a sparse calculation method designed to accelerate pre-filling of long-sequence processing. Specifically, we identify three unique patterns in long-context attention matrices-the A-shape, Vertical-Slash, and Block-Sparsethat can be leveraged for efficient sparse computation on GPUs. We determine the optimal pattern for each attention head offline and dynamically build sparse indices based on the assigned pattern during inference. With the pattern and sparse indices, we perform efficient sparse attention calculations via our optimized GPU kernels to significantly reduce the latency in the pre-filling stage of long-context LLMs. Our proposed technique can be directly applied to existing LLMs without any modifications to the pre-training setup or additional fine-tuning. By evaluating on a wide range of downstream tasks, including InfiniteBench, RULER, PG-19, and Needle In A Haystack, and models including LLaMA-3-1M, GLM4-1M, Yi-200K, Phi-3-128K, and Qwen2-128K, we demonstrate that MInference effectively reduces inference latency by up to 10x for pre-filling on an A100, while maintaining accuracy. Our code is available at https://aka.ms/MInference.

[Arxiv](https://arxiv.org/abs/2407.02490)