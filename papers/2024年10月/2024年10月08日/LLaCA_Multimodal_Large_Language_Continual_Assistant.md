# LLaCA：多模态大型语言持续助手

发布时间：2024年10月08日

`LLM应用` `人工智能` `机器学习`

> LLaCA: Multimodal Large Language Continual Assistant

# 摘要

> 指令调优通过设计文本指令，引导多模态大型语言模型（MLLM）对齐不同模态，是提升基础模型能力和可控性的关键技术。在此框架中，多模态持续指令调优（MCIT）用于持续指导MLLM在顺序数据集中遵循人类意图。然而，现有梯度更新会严重破坏之前数据集的调优性能和零-shot能力。指数移动平均（EMA）更新虽能追踪先前参数，减少遗忘，但其稳定权重难以应对变化数据集，导致MLLM的塑性和稳定性失衡。为此，我们提出多模态大型语言持续助手（LLaCA），通过权衡前提和EMA更新，提出塑性和稳定性的理想条件，并基于损失函数的泰勒展开，自动确定最佳平衡权重，显著提升性能。实验表明，LLaCA不仅大幅提高抗遗忘能力（遗忘从22.67降至2.68），还显著提升持续调优性能（平均准确率从41.31升至61.89）。代码即将发布。

> Instruction tuning guides the Multimodal Large Language Models (MLLMs) in aligning different modalities by designing text instructions, which seems to be an essential technique to enhance the capabilities and controllability of foundation models. In this framework, Multimodal Continual Instruction Tuning (MCIT) is adopted to continually instruct MLLMs to follow human intent in sequential datasets. We observe existing gradient update would heavily destroy the tuning performance on previous datasets and the zero-shot ability during continual instruction tuning. Exponential Moving Average (EMA) update policy owns the ability to trace previous parameters, which can aid in decreasing forgetting. However, its stable balance weight cannot deal with the ever-changing datasets, leading to the out-of-balance between plasticity and stability of MLLMs. In this paper, we propose a method called Multimodal Large Language Continual Assistant (LLaCA) to address the challenge. Starting from the trade-off prerequisite and EMA update, we propose the plasticity and stability ideal condition. Based on Taylor expansion in the loss function, we find the optimal balance weight is basically according to the gradient information and previous parameters. We automatically determine the balance weight and significantly improve the performance. Through comprehensive experiments on LLaVA-1.5 in a continual visual-question-answering benchmark, compared with baseline, our approach not only highly improves anti-forgetting ability (with reducing forgetting from 22.67 to 2.68), but also significantly promotes continual tuning performance (with increasing average accuracy from 41.31 to 61.89). Our code will be published soon.

[Arxiv](https://arxiv.org/abs/2410.10868)