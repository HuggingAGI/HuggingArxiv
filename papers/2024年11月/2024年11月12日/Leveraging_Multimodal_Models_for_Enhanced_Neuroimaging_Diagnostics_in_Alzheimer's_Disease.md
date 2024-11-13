# 利用多模态模型来增强阿尔茨海默病的神经影像学诊断

发布时间：2024年11月12日

`LLM应用` `神经影像学`

> Leveraging Multimodal Models for Enhanced Neuroimaging Diagnostics in Alzheimer's Disease

# 摘要

> 大型语言模型（LLM）和视觉语言模型（VLM）的快速发展在医疗诊断中显示出巨大潜力，特别是在放射学领域，例如 X 射线等数据集与人类生成的诊断报告相匹配。然而，在神经影像学领域存在显著的研究差距，特别是对于像阿尔茨海默病这样的病症，原因是缺乏可用于模型微调的综合诊断报告。本文通过在 OASIS-4 数据集中包含 663 名患者的结构化数据上使用 GPT-4o-mini 生成合成诊断报告来解决这一差距。使用合成报告作为训练和验证的基础事实，然后利用预训练的 BiomedCLIP 和 T5 模型直接从数据集中的图像生成神经学报告。我们提出的方法实现了 BLEU-4 分数为 0.1827，ROUGE-L 分数为 0.3719，METEOR 分数为 0.4163，显示出其在生成临床相关且准确的诊断报告方面的潜力。

> The rapid advancements in Large Language Models (LLMs) and Vision-Language Models (VLMs) have shown great potential in medical diagnostics, particularly in radiology, where datasets such as X-rays are paired with human-generated diagnostic reports. However, a significant research gap exists in the neuroimaging field, especially for conditions such as Alzheimer's disease, due to the lack of comprehensive diagnostic reports that can be utilized for model fine-tuning. This paper addresses this gap by generating synthetic diagnostic reports using GPT-4o-mini on structured data from the OASIS-4 dataset, which comprises 663 patients. Using the synthetic reports as ground truth for training and validation, we then generated neurological reports directly from the images in the dataset leveraging the pre-trained BiomedCLIP and T5 models. Our proposed method achieved a BLEU-4 score of 0.1827, ROUGE-L score of 0.3719, and METEOR score of 0.4163, revealing its potential in generating clinically relevant and accurate diagnostic reports.

[Arxiv](https://arxiv.org/abs/2411.07871)