# LoRTA：大型语言模型的低秩张量适应技术

发布时间：2024年10月05日

`LLM理论` `机器学习` `人工智能`

> LoRTA: Low Rank Tensor Adaptation of Large Language Models

# 摘要

> LoRA 是一种高效的 PEFT 方法，通过低秩矩阵在每层进行模型更新，大幅减少了微调时的参数和资源需求。然而，低秩矩阵的使用仍导致可训练参数的下限较高。本文提出了一种新的低秩张量参数化方法，不仅显著减少了参数数量，还提供了更精细的适配器控制。实验结果显示，该方法在多个基准测试中表现出色，既高效又有效，大幅减少了参数数量，同时保持了优异的性能。

> Low Rank Adaptation (LoRA) is a popular Parameter Efficient Fine Tuning (PEFT) method that effectively adapts large pre-trained models for downstream tasks. LoRA parameterizes model updates using low-rank matrices at each layer, significantly reducing the number of trainable parameters and, consequently, resource requirements during fine-tuning. However, the lower bound on the number of trainable parameters remains high due to the use of the low-rank matrix model. In this paper, we address this limitation by proposing a novel approach that employs a low rank tensor parametrization for model updates. The proposed low rank tensor model can significantly reduce the number of trainable parameters, while also allowing for finer-grained control over adapter size. Our experiments on Natural Language Understanding, Instruction Tuning, Preference Optimization and Protein Folding benchmarks demonstrate that our method is both efficient and effective for fine-tuning large language models, achieving a substantial reduction in the number of parameters while maintaining comparable performance.

[Arxiv](https://arxiv.org/abs/2410.04060)