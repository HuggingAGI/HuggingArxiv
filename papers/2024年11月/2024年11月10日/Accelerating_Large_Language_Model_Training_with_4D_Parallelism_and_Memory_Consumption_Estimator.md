# 使用 4D 并行和内存消耗估计器加速大型语言模型训练

发布时间：2024年11月10日

`LLM应用` `计算机` `人工智能`

> Accelerating Large Language Model Training with 4D Parallelism and Memory Consumption Estimator

# 摘要

> 在大型语言模型（LLM）训练中，包括张量并行（TP）、流水线并行（PP）、数据并行（DP）以及序列并行（SP）和上下文并行（CP）在内的几种并行化策略被用于在设备之间分布模型参数、激活和优化器状态。确定每个环境的最佳并行化配置，同时避免 GPU 内存溢出仍然是一项具有挑战性的任务。在本研究中，我们为 Llama 架构中的 4D 并行训练（DP、TP、PP、CP）提供了精确的公式来估计参数、梯度、优化器状态和激活所消耗的内存。我们在 A100 和 H100 GPU 上进行了 454 次实验，将临时缓冲区和内存碎片等经常被忽略的因素纳入我们的分析。结果表明，当估计的内存使用量低于可用 GPU 内存的 80％时，训练永远不会遇到内存不足的错误。这个简单而有效的公式使我们能够提前识别可能导致内存溢出的并行化配置，大大减少了配置搜索空间。此外，通过对 4D 并行中的最佳配置进行全面探索，我们对 454 个实验结果的分析为最佳 4D 并行配置提供了经验性的见解。

> In large language model (LLM) training, several parallelization strategies, including Tensor Parallelism (TP), Pipeline Parallelism (PP), Data Parallelism (DP), as well as Sequence Parallelism (SP) and Context Parallelism (CP), are employed to distribute model parameters, activations, and optimizer states across devices. Identifying the optimal parallelization configuration for each environment while avoiding GPU memory overflow remains a challenging task. In this study, we provide precise formulas to estimate the memory consumed by parameters, gradients, optimizer states, and activations for 4D parallel training (DP, TP, PP, CP) in the Llama architecture. We conducted 454 experiments on A100 and H100 GPUs, incorporating often neglected factors such as temporary buffers and memory fragmentation into our analysis. Results indicate that when the estimated memory usage is below 80\% of the available GPU memory, the training never encounters out-of-memory errors. This simple yet effective formula allows us to identify parallelization configurations that could lead to memory overflow in advance, significantly reducing the configuration search space. Additionally, through a comprehensive exploration of optimal configurations in 4D parallelism, our analysis of the 454 experimental results provides empirical insights into optimal 4D parallelism configurations.

[Arxiv](https://arxiv.org/abs/2411.06465)