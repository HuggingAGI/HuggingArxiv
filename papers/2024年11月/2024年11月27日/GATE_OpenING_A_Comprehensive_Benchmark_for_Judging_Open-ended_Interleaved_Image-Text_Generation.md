# GATE OpenING：评判开放式交错图像 - 文本生成的综合性基准

发布时间：2024年11月27日

`LLM应用` `多模态生成` `图像-文本生成`

> GATE OpenING: A Comprehensive Benchmark for Judging Open-ended Interleaved Image-Text Generation

# 摘要

> 多模态大型语言模型（MLLMs）在视觉理解和生成任务上取得显著进步。然而，生成交错的图像-文本内容仍是难题，这需要融合多模态的理解与生成能力。尽管统一模型的发展带来新解法，但因数据规模和多样性受限，现有基准难以评估这些方法。为填补此空缺，我们推出 GATE OpenING（OpenING），这一综合基准涵盖 56 个真实世界任务的 5400 个高质量人工标注实例。OpenING 包含诸如旅游指南、设计和头脑风暴等各类日常场景，为交错生成方法提供强大平台。此外，我们还给出 IntJudge，一个用于评估开放式多模态生成方法的评判模型。通过新的数据管道训练，我们的 IntJudge 与人类判断的一致率达 82.42%，比基于 GPT 的评估器高 11.34%。在 OpenING 上的大量实验表明，当下的交错生成方法仍有很大提升空间。进一步呈现关于交错图像-文本生成的关键发现，以引导下一代模型的开发。OpenING 在 https://opening.github.io 开源。

> Multimodal Large Language Models (MLLMs) have made significant strides in visual understanding and generation tasks. However, generating interleaved image-text content remains a challenge, which requires integrated multimodal understanding and generation abilities. While the progress in unified models offers new solutions, existing benchmarks are insufficient for evaluating these methods due to data size and diversity limitations. To bridge this gap, we introduce GATE OpenING (OpenING), a comprehensive benchmark comprising 5,400 high-quality human-annotated instances across 56 real-world tasks. OpenING covers diverse daily scenarios such as travel guide, design, and brainstorming, offering a robust platform for challenging interleaved generation methods. In addition, we present IntJudge, a judge model for evaluating open-ended multimodal generation methods. Trained with a novel data pipeline, our IntJudge achieves an agreement rate of 82. 42% with human judgments, outperforming GPT-based evaluators by 11.34%. Extensive experiments on OpenING reveal that current interleaved generation methods still have substantial room for improvement. Key findings on interleaved image-text generation are further presented to guide the development of next-generation models. The OpenING is open-sourced at https://opening.github.io.

[Arxiv](https://arxiv.org/abs/2411.18499)