# 聚焦效率：LayerNorm 助力医疗视觉语言预训练模型的精细调整。

发布时间：2024年04月25日

`LLM应用` `人工智能`

> Efficiency in Focus: LayerNorm as a Catalyst for Fine-tuning Medical Visual Language Pre-trained Models

# 摘要

> 在医学视觉语言模型（Med-VLMs）的研究中，探索一种高效通用的微调机制显得尤为关键，特别是在跨学科研究者面临训练资源匮乏的挑战时。面对医学领域的特殊难题，如数据的有限性和对领域特定要求的高依赖性，对参数高效微调（PEFT）方法进行评估和定制化调整对于Med-VLMs来说至关重要。目前，大多数PEFT方法尚未在Med-VLMs上进行全面的研究，而是更多地关注于模型结构或输入的简单增加。但是，对模型内部组件进行微调往往能够带来更优的泛化和一致性，其对Med-VLMs性能的潜在影响却被普遍忽视。本文旨在探索一种替代性的传统PEFT方法，特别关注微调LayerNorm层、FFN和注意力层对Med-VLMs的影响。我们进行了广泛的研究，覆盖了从小规模到大规模的Med-VLMs，并在多种微调策略下评估了它们在医学视觉问答和医学影像报告生成等任务上的表现。研究发现，内在参数微调方法在微调Med-VLMs以适应下游任务时的效果显著，尤其是仅对LayerNorm层进行微调，不仅在效率上超越了传统PEFT方法，而且在一系列医学相关任务中保持了模型的准确性和泛化能力。实验结果进一步证明了LayerNorm微调在大规模Med-VLMs中的卓越适应性和可扩展性。

> In the realm of Medical Visual Language Models (Med-VLMs), the quest for universal efficient fine-tuning mechanisms remains paramount, especially given researchers in interdisciplinary fields are often extremely short of training resources, yet largely unexplored. Given the unique challenges in the medical domain, such as limited data scope and significant domain-specific requirements, evaluating and adapting Parameter-Efficient Fine-Tuning (PEFT) methods specifically for Med-VLMs is essential. Most of the current PEFT methods on Med-VLMs have yet to be comprehensively investigated but mainly focus on adding some components to the model's structure or input. However, fine-tuning intrinsic model components often yields better generality and consistency, and its impact on the ultimate performance of Med-VLMs has been widely overlooked and remains understudied. In this paper, we endeavour to explore an alternative to traditional PEFT methods, especially the impact of fine-tuning LayerNorm layers, FFNs and Attention layers on the Med-VLMs. Our comprehensive studies span both small-scale and large-scale Med-VLMs, evaluating their performance under various fine-tuning paradigms across tasks such as Medical Visual Question Answering and Medical Imaging Report Generation. The findings reveal unique insights into the effects of intrinsic parameter fine-tuning methods on fine-tuning Med-VLMs to downstream tasks and expose fine-tuning solely the LayerNorm layers not only surpasses the efficiency of traditional PEFT methods but also retains the model's accuracy and generalization capabilities across a spectrum of medical downstream tasks. The experiments show LayerNorm fine-tuning's superior adaptability and scalability, particularly in the context of large-scale Med-VLMs.

[Arxiv](https://arxiv.org/abs/2404.16385)