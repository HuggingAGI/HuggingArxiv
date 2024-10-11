# 辩证行为疗法在 LLM 提示中的应用

发布时间：2024年10月10日

`LLM应用` `人工智能`

> Dialectical Behavior Therapy Approach to LLM Prompting

# 摘要

> 大型语言模型在应用 CoT 提示技术时，在各种推理任务上表现卓越。然而，解决复杂推理任务仍具挑战。本文提出了一种受 DBT 启发的创新提示策略，通过将 DBT 的对话塑造概念应用于提示构建，显著提升了较小模型的性能。实验结果显示，在 StrategyQA 和 Aqua 数据集上分别实现了 7% 和 4.8% 的准确性提升，而在 GSM8K 数据集上则实现了 5.3% 的提升。

> Large language models demonstrated state-of-the-art results on various reasoning tasks when applying the chain-of-thought (CoT) prompting technique. CoT prompting guides the model into breaking tasks into a few intermediate steps and provides step-by-step demonstrations. However, solving complex reasoning tasks remains a challenge. In this paper, we propose a novel prompting strategy inspired by Dialectical Behavioral Therapy (DBT). DBT, a form of cognitive-behavioral therapy, aims to help individuals cope with stress by developing a system of reasoning. We applied DBT's basic concepts of shaping dialog to construct prompts and conducted experiments on different datasets and LLMs with various numbers of parameters. Our results show that prompts crafted with DBT techniques significantly improve results on smaller models, achieving a 7% increase in accuracy on the StrategyQA, 4.8% on Aqua dataset using 8b parameters model, and a 16.2% increase on the StrategyQA, 5.3% on GSM8K dataset with 14b parameters model.

[Arxiv](https://arxiv.org/abs/2410.07768)