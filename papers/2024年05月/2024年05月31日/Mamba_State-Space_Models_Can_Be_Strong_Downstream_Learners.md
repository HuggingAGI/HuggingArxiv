# Mamba 状态空间模型展现出作为下游学习者的强大潜力

发布时间：2024年05月31日

`LLM理论

理由：这篇论文主要探讨了Mamba状态空间模型在情境学习（ICL）方面的性能，以及如何通过混合精度微调（MPFT）和参数高效微调（PEFT）来提升其性能。这些内容涉及模型的理论分析和改进，特别是在微调和性能优化方面的深入研究，因此属于LLM理论分类。` `人工智能`

> Mamba State-Space Models Can Be Strong Downstream Learners

# 摘要

> Mamba状态空间模型近期在多个任务上超越了顶尖的Transformer大型语言模型，并被广泛采纳。尽管如此，Mamba在下游学习能力方面，如混合精度微调和参数高效微调，仍未得到充分研究，尤其是在情境学习（ICL）方面。最近的研究指出，Mamba在非标准基准上的ICL表现与顶尖Transformer模型相当。然而，我们的研究表明，在标准基准上，预训练的Mamba模型在ICL性能上仅能达到同等规模Transformer模型的38%。在Mamba架构中实现MPFT和PEFT颇具挑战，这源于其循环动力学和定制CUDA内核的复杂性。但我们通过动力系统理论证实，Mamba的循环动力学对输入微小变化具有稳健性。实证分析显示，Mamba因混合精度而导致的推理和微调性能变化与Transformer模型一致。此外，我们发现，通过针对Mamba定制CUDA内核中的关键内存缓冲区进行低秩适应，可以有效规范SSM参数，既保持了加速，又实现了参数效率。结合MPFT和PEFT，我们实现了每秒处理令牌数量提升2.15倍，每个令牌的内存消耗降低65.5%，同时ICL性能提升（相对于零-shot）达到了同等微调Transformer模型的81.5%。

> Mamba state-space models (SSMs) have recently outperformed state-of-the-art (SOTA) Transformer large language models (LLMs) in various tasks and been widely adapted. However, Mamba's downstream learning capabilities remain either unexplored$\unicode{x2013}$e.g., mixed-precision (MPFT) and parameter-efficient fine-tuning (PEFT)--or under-evaluated$\unicode{x2013}$e.g., in-context learning (ICL). For the latter, recent works reported Mamba's ICL rivals SOTA Transformer LLMs using non-standard benchmarks. In contrast, we show that on standard benchmarks, pretrained Mamba models achieve only 38% of the ICL performance improvements (over zero-shot) of comparable Transformers.
  Enabling MPFT and PEFT in Mamba architectures is challenging due to recurrent dynamics and highly customized CUDA kernels, respectively. However, we prove that Mamba's recurrent dynamics are robust to small input changes using dynamical systems theory. Empirically, we show that performance changes in Mamba's inference and fine-tuning due to mixed-precision align with Transformer LLMs. Furthermore, we show that targeting key memory buffers in Mamba's customized CUDA kernels for low-rank adaptation regularizes SSM parameters, thus achieving parameter efficiency while retaining speedups. We show that combining MPFT and PEFT enables up to 2.15 times more tokens-per-second and 65.5% reduced per-token-memory compared to full Mamba fine-tuning, while achieving up to 81.5% of the ICL performance improvements (over zero-shot) of comparably fine-tuned Transformers.

![Mamba 状态空间模型展现出作为下游学习者的强大潜力](../../../paper_images/2406.00209/x1.png)

![Mamba 状态空间模型展现出作为下游学习者的强大潜力](../../../paper_images/2406.00209/x2.png)

![Mamba 状态空间模型展现出作为下游学习者的强大潜力](../../../paper_images/2406.00209/x3.png)

![Mamba 状态空间模型展现出作为下游学习者的强大潜力](../../../paper_images/2406.00209/x4.png)

![Mamba 状态空间模型展现出作为下游学习者的强大潜力](../../../paper_images/2406.00209/x5.png)

![Mamba 状态空间模型展现出作为下游学习者的强大潜力](../../../paper_images/2406.00209/x6.png)

![Mamba 状态空间模型展现出作为下游学习者的强大潜力](../../../paper_images/2406.00209/x7.png)

![Mamba 状态空间模型展现出作为下游学习者的强大潜力](../../../paper_images/2406.00209/x8.png)

![Mamba 状态空间模型展现出作为下游学习者的强大潜力](../../../paper_images/2406.00209/x9.png)

[Arxiv](https://arxiv.org/abs/2406.00209)