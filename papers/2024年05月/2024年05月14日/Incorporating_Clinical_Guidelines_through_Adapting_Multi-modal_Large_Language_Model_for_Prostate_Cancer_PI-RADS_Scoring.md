# 融合临床指南：多模态大型语言模型在前列腺癌PI-RADS评分中的应用

发布时间：2024年05月14日

`LLM应用

这篇论文探讨了如何将多模态大型语言模型（MLLM）应用于前列腺影像报告和数据系统（PI-RADS）评分中，通过整合前列腺影像报告和数据系统临床指南（PICG）来提高评分的准确性。这种方法涉及对MLLM进行微调，以适应特定的医学影像处理需求，并将临床指南的信息融入模型中，从而提升深度学习模型的性能。因此，这篇论文属于LLM应用类别，因为它展示了如何将大型语言模型应用于特定的实际问题，即医学影像分析和诊断。` `医疗影像` `人工智能辅助诊断`

> Incorporating Clinical Guidelines through Adapting Multi-modal Large Language Model for Prostate Cancer PI-RADS Scoring

# 摘要

> 前列腺影像报告和数据系统（PI-RADS）是诊断临床显著性前列腺癌的关键工具，尤其是在MRI影像领域。然而，现有的深度学习PI-RADS评分方法往往忽视了放射科医生依赖的PI-RADS临床指南（PICG），这可能影响评分的准确性。本文提出了一种创新方法，利用多模态大型语言模型（MLLM）将PICG无缝融入PI-RADS评分，无需额外标注和参数。我们的方法分为两个微调阶段：首先，我们定制了一个处理3D MRI图像的领域适配层，并优化了MLLM指令以区分不同的MRI模态；其次，我们将PICG转化为模型指令，引导生成受PICG影响的图像特征。通过特征蒸馏，我们确保评分网络与PICG指导的图像特征保持一致，从而有效整合了PICG信息。我们在公开数据集上训练模型，并在真实世界的内部数据集上验证了其性能，实验结果显示，我们的方法显著提升了评分网络的准确性。

> The Prostate Imaging Reporting and Data System (PI-RADS) is pivotal in the diagnosis of clinically significant prostate cancer through MRI imaging. Current deep learning-based PI-RADS scoring methods often lack the incorporation of essential PI-RADS clinical guidelines~(PICG) utilized by radiologists, potentially compromising scoring accuracy. This paper introduces a novel approach that adapts a multi-modal large language model (MLLM) to incorporate PICG into PI-RADS scoring without additional annotations and network parameters. We present a two-stage fine-tuning process aimed at adapting MLLMs originally trained on natural images to the MRI data domain while effectively integrating the PICG. In the first stage, we develop a domain adapter layer specifically tailored for processing 3D MRI image inputs and design the MLLM instructions to differentiate MRI modalities effectively. In the second stage, we translate PICG into guiding instructions for the model to generate PICG-guided image features. Through feature distillation, we align scoring network features with the PICG-guided image feature, enabling the scoring network to effectively incorporate the PICG information. We develop our model on a public dataset and evaluate it in a real-world challenging in-house dataset. Experimental results demonstrate that our approach improves the performance of current scoring networks.

[Arxiv](https://arxiv.org/abs/2405.08786)