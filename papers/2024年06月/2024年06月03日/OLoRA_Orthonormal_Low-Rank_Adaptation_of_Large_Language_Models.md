# OLoRA：大型语言模型的正交低秩适配技术

发布时间：2024年06月03日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的微调技术，特别是介绍了OLoRA这一改进方法，它通过QR分解实现正交矩阵初始化，以加速训练收敛并减少可训练参数和GPU内存使用。这种对LLM微调技术的深入研究和改进属于理论层面的探讨，因为它涉及模型训练的优化方法和理论基础，而不是直接的应用或Agent行为。因此，将其归类为LLM理论是合适的。` `机器学习`

> OLoRA: Orthonormal Low-Rank Adaptation of Large Language Models

# 摘要

> 大型语言模型（LLMs）的兴起为自然语言处理带来了革命性的变革，使其在理解和生成类人文本方面达到了前所未有的水平。然而，微调这些模型的计算成本和时间成本仍然是一大挑战。低秩适应（LoRA）作为一种有前景的解决方案应运而生，它通过减少可训练参数的数量，采用高效的微调技术来缓解这些问题。本文中，我们介绍了OLoRA，这是对LoRA方法的改进，它通过QR分解实现正交矩阵初始化，从而加速LLM训练的收敛，同时保持了LoRA的效率优势，如减少的可训练参数和GPU内存使用。实证研究表明，OLoRA不仅加速了收敛，而且在多种语言建模任务中表现优于标准LoRA。这一进步将推动LLMs微调技术的发展，使其更加高效和普及，为自然语言应用的创新和广泛应用开辟新道路。

> The advent of large language models (LLMs) has revolutionized natural language processing, enabling unprecedented capabilities in understanding and generating human-like text. However, the computational cost and convergence times associated with fine-tuning these models remain significant challenges. Low-Rank Adaptation (LoRA) has emerged as a promising method to mitigate these issues by introducing efficient fine-tuning techniques with a reduced number of trainable parameters. In this paper, we present OLoRA, an enhancement to the LoRA method that leverages orthonormal matrix initialization through QR decomposition. OLoRA significantly accelerates the convergence of LLM training while preserving the efficiency benefits of LoRA, such as the number of trainable parameters and GPU memory footprint. Our empirical evaluations demonstrate that OLoRA not only converges faster but also exhibits improved performance compared to standard LoRA across a variety of language modeling tasks. This advancement opens new avenues for more efficient and accessible fine-tuning of LLMs, potentially enabling broader adoption and innovation in natural language applications.

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/x1.png)

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/tiny-32-loss.png)

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/tiny-64-loss.png)

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/gemma-128.png)

![OLoRA：大型语言模型的正交低秩适配技术](../../../paper_images/2406.01775/opt-64.png)

[Arxiv](https://arxiv.org/abs/2406.01775)