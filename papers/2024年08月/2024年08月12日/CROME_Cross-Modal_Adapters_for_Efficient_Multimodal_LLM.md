# CROME：高效多模态 LLM 的跨模态适配器

发布时间：2024年08月12日

`LLM应用` `人工智能` `计算机视觉`

> CROME: Cross-Modal Adapters for Efficient Multimodal LLM

# 摘要

> 多模态大型语言模型（MLLMs）虽在图像与语言处理上表现出色，但其广泛应用受限于成本效益的训练与适应性问题。传统方法常需昂贵的模型重训且适应性有限，且对零-shot性能的改进未能充分指导任务特定调优。为此，我们推出了CROME框架，该框架通过创新的门控跨模态适配器，在输入至冻结的LLM前有效融合视觉与文本信息，以轻量级设计实现高效跨模态理解。CROME不仅在视觉问答与指令遵循任务上展现了卓越的零-shot性能，更在微调过程中实现了极高的参数效率，媲美特定任务的顶尖方法。这一成果揭示了预LM对齐在构建可扩展、适应性强且参数高效的多模态模型方面的巨大潜力。

> Multimodal Large Language Models (MLLMs) demonstrate remarkable image-language capabilities, but their widespread use faces challenges in cost-effective training and adaptation. Existing approaches often necessitate expensive language model retraining and limited adaptability. Additionally, the current focus on zero-shot performance improvements offers insufficient guidance for task-specific tuning. We propose CROME, an efficient vision-language instruction tuning framework. It features a novel gated cross-modal adapter that effectively combines visual and textual representations prior to input into a frozen LLM. This lightweight adapter, trained with minimal parameters, enables efficient cross-modal understanding. Notably, CROME demonstrates superior zero-shot performance on standard visual question answering and instruction-following benchmarks. Moreover, it yields fine-tuning with exceptional parameter efficiency, competing with task-specific specialist state-of-the-art methods. CROME demonstrates the potential of pre-LM alignment for building scalable, adaptable, and parameter-efficient multimodal models.

[Arxiv](https://arxiv.org/abs/2408.06610)