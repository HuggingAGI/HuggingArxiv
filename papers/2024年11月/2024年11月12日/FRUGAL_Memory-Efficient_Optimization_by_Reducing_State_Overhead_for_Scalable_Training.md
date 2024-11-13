# FRUGAL：通过减少可扩展训练的状态开销来实现内存高效优化

发布时间：2024年11月12日

`LLM理论` `计算机` `人工智能`

> FRUGAL: Memory-Efficient Optimization by Reducing State Overhead for Scalable Training

# 摘要

> 随着大型语言模型中参数数量的增加，预训练和微调的过程对 GPU 内存的需求越来越大。此内存的很大一部分通常由优化器状态消耗。为了克服这一挑战，最近提出了诸如低秩适应（LoRA（Hu 等人，2021））、低秩梯度投影（GaLore（Zhao 等人，2024））和分块优化（BAdam（Luo 等人，2024））等方法。然而，在所有这些算法中，权重更新的有效秩仍然是低秩的，这可能导致梯度的大量信息丢失。这种损失可能非常重要，特别是在预训练阶段。在本文中，我们引入了 $	exttt{FRUGAL}$（$	extbf{F}$ull-$	extbf{R}$ank $	extbf{U}$pdates with $	extbf{G}$r$	extbf{A}$dient sp$	extbf{L}$itting），这是一种新的内存高效优化框架。$	exttt{FRUGAL}$ 利用梯度分裂，使用高级算法（如 Adam）执行低维更新，而沿其余方向的更新则通过无状态方法（如 SGD 或 signSGD（Bernstein 等人，2018））执行。我们的框架可以与各种低秩更新选择技术集成，包括 GaLore 和 BAdam。当使用 SGDM 进行低维更新和 SGD 进行无状态更新时，我们为我们的框架提供了理论收敛保证。此外，在各种固定内存预算下，我们的方法始终优于并发方法，在预训练和微调任务中实现了最先进的结果，同时平衡了内存效率和性能指标。

> With the increase in the number of parameters in large language models, the process of pre-training and fine-tuning increasingly demands larger volumes of GPU memory. A significant portion of this memory is typically consumed by the optimizer state. To overcome this challenge, recent approaches such as low-rank adaptation (LoRA (Hu et al., 2021)), low-rank gradient projection (GaLore (Zhao et al., 2024)), and blockwise optimization (BAdam (Luo et al., 2024)) have been proposed. However, in all these algorithms, the $\textit{effective rank of the weight updates remains low-rank}$, which can lead to a substantial loss of information from the gradient. This loss can be critically important, especially during the pre-training stage. In this paper, we introduce $\texttt{FRUGAL}$ ($\textbf{F}$ull-$\textbf{R}$ank $\textbf{U}$pdates with $\textbf{G}$r$\textbf{A}$dient sp$\textbf{L}$itting), a new memory-efficient optimization framework. $\texttt{FRUGAL}$ leverages gradient splitting to perform low-dimensional updates using advanced algorithms (such as Adam), while updates along the remaining directions are executed via state-free methods like SGD or signSGD (Bernstein et al., 2018). Our framework can be integrated with various low-rank update selection techniques, including GaLore and BAdam. We provide theoretical convergence guarantees for our framework when using SGDM for low-dimensional updates and SGD for state-free updates. Additionally, our method consistently outperforms concurrent approaches across various fixed memory budgets, achieving state-of-the-art results in pre-training and fine-tuning tasks while balancing memory efficiency and performance metrics.

[Arxiv](https://arxiv.org/abs/2411.07837)