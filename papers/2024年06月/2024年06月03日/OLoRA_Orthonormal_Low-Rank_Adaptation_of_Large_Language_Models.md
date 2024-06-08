# OLoRA：大型语言模型的正交低秩适配技术

发布时间：2024年06月03日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的微调技术，特别是介绍了低秩适应（LoRA）的优化版本OLoRA，并通过理论分析和实证研究展示了其在提升训练收敛速度和性能方面的优势。这属于对LLMs理论层面的深入研究，特别是关于模型微调和优化技术，因此归类为LLM理论。` `机器学习`

> OLoRA: Orthonormal Low-Rank Adaptation of Large Language Models

# 摘要

> 大型语言模型（LLMs）的兴起为自然语言处理带来了革命性的变革，极大地提升了理解和生成类人文本的能力。尽管如此，微调这些模型的计算成本和时间仍是亟待解决的难题。低秩适应（LoRA）作为一种创新方法，通过减少可训练参数并采用高效微调技术，有效缓解了这些问题。本文介绍的OLoRA是对LoRA的进一步优化，它通过QR分解实现正交矩阵初始化，显著提升了LLM训练的收敛速度，同时保持了LoRA的效率优势，如减少的参数数量和GPU内存使用。实证结果显示，OLoRA在多个语言建模任务中不仅收敛更快，性能也超越了标准LoRA。这一突破为LLMs的微调提供了更高效、更便捷的途径，有望推动自然语言应用的广泛普及和创新。

> The advent of large language models (LLMs) has revolutionized natural language processing, enabling unprecedented capabilities in understanding and generating human-like text. However, the computational cost and convergence times associated with fine-tuning these models remain significant challenges. Low-Rank Adaptation (LoRA) has emerged as a promising method to mitigate these issues by introducing efficient fine-tuning techniques with a reduced number of trainable parameters. In this paper, we present OLoRA, an enhancement to the LoRA method that leverages orthonormal matrix initialization through QR decomposition. OLoRA significantly accelerates the convergence of LLM training while preserving the efficiency benefits of LoRA, such as the number of trainable parameters and GPU memory footprint. Our empirical evaluations demonstrate that OLoRA not only converges faster but also exhibits improved performance compared to standard LoRA across a variety of language modeling tasks. This advancement opens new avenues for more efficient and accessible fine-tuning of LLMs, potentially enabling broader adoption and innovation in natural language applications.

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/x1.png)

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/tiny-32-loss.png)

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/tiny-64-loss.png)

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/gemma-128.png)

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/opt-64.png)

[Arxiv](https://arxiv.org/abs/2406.01775)