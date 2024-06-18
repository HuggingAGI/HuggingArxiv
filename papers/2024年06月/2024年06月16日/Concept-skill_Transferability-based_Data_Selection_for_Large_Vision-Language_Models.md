# 针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。

发布时间：2024年06月16日

`LLM应用

这篇论文主要讨论了一种名为COINCIDE的技术，该技术用于高效微调大型视觉-语言模型（LVLMs），通过一个小模型来精选数据，以提高数据选择效率和模型的泛化能力。这种方法特别关注数据的多样性和可转移性，并通过实验证明了其在减少数据使用量和运行时间的同时，保持或提高模型性能的有效性。因此，这项工作属于大型语言模型（LLM）的应用范畴，具体是在优化和提高视觉-语言模型性能的应用层面。` `计算机视觉`

> Concept-skill Transferability-based Data Selection for Large Vision-Language Models

# 摘要

> 为了使大型视觉-语言模型（LVLMs）在多种视觉-语言任务中表现出色，需要在特定任务的大量数据上进行监督微调。但这种方法成本高昂。为此，我们开发了COINCIDE技术，它利用一个小模型来精选数据，以高效微调目标LVLM，特别注重数据的多样性和可转移性。我们通过小模型的内部激活对训练数据进行聚类，识别出LVLM所需的关键视觉-语言概念和技能组合，并根据这些组合的密度和转移能力进行数据采样。这种方法确保了数据组合的多样性，对LVLM的泛化能力至关重要。实验结果显示，COINCIDE在LLaVA-1.5和Vision-Flan两个数据集上，相比8个强基线，不仅性能更优，而且数据选择效率更高。例如，仅用LLaVA-1.5数据集的20%，COINCIDE就能达到与全数据集训练相当的性能，同时运行时间减少了70%。在Vision-Flan数据集上，我们的方法仅用16.7%的训练数据就取得了显著成果。

> Instruction tuning, or supervised finetuning on extensive task-specific data, is necessary for Large Vision-Language Models (LVLMs) to generalize well across a broad range of vision-language (VL) tasks. However, training on large VL datasets can become prohibitively expensive. In this work, we introduce COINCIDE, an effective and scalable data selection technique that uses a small model as a reference model to select visual instruction tuning data for efficient finetuning of a target LVLM, focusing on diversity and transferability. Specifically, we cluster the training data using internal activations from a small model, which identifies VL concept-skill compositions needed by a target LVLM. We then sample data from these diverse clusters by considering their density and transferability, or the ability to transfer well to other concept-skill compositions. This approach ensures the diversity of these compositions, which is vital for LVLM generalization. Extensive experiments demonstrate that COINCIDE achieves superior performance and data selection efficiency against 8 strong baselines on two distinct datasets: LLaVA-1.5 and Vision-Flan. Using only 20% of the LLaVA-1.5 dataset, COINCIDE achieves performance comparable to the LVLM finetuned on the whole dataset, with 70% reduction of the wall-clock running time. On the Vision-Flan dataset, our method achieves superior results with only 16.7% of the training data.

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x1.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x2.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x3.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x4.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x5.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x6.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x7.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x8.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x9.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x10.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x11.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x12.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x13.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x14.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x15.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x16.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x17.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x18.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x19.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x20.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x21.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x22.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x23.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x24.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x25.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x26.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x27.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x28.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x29.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x30.png)

![针对大型视觉-语言模型，采用基于概念技能可迁移性的数据筛选策略。](../../../paper_images/2406.10995/x31.png)

[Arxiv](https://arxiv.org/abs/2406.10995)