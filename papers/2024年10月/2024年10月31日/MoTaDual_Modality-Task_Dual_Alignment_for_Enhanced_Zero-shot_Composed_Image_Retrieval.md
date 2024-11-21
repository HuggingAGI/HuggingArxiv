# MoTaDual：实现增强零样本组合图像检索的模态-任务双重对齐

发布时间：2024年10月31日

`LLM应用` `图像检索` `视觉语言`

> MoTaDual: Modality-Task Dual Alignment for Enhanced Zero-shot Composed Image Retrieval

# 摘要

> 组合图像检索（CIR）是一项颇具挑战性的视觉语言任务，借助双模态（图像+文本）查询来检索目标图像。尽管有监督的 CIR 表现不俗，但对高价人工标注三元组的依赖限制了其可扩展性和零样本能力。为应对此问题，零样本组合图像检索（ZS-CIR）及基于投影的方法应运而生。然而，这类方法面临两大主要问题，即预训练（图像$\leftrightarrow$文本）与推理（图像+文本$ightarrow$图像）之间的任务差异，以及模态差异。后者涉及基于纯文本投影训练的方法，因为在推理时需要从参考图像提取特征。在本文中，我们提出了一个两阶段框架来化解这两个差异。首先，为保障效率和可扩展性，在大规模的字幕数据集上预训练了一个文本反转网络。接着，我们提出模态-任务双重对齐（MoTaDual）作为第二阶段，其中大型语言模型（LLMs）生成三元组数据用于微调，此外，在多模态情境中引入提示学习，有效缓解了模态和任务差异。实验结果显示，我们的 MoTaDual 在四个广泛使用的 ZS-CIR 基准测试中达到了最先进的性能，同时保持了较低的训练时间和计算成本。代码即将公布。

> Composed Image Retrieval (CIR) is a challenging vision-language task, utilizing bi-modal (image+text) queries to retrieve target images. Despite the impressive performance of supervised CIR, the dependence on costly, manually-labeled triplets limits its scalability and zero-shot capability. To address this issue, zero-shot composed image retrieval (ZS-CIR) is presented along with projection-based approaches. However, such methods face two major problems, i.e., task discrepancy between pre-training (image $\leftrightarrow$ text) and inference (image+text $\rightarrow$ image), and modality discrepancy. The latter pertains to approaches based on text-only projection training due to the necessity of feature extraction from the reference image during inference. In this paper, we propose a two-stage framework to tackle both discrepancies. First, to ensure efficiency and scalability, a textual inversion network is pre-trained on large-scale caption datasets. Subsequently, we put forward Modality-Task Dual Alignment (MoTaDual) as the second stage, where large-language models (LLMs) generate triplet data for fine-tuning, and additionally, prompt learning is introduced in a multi-modal context to effectively alleviate both modality and task discrepancies. The experimental results show that our MoTaDual achieves the state-of-the-art performance across four widely used ZS-CIR benchmarks, while maintaining low training time and computational cost. The code will be released soon.

[Arxiv](https://arxiv.org/abs/2410.23736)