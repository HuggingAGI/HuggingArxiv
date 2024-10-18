# 微调语言模型于多数据集，精准分类引用意图

发布时间：2024年10月17日

`LLM应用` `学术研究`

> Fine-Tuning Language Models on Multiple Datasets for Citation Intention Classification

# 摘要

> 引用意图分类 (CIC) 工具通过识别引用意图（如背景、动机）帮助读者评估文献贡献。研究表明，预训练语言模型 (PLM) 如 SciBERT 在 CIC 任务中表现卓越。PLM 通过自监督任务在大规模文本上训练，能快速适应 CIC 任务。然而，微调时易在小数据集上过拟合。为此，我们提出多任务学习 (MTL) 框架，联合微调 PLM 在主数据集和多个辅助 CIC 数据集上，以增强监督信号。我们还开发了数据驱动的任务关系学习 (TRL) 方法，控制辅助数据集的贡献，避免负迁移和超参数调优的复杂性。实验表明，通过添加数据集微调，PLM 在主数据集上的泛化性能显著提升。我们的框架在小型数据集上比现有最先进模型高出 7% 到 11%，同时在大数据集上表现优异。

> Citation intention Classification (CIC) tools classify citations by their intention (e.g., background, motivation) and assist readers in evaluating the contribution of scientific literature. Prior research has shown that pretrained language models (PLMs) such as SciBERT can achieve state-of-the-art performance on CIC benchmarks. PLMs are trained via self-supervision tasks on a large corpus of general text and can quickly adapt to CIC tasks via moderate fine-tuning on the corresponding dataset. Despite their advantages, PLMs can easily overfit small datasets during fine-tuning. In this paper, we propose a multi-task learning (MTL) framework that jointly fine-tunes PLMs on a dataset of primary interest together with multiple auxiliary CIC datasets to take advantage of additional supervision signals. We develop a data-driven task relation learning (TRL) method that controls the contribution of auxiliary datasets to avoid negative transfer and expensive hyper-parameter tuning. We conduct experiments on three CIC datasets and show that fine-tuning with additional datasets can improve the PLMs' generalization performance on the primary dataset. PLMs fine-tuned with our proposed framework outperform the current state-of-the-art models by 7% to 11% on small datasets while aligning with the best-performing model on a large dataset.

[Arxiv](https://arxiv.org/abs/2410.13332)