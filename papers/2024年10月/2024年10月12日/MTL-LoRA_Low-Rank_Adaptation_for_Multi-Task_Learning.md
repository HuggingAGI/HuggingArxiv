# MTL-LoRA：多任务学习的低秩适应

发布时间：2024年10月12日

`LLM理论` `人工智能` `多任务学习`

> MTL-LoRA: Low-Rank Adaptation for Multi-Task Learning

# 摘要

> 参数高效微调 (PEFT) 中，LoRA 因其简便有效而备受青睐。但在多任务学习 (MTL) 中，LoRA 将不同任务的高维稀疏特征压缩至同一低维空间，导致任务间干扰，性能受限。为此，我们推出 MTL-LoRA，既保留低秩适应的优点，又显著提升多任务处理能力。MTL-LoRA 通过引入任务自适应参数，精准区分任务信息，并在低维空间内高效整合共享知识。这使得预训练的大型语言模型 (LLM) 能以少量参数灵活适应各类任务领域。实验结果显示，MTL-LoRA 在多任务学习中超越了 LoRA 及其变体，且所需学习参数更少。

> Parameter-efficient fine-tuning (PEFT) has been widely employed for domain adaptation, with LoRA being one of the most prominent methods due to its simplicity and effectiveness. However, in multi-task learning (MTL) scenarios, LoRA tends to obscure the distinction between tasks by projecting sparse high-dimensional features from different tasks into the same dense low-dimensional intrinsic space. This leads to task interference and suboptimal performance for LoRA and its variants. To tackle this challenge, we propose MTL-LoRA, which retains the advantages of low-rank adaptation while significantly enhancing multi-task learning capabilities. MTL-LoRA augments LoRA by incorporating additional task-adaptive parameters that differentiate task-specific information and effectively capture shared knowledge across various tasks within low-dimensional spaces. This approach enables large language models (LLMs) pre-trained on general corpus to adapt to different target task domains with a limited number of trainable parameters. Comprehensive experimental results, including evaluations on public academic benchmarks for natural language understanding, commonsense reasoning, and image-text understanding, as well as real-world industrial text Ads relevance datasets, demonstrate that MTL-LoRA outperforms LoRA and its various variants with comparable or even fewer learnable parameters in multitask learning.

[Arxiv](https://arxiv.org/abs/2410.09437)