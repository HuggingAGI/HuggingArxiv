# 微调驱动：引领大型语言模型前行

发布时间：2024年09月17日

`LLM理论` `机器学习`

> Propulsion: Steering LLM with Tiny Fine-Tuning

# 摘要

> 大型语言模型 (LLM) 的迅猛发展彻底革新了自然语言处理 (NLP) 领域。然而，为特定任务微调这些模型既昂贵又可能损害预学知识。为此，我们推出了 Propulsion，一种创新的参数高效微调 (PEFT) 方法，旨在提升任务性能的同时大幅降低计算负担。受物理运动中精准调整的启发，Propulsion 通过选择性调整预训练模型的特定维度，引导输出朝向任务目标，而无需改动模型参数。通过在预训练层加入轻量级可训练参数，我们有效减少了微调时的参数更新，避免了过拟合和知识覆盖。理论分析和神经切线核 (NTK) 理论证实，Propulsion 以极少的可训练参数实现了接近全量微调的效果。实证结果显示，Propulsion 将参数数量从 355.3 百万锐减至 0.086 百万，性能媲美 LoRA 等标准方法，参数效率却提升了十倍以上。

> The rapid advancements in Large Language Models (LLMs) have revolutionized natural language processing (NLP) and related fields. However, fine-tuning these models for specific tasks remains computationally expensive and risks degrading pre-learned features. To address these challenges, we propose Propulsion, a novel parameter efficient fine-tuning (PEFT) method designed to optimize task-specific performance while drastically reducing computational overhead. Inspired by the concept of controlled adjustments in physical motion, Propulsion selectively re-scales specific dimensions of a pre-trained model, guiding output predictions toward task objectives without modifying the model's parameters. By introducing lightweight, trainable Propulsion parameters at the pre-trained layer, we minimize the number of parameters updated during fine-tuning, preventing overfitting or overwriting of existing knowledge. Our theoretical analysis, supported by Neural Tangent Kernel (NTK) theory, shows that Propulsion approximates the performance of full fine-tuning with far fewer trainable parameters. Empirically, Propulsion reduces the parameter count from 355.3 million to just 0.086 million, achieving over a 10x reduction compared to standard approaches like LoRA while maintaining competitive performance across benchmarks.

[Arxiv](https://arxiv.org/abs/2409.10927)