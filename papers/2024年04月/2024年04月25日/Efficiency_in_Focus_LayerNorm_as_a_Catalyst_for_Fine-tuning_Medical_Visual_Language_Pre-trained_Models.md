# 聚焦效率：LayerNorm 在微调医学视觉语言预训练模型中的关键作用

发布时间：2024年04月25日

`LLM应用` `人工智能`

> Efficiency in Focus: LayerNorm as a Catalyst for Fine-tuning Medical Visual Language Pre-trained Models

# 摘要

> 在医学视觉语言模型（Med-VLMs）的研究中，探索一种普遍且高效的微调机制尤为关键，特别是在跨学科研究者面临训练资源匮乏的挑战时。面对医学领域的特殊挑战，如数据范围有限和领域特定需求显著，对参数高效微调（PEFT）方法进行评估和定制化以适应Med-VLMs显得尤为重要。目前，大多数应用于Med-VLMs的PEFT方法尚未经过全面探究，通常只是简单地对模型结构或输入进行一些扩展。然而，对模型内部组件进行微调往往能够带来更佳的泛化和一致性，其对Med-VLMs性能的影响却被普遍忽视，研究也相对不足。本文旨在探索一种传统PEFT方法之外的新途径，尤其是研究微调LayerNorm层、FFN和注意力层对Med-VLMs的影响。我们进行了深入研究，涵盖了从小规模到大规模的Med-VLMs，并在多种微调框架下，对它们在医学视觉问答和医学影像报告生成等任务中的表现进行了评估。研究发现，内在参数微调方法对Med-VLMs在下游任务中的微调效果具有独特影响，并且仅微调LayerNorm层不仅在效率上超越了传统PEFT方法，而且在一系列医学相关下游任务中保持了模型的准确性和泛化能力。实验结果进一步证实了LayerNorm微调在大型Med-VLMs中的卓越适应性和可扩展性。

> In the realm of Medical Visual Language Models (Med-VLMs), the quest for universal efficient fine-tuning mechanisms remains paramount, especially given researchers in interdisciplinary fields are often extremely short of training resources, yet largely unexplored. Given the unique challenges in the medical domain, such as limited data scope and significant domain-specific requirements, evaluating and adapting Parameter-Efficient Fine-Tuning (PEFT) methods specifically for Med-VLMs is essential. Most of the current PEFT methods on Med-VLMs have yet to be comprehensively investigated but mainly focus on adding some components to the model's structure or input. However, fine-tuning intrinsic model components often yields better generality and consistency, and its impact on the ultimate performance of Med-VLMs has been widely overlooked and remains understudied. In this paper, we endeavour to explore an alternative to traditional PEFT methods, especially the impact of fine-tuning LayerNorm layers, FFNs and Attention layers on the Med-VLMs. Our comprehensive studies span both small-scale and large-scale Med-VLMs, evaluating their performance under various fine-tuning paradigms across tasks such as Medical Visual Question Answering and Medical Imaging Report Generation. The findings reveal unique insights into the effects of intrinsic parameter fine-tuning methods on fine-tuning Med-VLMs to downstream tasks and expose fine-tuning solely the LayerNorm layers not only surpasses the efficiency of traditional PEFT methods but also retains the model's accuracy and generalization capabilities across a spectrum of medical downstream tasks. The experiments show LayerNorm fine-tuning's superior adaptability and scalability, particularly in the context of large-scale Med-VLMs.

[Arxiv](https://arxiv.org/abs/2404.16385)