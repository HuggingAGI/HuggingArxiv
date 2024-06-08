# OLoRA：大型语言模型的正交低秩适配技术

发布时间：2024年06月03日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的微调技术，特别是介绍了OLoRA这一改进的低秩适应（LoRA）方法。论文通过引入QR分解实现正交矩阵初始化，提高了训练收敛速度，并保持了LoRA的效率优势。这种对LLM微调技术的理论改进和实证研究，属于LLM理论的范畴，因为它关注的是模型训练和优化的理论方法，而不是直接的应用或Agent行为。` `机器学习`

> OLoRA: Orthonormal Low-Rank Adaptation of Large Language Models

# 摘要

> 大型语言模型（LLMs）的兴起为自然语言处理带来了革命性的变革，使其在理解和生成类人文本方面达到了前所未有的水平。然而，微调这些模型的计算成本和时间成本仍然是一大难题。低秩适应（LoRA）作为一种创新方法，通过高效微调技术和减少可训练参数，为解决这些问题提供了希望。本文中，我们介绍了OLoRA，这是对LoRA方法的改进，它通过QR分解实现正交矩阵初始化。OLoRA不仅大幅加快了LLM训练的收敛速度，还保持了LoRA的效率优势，如减少的可训练参数和GPU内存使用。实证研究表明，OLoRA在多个语言建模任务中不仅收敛更快，而且性能优于标准LoRA。这一进步将推动更高效、更易用的LLMs微调技术的发展，为自然语言应用的广泛普及和创新开辟新天地。

> The advent of large language models (LLMs) has revolutionized natural language processing, enabling unprecedented capabilities in understanding and generating human-like text. However, the computational cost and convergence times associated with fine-tuning these models remain significant challenges. Low-Rank Adaptation (LoRA) has emerged as a promising method to mitigate these issues by introducing efficient fine-tuning techniques with a reduced number of trainable parameters. In this paper, we present OLoRA, an enhancement to the LoRA method that leverages orthonormal matrix initialization through QR decomposition. OLoRA significantly accelerates the convergence of LLM training while preserving the efficiency benefits of LoRA, such as the number of trainable parameters and GPU memory footprint. Our empirical evaluations demonstrate that OLoRA not only converges faster but also exhibits improved performance compared to standard LoRA across a variety of language modeling tasks. This advancement opens new avenues for more efficient and accessible fine-tuning of LLMs, potentially enabling broader adoption and innovation in natural language applications.

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/x1.png)

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/tiny-32-loss.png)

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/tiny-64-loss.png)

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/gemma-128.png)

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/opt-64.png)

[Arxiv](https://arxiv.org/abs/2406.01775)