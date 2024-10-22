# MagicPIG：利用 LSH 采样技术，实现 LLM 生成的高效能

发布时间：2024年10月21日

`LLM理论` `人工智能` `高性能计算`

> MagicPIG: LSH Sampling for Efficient LLM Generation

# 摘要

> 长上下文窗口的大型语言模型 (LLM) 备受瞩目，但存储以避免重新计算的 KV 缓存却成了瓶颈。本文首先指出，TopK 注意力在某些任务中质量下降，因为注意力并不总是稀疏的。我们提出 MagicPIG，一个基于局部敏感哈希 (LSH) 的异构系统，通过采样而非选择最高分数的键和值，显著减少计算量并保持高准确性。MagicPIG 在 CPU 上运行注意力计算，支持更长上下文和更大批量，且近似精度高。在各种 GPU 硬件上，MagicPIG 可将解码吞吐量提升 $1.9\sim3.9\times$，并在单个 RTX 4090 上为 Llama-3.1-8B-Instruct 模型在 96k 个 token 的上下文中实现 110ms 的解码延迟。代码已开源，详见 \url{https://github.com/Infini-AI-Lab/MagicPIG}。

> Large language models (LLMs) with long context windows have gained significant attention. However, the KV cache, stored to avoid re-computation, becomes a bottleneck. Various dynamic sparse or TopK-based attention approximation methods have been proposed to leverage the common insight that attention is sparse. In this paper, we first show that TopK attention itself suffers from quality degradation in certain downstream tasks because attention is not always as sparse as expected. Rather than selecting the keys and values with the highest attention scores, sampling with theoretical guarantees can provide a better estimation for attention output. To make the sampling-based approximation practical in LLM generation, we propose MagicPIG, a heterogeneous system based on Locality Sensitive Hashing (LSH). MagicPIG significantly reduces the workload of attention computation while preserving high accuracy for diverse tasks. MagicPIG stores the LSH hash tables and runs the attention computation on the CPU, which allows it to serve longer contexts and larger batch sizes with high approximation accuracy. MagicPIG can improve decoding throughput by $1.9\sim3.9\times$ across various GPU hardware and achieve 110ms decoding latency on a single RTX 4090 for Llama-3.1-8B-Instruct model with a context of 96k tokens. The code is available at \url{https://github.com/Infini-AI-Lab/MagicPIG}.

[Arxiv](https://arxiv.org/abs/2410.16179)