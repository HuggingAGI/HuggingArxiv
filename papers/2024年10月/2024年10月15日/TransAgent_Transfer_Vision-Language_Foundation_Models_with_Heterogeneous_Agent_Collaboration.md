# TransAgent：借助异构代理协作，实现视觉-语言基础模型的迁移

发布时间：2024年10月15日

`Agent` `计算机视觉` `机器学习`

> TransAgent: Transfer Vision-Language Foundation Models with Heterogeneous Agent Collaboration

# 摘要

> 视觉-语言基础模型（如 CLIP）凭借大规模图像-文本预训练，在迁移学习中展现了强大实力。然而，下游任务的数据可能与预训练数据差异巨大，使得单一模型难以泛化。为此，我们提出了 TransAgent 框架，通过整合多个专家模型的知识，有效提升 CLIP 的泛化能力。该框架无需额外推理成本，便能灵活协作 11 个异构模型，最终在 11 个视觉识别数据集上取得领先成绩。在低样本设置下，TransAgent 平均优于 CoOp 约 10%，在 EuroSAT 上更是高出 20%。

> Vision-language foundation models (such as CLIP) have recently shown their power in transfer learning, owing to large-scale image-text pre-training. However, target domain data in the downstream tasks can be highly different from the pre-training phase, which makes it hard for such a single model to generalize well. Alternatively, there exists a wide range of expert models that contain diversified vision and/or language knowledge pre-trained on different modalities, tasks, networks, and datasets. Unfortunately, these models are "isolated agents" with heterogeneous structures, and how to integrate their knowledge for generalizing CLIP-like models has not been fully explored. To bridge this gap, we propose a general and concise TransAgent framework, which transports the knowledge of the isolated agents in a unified manner, and effectively guides CLIP to generalize with multi-source knowledge distillation. With such a distinct framework, we flexibly collaborate with 11 heterogeneous agents to empower vision-language foundation models, without further cost in the inference phase. Finally, our TransAgent achieves state-of-the-art performance on 11 visual recognition datasets. Under the same low-shot setting, it outperforms the popular CoOp with around 10% on average, and 20% on EuroSAT which contains large domain shifts.

[Arxiv](https://arxiv.org/abs/2410.12183)