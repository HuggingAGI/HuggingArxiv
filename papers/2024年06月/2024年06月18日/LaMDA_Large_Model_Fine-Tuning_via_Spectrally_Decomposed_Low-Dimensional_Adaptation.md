# LaMDA：利用频谱分解实现低维适应性的大型模型微调

发布时间：2024年06月18日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的微调方法，特别是通过提出一种名为LaMDA的新方法来减少计算成本和GPU内存需求。这种方法涉及光谱分解的低维适应，以及在微调过程中冻结部分矩阵并引入低维可训练矩阵。这些内容更多地涉及LLM的理论和内部机制的改进，而不是直接的应用或Agent的行为，也不是RAG（检索增强生成）的相关技术。因此，将其归类为LLM理论是合适的。` `机器学习`

> LaMDA: Large Model Fine-Tuning via Spectrally Decomposed Low-Dimensional Adaptation

# 摘要

> 低秩适应（LoRA）因其大幅减少可训练参数而成为微调大型语言模型（LLMs）的首选方法。但随着模型嵌入维度的提升，LoRA的计算成本和GPU内存需求也随之攀升。本文提出了一种名为LaMDA的新方法，通过光谱分解的低维适应，显著降低了参数和内存的消耗。LaMDA在微调过程中冻结部分矩阵，引入低维可训练矩阵，有效控制了资源消耗。此外，LaMDA++版本通过智能秩分配进一步优化了性能。在多项任务测试中，LaMDA系列方法不仅性能卓越，而且资源消耗大幅减少。相关代码即将公开。

> Low-rank adaptation (LoRA) has become the default approach to fine-tune large language models (LLMs) due to its significant reduction in trainable parameters. However, trainable parameter demand for LoRA increases with increasing model embedding dimensions, leading to high compute costs. Additionally, its backward updates require storing high-dimensional intermediate activations and optimizer states, demanding high peak GPU memory. In this paper, we introduce large model fine-tuning via spectrally decomposed low-dimensional adaptation (LaMDA), a novel approach to fine-tuning large language models, which leverages low-dimensional adaptation to achieve significant reductions in trainable parameters and peak GPU memory footprint. LaMDA freezes a first projection matrix (PMA) in the adaptation path while introducing a low-dimensional trainable square matrix, resulting in substantial reductions in trainable parameters and peak GPU memory usage. LaMDA gradually freezes a second projection matrix (PMB) during the early fine-tuning stages, reducing the compute cost associated with weight updates to enhance parameter efficiency further. We also present an enhancement, LaMDA++, incorporating a ``lite-weight" adaptive rank allocation for the LoRA path via normalized spectrum analysis of pre-trained model weights. We evaluate LaMDA/LaMDA++ across various tasks, including natural language understanding with the GLUE benchmark, text summarization, natural language generation, and complex reasoning on different LLMs. Results show that LaMDA matches or surpasses the performance of existing alternatives while requiring up to 17.7x fewer parameter updates and up to 1.32x lower peak GPU memory usage during fine-tuning. Code will be publicly available.

![LaMDA：利用频谱分解实现低维适应性的大型模型微调](../../../paper_images/2406.12832/Method.png)

![LaMDA：利用频谱分解实现低维适应性的大型模型微调](../../../paper_images/2406.12832/x1.png)

![LaMDA：利用频谱分解实现低维适应性的大型模型微调](../../../paper_images/2406.12832/x2.png)

![LaMDA：利用频谱分解实现低维适应性的大型模型微调](../../../paper_images/2406.12832/x3.png)

![LaMDA：利用频谱分解实现低维适应性的大型模型微调](../../../paper_images/2406.12832/x4.png)

[Arxiv](https://arxiv.org/abs/2406.12832)