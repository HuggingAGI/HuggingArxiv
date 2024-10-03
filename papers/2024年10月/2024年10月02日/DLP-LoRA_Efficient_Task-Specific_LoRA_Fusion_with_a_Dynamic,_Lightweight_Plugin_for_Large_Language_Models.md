# DLP-LoRA：为大型语言模型量身定制的动态轻量级插件，实现高效的任务特定 LoRA 融合

发布时间：2024年10月02日

`LLM应用` `人工智能`

> DLP-LoRA: Efficient Task-Specific LoRA Fusion with a Dynamic, Lightweight Plugin for Large Language Models

# 摘要

> 大型语言模型 (LLM) 在各种任务中表现出色，但针对特定领域进行微调仍需大量资源。参数高效微调 (PEFT) 方法，如低秩适应 (LoRA)，通过微调少量参数来应对这一挑战。然而，现有融合多个 LoRA 的方法缺乏基于上下文的动态融合，且常因令牌级操作而增加推理时间。我们提出 DLP-LoRA，一种动态轻量级插件，采用仅 5M 参数的 mini-MLP 模块，通过 top-p 采样策略在句子级别动态融合多个 LoRA。此方法通过并行计算将推理时间降至单个 LoRA 推理时间的一半以下。在多项选择题和问答等 26 项任务的评估中，DLP-LoRA 在多项选择数据集上达到 92.34% 的平均准确率，并在问答数据集上显著提升 BLEU 和 ROUGE 分数，优于复合任务设置下的不同 LLM 骨干。DLP-LoRA 有效平衡性能与效率，成为 LLM 中动态多任务适应的实用方案。代码见 https://github.com/MeCuping/DLP-LoRA。

> Recent advancements in Large Language Models (LLMs) have achieved robust performance across diverse tasks, but fine-tuning these models for specific domains remains resource-intensive. Parameter-Efficient Fine-Tuning (PEFT) methods like Low-Rank Adaptation (LoRA) address this challenge by fine-tuning a small subset of parameters. However, existing methods for fusing multiple LoRAs lack dynamic fusion based on contextual inputs and often increase inference time due to token-level operations. We propose DLP-LoRA, a Dynamic Lightweight Plugin that employs a mini-MLP module with only 5M parameters to dynamically fuse multiple LoRAs at the sentence level using top-p sampling strategies. This approach reduces inference time to less than twice that of single LoRA inference by leveraging parallel computation. Evaluations across 26 tasks-including multiple-choice questions and question answering-demonstrate that DLP-LoRA achieves an average accuracy of 92.34% on multiple-choice datasets and significant improvements in BLEU and ROUGE scores on QA datasets, outperforming different LLMs backbones under composite task settings. DLP-LoRA effectively balances performance and efficiency, making it a practical solution for dynamic multi-task adaptation in LLMs. Our code is available at https://github.com/MeCuping/DLP-LoRA.

[Arxiv](https://arxiv.org/abs/2410.01497)