# LLaCA：多模态大型语言持续助手

发布时间：2024年10月08日

`LLM理论` `人工智能` `多模态学习`

> LLaCA: Multimodal Large Language Continual Assistant

# 摘要

> 指令调整通过设计文本指令引导多模态大型语言模型 (MLLM) 对齐不同模态，是提升基础模型能力和可控性的关键技术。我们采用多模态持续指令调整 (MCIT) 来持续指导 MLLM 遵循人类意图。然而，现有梯度更新会严重破坏先前数据集的调整性能和零-shot 能力。指数移动平均 (EMA) 更新虽能追踪先前参数，但其稳定权重无法应对变化数据集，导致 MLLM 塑性和稳定性失衡。为此，我们提出多模态大型语言持续助手 (LLaCA) 方法，通过泰勒展开确定最优平衡权重，自动调整并显著提升性能。实验表明，我们的方法不仅大幅减少遗忘率（从 22.67 降至 2.68），还显著提高平均准确率（从 41.31 提升至 61.89）。代码即将发布。

> Instruction tuning guides the Multimodal Large Language Models (MLLMs) in aligning different modalities by designing text instructions, which seems to be an essential technique to enhance the capabilities and controllability of foundation models. In this framework, Multimodal Continual Instruction Tuning (MCIT) is adopted to continually instruct MLLMs to follow human intent in sequential datasets. We observe existing gradient update would heavily destroy the tuning performance on previous datasets and the zero-shot ability during continual instruction tuning. Exponential Moving Average (EMA) update policy owns the ability to trace previous parameters, which can aid in decreasing forgetting. However, its stable balance weight cannot deal with the ever-changing datasets, leading to the out-of-balance between plasticity and stability of MLLMs. In this paper, we propose a method called Multimodal Large Language Continual Assistant (LLaCA) to address the challenge. Starting from the trade-off prerequisite and EMA update, we propose the plasticity and stability ideal condition. Based on Taylor expansion in the loss function, we find the optimal balance weight is basically according to the gradient information and previous parameters. We automatically determine the balance weight and significantly improve the performance. Through comprehensive experiments on LLaVA-1.5 in a continual visual-question-answering benchmark, compared with baseline, our approach not only highly improves anti-forgetting ability (with reducing forgetting from 22.67 to 2.68), but also significantly promotes continual tuning performance (with increasing average accuracy from 41.31 to 61.89). Our code will be published soon.

[Arxiv](https://arxiv.org/abs/2410.10868)