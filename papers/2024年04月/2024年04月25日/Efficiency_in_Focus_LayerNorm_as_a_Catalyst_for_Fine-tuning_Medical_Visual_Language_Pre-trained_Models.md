# 聚焦效率：LayerNorm 助力医学视觉语言预训练模型的精准调优。

发布时间：2024年04月25日

`LLM应用` `人工智能`

> Efficiency in Focus: LayerNorm as a Catalyst for Fine-tuning Medical Visual Language Pre-trained Models

# 摘要

> 在医学视觉语言模型（Med-VLMs）的研究领域，探索一种通用且高效的微调机制显得尤为关键，特别是对于资源匮乏的跨学科研究者来说，这一需求尚未得到充分满足。面对医学领域的特殊挑战，如数据的有限性和领域特定的高标准要求，对Med-VLMs进行参数高效微调（PEFT）的评估与适配显得尤为重要。目前，大多数PEFT方法尚未全面探究，而是更多关注于模型结构或输入的局部改进。然而，对模型内部组件进行微调往往能够带来更佳的泛化和一致性，这一点在Med-VLMs的最终性能影响上却鲜有关注。本文旨在探索一种替代传统PEFT方法的新途径，特别是研究微调LayerNorm层、FFN和注意力层对Med-VLMs的影响。我们对不同规模的Med-VLMs进行了深入研究，包括小规模和大规模模型，并在多种微调框架下，评估了它们在医学视觉问答和医学影像报告生成等任务上的表现。研究发现，内部参数微调的方法在微调Med-VLMs以适应下游任务时具有独特的效果，尤其是仅微调LayerNorm层的方法，不仅在效率上超越了传统PEFT方法，而且在一系列医学相关下游任务中保持了模型的准确性和泛化能力。实验结果进一步证明，LayerNorm微调在大型Med-VLMs中的应用展现出了卓越的适应性和可扩展性。

> In the realm of Medical Visual Language Models (Med-VLMs), the quest for universal efficient fine-tuning mechanisms remains paramount, especially given researchers in interdisciplinary fields are often extremely short of training resources, yet largely unexplored. Given the unique challenges in the medical domain, such as limited data scope and significant domain-specific requirements, evaluating and adapting Parameter-Efficient Fine-Tuning (PEFT) methods specifically for Med-VLMs is essential. Most of the current PEFT methods on Med-VLMs have yet to be comprehensively investigated but mainly focus on adding some components to the model's structure or input. However, fine-tuning intrinsic model components often yields better generality and consistency, and its impact on the ultimate performance of Med-VLMs has been widely overlooked and remains understudied. In this paper, we endeavour to explore an alternative to traditional PEFT methods, especially the impact of fine-tuning LayerNorm layers, FFNs and Attention layers on the Med-VLMs. Our comprehensive studies span both small-scale and large-scale Med-VLMs, evaluating their performance under various fine-tuning paradigms across tasks such as Medical Visual Question Answering and Medical Imaging Report Generation. The findings reveal unique insights into the effects of intrinsic parameter fine-tuning methods on fine-tuning Med-VLMs to downstream tasks and expose fine-tuning solely the LayerNorm layers not only surpasses the efficiency of traditional PEFT methods but also retains the model's accuracy and generalization capabilities across a spectrum of medical downstream tasks. The experiments show LayerNorm fine-tuning's superior adaptability and scalability, particularly in the context of large-scale Med-VLMs.

[Arxiv](https://arxiv.org/abs/2404.16385)