# Mamba 状态空间模型展现出作为下游学习者的强大潜力

发布时间：2024年05月31日

`LLM理论

理由：这篇论文主要探讨了Mamba状态空间模型的下游学习能力，包括混合精度和参数高效微调，以及其在情境学习（ICL）方面的性能。这些内容涉及到模型的理论改进和性能评估，特别是在模型架构和计算效率方面的深入研究，因此属于大型语言模型（LLM）的理论研究范畴。` `机器学习`

> Mamba State-Space Models Can Be Strong Downstream Learners

# 摘要

> Mamba状态空间模型近期在多个任务上超越了顶尖的Transformer大型语言模型，并广受欢迎。但其下游学习能力，如混合精度和参数高效微调，尚未得到充分探索或评估，尤其是在情境学习方面。尽管有研究指出Mamba在非标准测试中与顶尖Transformer表现相当，但在标准测试中，Mamba的ICL性能提升仅达到Transformer的38%。在Mamba架构中引入混合精度和参数高效微调颇具挑战，因其循环动力学和定制CUDA内核。但我们通过动力系统理论证实，Mamba对输入微小变化具有强健性。实证研究表明，Mamba因混合精度在推理和微调中的性能变化与Transformer一致。此外，通过针对Mamba定制CUDA内核的关键内存缓冲区进行低秩适应，我们实现了参数的规范化，既保持了速度优势，又提高了参数效率。结合这两种技术，我们实现了每秒处理令牌数提升2.15倍，每个令牌内存消耗降低65.5%，同时ICL性能提升达到同等微调Transformer的81.5%。

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