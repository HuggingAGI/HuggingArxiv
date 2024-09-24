# Domino：利用通用张量切片与重叠技术，彻底消除 LLM 训练中的通信瓶颈。

发布时间：2024年09月23日

`LLM理论` `人工智能` `高性能计算`

> Domino: Eliminating Communication in LLM Training via Generic Tensor Slicing and Overlapping

# 摘要

> 随着生成式 AI 的兴起，大型语言模型（LLM）的训练通常需要数百甚至数千个 GPU 来并行加速。然而，这种规模的训练带来了显著的通信开销。为此，我们推出了 Domino，一种将通信巧妙隐藏在计算背后的通用方案。Domino 通过将训练任务分解为更小的独立模块，并实现细粒度的通信与计算重叠，显著提升了训练效率。实验结果显示，与 Megatron-LM 相比，Domino 在 Nvidia DGX-H100 GPU 上可将 LLM 训练速度提升至多 1.3 倍。

> Given the popularity of generative AI, Large Language Models (LLMs) often consume hundreds or thousands of GPUs for parallelizing and accelerating the training process. Communication overhead becomes more pronounced when training LLMs at scale. To eliminate communication overhead in distributed LLM training, we propose Domino, which provides a generic scheme to hide communication behind computation. By breaking data dependency of a single batch training into smaller independent pieces, Domino pipelines these independent pieces training and provides generic strategy of fine-grained communication and computation overlapping. Extensive results show that, comparing with Megatron-LM, Domino achieves up to 1.3x speedup for LLM training on Nvidia DGX-H100 GPUs.

[Arxiv](https://arxiv.org/abs/2409.15241)