# LLaVA-KD：多模态大型语言模型蒸馏框架

发布时间：2024年10月25日

`LLM应用` `人工智能` `计算机视觉`

> LLaVA-KD: A Framework of Distilling Multimodal Large Language Models

# 摘要

> 大型语言模型 (LLM) 的成功推动了多模态大型语言模型 (MLLM) 的研究，旨在实现视觉和语言的统一理解。然而，MLLM 的庞大体积和计算复杂性限制了其在资源有限环境中的应用。为此，我们提出了小规模 MLLM (s-MLLM)，旨在保留大规模模型 (l-MLLM) 的功能，同时降低计算需求，但性能有所下降。为解决这一问题，我们设计了 LLaVA-KD 框架，通过多模态蒸馏 (MDist) 和关系蒸馏 (RDist) 将 l-MLLM 的知识转移到 s-MLLM。我们还提出了三阶段训练方案：蒸馏预训练、监督微调和蒸馏微调，以最大化 s-MLLM 的潜力。实验证明，我们的方法在不改变模型架构的情况下显著提升了性能。代码即将在 https://github.com/caiyuxuan1120/LLaVA-KD 发布。

> The success of Large Language Models (LLM) has led researchers to explore Multimodal Large Language Models (MLLM) for unified visual and linguistic understanding. However, the increasing model size and computational complexity of MLLM limit their use in resource-constrained environments. Small-scale MLLM (s-MLLM) aims to retain the capabilities of the large-scale model (l-MLLM) while reducing computational demands, but resulting in a significant decline in performance. To address the aforementioned issues, we propose a novel LLaVA-KD framework to transfer knowledge from l-MLLM to s-MLLM. Specifically, we introduce Multimodal Distillation (MDist) to minimize the divergence between the visual-textual output distributions of l-MLLM and s-MLLM, and Relation Distillation (RDist) to transfer l-MLLM's ability to model correlations between visual features. Additionally, we propose a three-stage training scheme to fully exploit the potential of s-MLLM: 1) Distilled Pre-Training to align visual-textual representations, 2) Supervised Fine-Tuning to equip the model with multimodal understanding, and 3) Distilled Fine-Tuning to further transfer l-MLLM capabilities. Our approach significantly improves performance without altering the small model's architecture. Extensive experiments and ablation studies validate the effectiveness of each proposed component. Code will be available at https://github.com/Fantasyele/LLaVA-KD.

[Arxiv](https://arxiv.org/abs/2410.16236)