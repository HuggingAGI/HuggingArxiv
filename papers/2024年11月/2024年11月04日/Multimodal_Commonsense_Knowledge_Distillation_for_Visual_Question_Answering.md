# 用于视觉问答的多模态常识知识蒸馏

发布时间：2024年11月04日

`LLM应用` `视觉问答` `知识蒸馏`

> Multimodal Commonsense Knowledge Distillation for Visual Question Answering

# 摘要

> 现有的多模态大型语言模型（MLLMs）和视觉语言预训练模型（VLPMs）在一般的视觉问答（VQA）中表现出色。然而，由于生成高质量提示的挑战和微调的高计算成本，这些模型在处理需要外部常识知识的 VQA 问题时遇到困难。在这项工作中，我们提出了一种新颖的基于图的多模态常识知识蒸馏框架，该框架通过图卷积网络（GCN）在教师-学生环境下构建了一个关于常识知识、视觉对象和问题的统一关系图。这个提出的框架对于任何类型的教师和学生模型都具有灵活性，无需进一步微调，并且在 ScienceQA 数据集上取得了有竞争力的性能。

> Existing Multimodal Large Language Models (MLLMs) and Visual Language Pretrained Models (VLPMs) have shown remarkable performances in the general Visual Question Answering (VQA). However, these models struggle with VQA questions that require external commonsense knowledge due to the challenges in generating high-quality prompts and the high computational costs of fine-tuning. In this work, we propose a novel graph-based multimodal commonsense knowledge distillation framework that constructs a unified relational graph over commonsense knowledge, visual objects and questions through a Graph Convolutional Network (GCN) following a teacher-student environment. This proposed framework is flexible with any type of teacher and student models without further fine-tuning, and has achieved competitive performances on the ScienceQA dataset.

[Arxiv](https://arxiv.org/abs/2411.02722)