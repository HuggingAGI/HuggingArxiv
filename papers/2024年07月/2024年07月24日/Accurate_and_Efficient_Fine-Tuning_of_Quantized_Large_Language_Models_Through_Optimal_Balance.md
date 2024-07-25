# 精准高效地微调量化大型语言模型，关键在于找到最佳平衡点。

发布时间：2024年07月24日

`LLM理论` `人工智能` `计算机科学`

> Accurate and Efficient Fine-Tuning of Quantized Large Language Models Through Optimal Balance

# 摘要

> 大型语言模型 (LLM) 在多领域表现卓越，但其庞大的参数数量使得微调变得棘手，限制了应用与部署。现有方案结合参数量化与低秩适应 (LoRA)，虽大幅降低内存消耗，却带来显著性能损失。本文揭示了微调量化预训练模型中的不平衡问题：适配器输入输出过于复杂，而适应性训练效率低下。为此，我们提出平衡秩适应的量化 LLM (Q-BaRA)，简化适配器设计，提升秩以优化微调平衡。针对需部署为低精度推理模型的场景，我们引入更高秩适应的量化感知微调 (QA-HiRA)，简化适配器并实现更高秩，与预训练模型块级量化对齐。Q-BaRA 与 QA-HiRA 均易于实施，提供以下优化：(i) Q-BaRA 在准确性上超越其他方案，且训练参数与计算量不变；(ii) QA-HiRA 在微调后自然合并适配器参数，准确性领先。我们已将 Q-BaRA 和 QA-HiRA 应用于 LLaMA 及 LLaMA2 系列，并在多样微调数据集与下游场景中验证其效能。代码将发布于 \href{https://github.com/xiaocaigou/qbaraqahira}{https://github.com/xiaocaigou/qbaraqahira}。

> Large Language Models (LLMs) have demonstrated impressive performance across various domains. However, the enormous number of model parameters makes fine-tuning challenging, significantly limiting their application and deployment. Existing solutions combine parameter quantization with Low-Rank Adaptation (LoRA), greatly reducing memory usage but resulting in noticeable performance degradation. In this paper, we identify an imbalance in fine-tuning quantized pre-trained models: overly complex adapter inputs and outputs versus low effective trainability of the adaptation. We propose Quantized LLMs with Balanced-rank Adaptation (Q-BaRA), which simplifies the adapter inputs and outputs while increasing the adapter's rank to achieve a more suitable balance for fine-tuning quantized LLMs. Additionally, for scenarios where fine-tuned LLMs need to be deployed as low-precision inference models, we introduce Quantization-Aware Fine-tuning with Higher Rank Adaptation (QA-HiRA), which simplifies the adapter inputs and outputs to align with the pre-trained model's block-wise quantization while employing a single matrix to achieve a higher rank. Both Q-BaRA and QA-HiRA are easily implemented and offer the following optimizations: (i) Q-BaRA consistently achieves the highest accuracy compared to baselines and other variants, requiring the same number of trainable parameters and computational effort; (ii) QA-HiRA naturally merges adapter parameters into the block-wise quantized model after fine-tuning, achieving the highest accuracy compared to other methods. We apply our Q-BaRA and QA-HiRA to the LLaMA and LLaMA2 model families and validate their effectiveness across different fine-tuning datasets and downstream scenarios.
  Code will be made available at \href{https://github.com/xiaocaigou/qbaraqahira}{https://github.com/xiaocaigou/qbaraqahira}

[Arxiv](https://arxiv.org/abs/2407.17029)