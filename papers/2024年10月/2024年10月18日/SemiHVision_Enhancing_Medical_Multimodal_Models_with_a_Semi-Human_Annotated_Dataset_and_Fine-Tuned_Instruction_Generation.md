# SemiHVision：借助半人工标注的数据集和精细调整的指令生成，提升医学多模态模型的性能。

发布时间：2024年10月18日

`LLM应用` `人工智能`

> SemiHVision: Enhancing Medical Multimodal Models with a Semi-Human Annotated Dataset and Fine-Tuned Instruction Generation

# 摘要

> 多模态大型语言模型（MLLM）虽有显著进展，但在医疗领域因专业知识有限而面临挑战。尽管近期医疗MLLM在实验室表现出色，实际应用中却常显不足，凸显研究与实践间的巨大鸿沟。本文旨在从数据收集、模型微调到评估各环节解决此问题。我们引入SemiHVision数据集，结合人工注释与自动化增强技术，提升医学知识与诊断推理。微调PMC-Cambrian-8B-AN模型，使其在SLAKE和VQA-RAD等传统基准上超越HuatuoGPT-Vision-34B与Claude3-Opus。评估发现，传统基准无法准确反映临床任务能力，故推出JAMA临床挑战新基准，PMC-Cambrian-AN在此基准上以1.29的GPT-4分数领先，展示卓越诊断推理能力。

> Multimodal large language models (MLLMs) have made significant strides, yet they face challenges in the medical domain due to limited specialized knowledge. While recent medical MLLMs demonstrate strong performance in lab settings, they often struggle in real-world applications, highlighting a substantial gap between research and practice. In this paper, we seek to address this gap at various stages of the end-to-end learning pipeline, including data collection, model fine-tuning, and evaluation. At the data collection stage, we introduce SemiHVision, a dataset that combines human annotations with automated augmentation techniques to improve both medical knowledge representation and diagnostic reasoning. For model fine-tuning, we trained PMC-Cambrian-8B-AN over 2400 H100 GPU hours, resulting in performance that surpasses public medical models like HuatuoGPT-Vision-34B (79.0% vs. 66.7%) and private general models like Claude3-Opus (55.7%) on traditional benchmarks such as SLAKE and VQA-RAD. In the evaluation phase, we observed that traditional benchmarks cannot accurately reflect realistic clinical task capabilities. To overcome this limitation and provide more targeted guidance for model evaluation, we introduce the JAMA Clinical Challenge, a novel benchmark specifically designed to evaluate diagnostic reasoning. On this benchmark, PMC-Cambrian-AN achieves state-of-the-art performance with a GPT-4 score of 1.29, significantly outperforming HuatuoGPT-Vision-34B (1.13) and Claude3-Opus (1.17), demonstrating its superior diagnostic reasoning abilities.

[Arxiv](https://arxiv.org/abs/2410.14948)