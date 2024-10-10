# 探索大型视觉-语言模型中跨模态对齐的奥秘，聚焦模态集成率的影响。

发布时间：2024年10月09日

`LLM理论` `人工智能` `计算机视觉`

> Deciphering Cross-Modal Alignment in Large Vision-Language Models with Modality Integration Rate

# 摘要

> 我们引入了模态整合率（MIR），这一指标既有效又稳健，能够全面评估大型视觉语言模型（LVLMs）的多模态预训练质量。大规模预训练对构建强大的LVLMs至关重要，但如何在无需昂贵监督微调的情况下评估其质量，仍是一个未被充分探索的领域。传统的预训练指标如损失、困惑度和上下文评估，在将LLM与新模态对齐时表现不佳。这导致LVLMs在预训练阶段的研究受阻，尤其是在数据选择和模块设计方面。为此，我们提出从模态间分布距离的角度来评估预训练质量，并设计了MIR。MIR不仅能够有效反映预训练质量，还与微调后的性能正相关，且对不同数据集表现稳健，并适用于多种训练配置和架构。通过一系列实验，我们验证了MIR在指导数据选择、训练策略和模型设计方面的有效性。我们期待MIR能成为构建强大LVLMs的有力工具，并推动模态对齐研究的进一步发展。代码已公开在：https://github.com/shikiw/Modality-Integration-Rate。

> We present the Modality Integration Rate (MIR), an effective, robust, and generalized metric to indicate the multi-modal pre-training quality of Large Vision Language Models (LVLMs). Large-scale pre-training plays a critical role in building capable LVLMs, while evaluating its training quality without the costly supervised fine-tuning stage is under-explored. Loss, perplexity, and in-context evaluation results are commonly used pre-training metrics for Large Language Models (LLMs), while we observed that these metrics are less indicative when aligning a well-trained LLM with a new modality. Due to the lack of proper metrics, the research of LVLMs in the critical pre-training stage is hindered greatly, including the training data choice, efficient module design, etc. In this paper, we propose evaluating the pre-training quality from the inter-modal distribution distance perspective and present MIR, the Modality Integration Rate, which is 1) \textbf{Effective} to represent the pre-training quality and show a positive relation with the benchmark performance after supervised fine-tuning. 2) \textbf{Robust} toward different training/evaluation data. 3) \textbf{Generalize} across training configurations and architecture choices. We conduct a series of pre-training experiments to explore the effectiveness of MIR and observe satisfactory results that MIR is indicative about training data selection, training strategy schedule, and model architecture design to get better pre-training results. We hope MIR could be a helpful metric for building capable LVLMs and inspire the following research about modality alignment in different areas. Our code is at: https://github.com/shikiw/Modality-Integration-Rate.

[Arxiv](https://arxiv.org/abs/2410.07167)