# 借助 ChatGPT 和数据集增强，提升 SLM 性能

发布时间：2024年09月19日

`LLM应用` `人工智能`

> Enhancing SLM via ChatGPT and Dataset Augmentation

# 摘要

> 本文通过 ChatGPT-3.5-Turbo 在 NLI 领域，探讨了战略性数据集增强对小型语言模型的提升。我们采用知识蒸馏和合成数据增强技术，旨在在不增加人工标注成本的情况下，缩小 LLM 和 SLM 的性能差距。我们通过信息提取和有根据的推理两种方式，丰富了 ANLI 数据集。随后，我们在增强数据集上微调 T5-Small，并对比基准测试。结果显示，合成推理显著提升了模型对自然语言的理解能力，分别在 ANLI 数据集上提高了 1.3% 和 2.3% 的分类准确率，证明了 LLM 在数据集增强中的潜力。这种方法不仅提升了小型模型在复杂任务上的表现，还提供了一种经济高效的微调策略。通过深化对知识蒸馏和微调策略的理解，本文为构建更强大和高效的自然语言处理系统贡献了力量。

> This paper explores the enhancement of small language models through strategic dataset augmentation via ChatGPT-3.5-Turbo, in the domain of Natural Language Inference (NLI). By employing knowledge distillation-based techniques and synthetic dataset augmentation, we aim to bridge the performance gap between large language models (LLMs) and small language models (SLMs) without the immense cost of human annotation. Our methods involve two forms of rationale generation--information extraction and informed reasoning--to enrich the ANLI dataset. We then fine-tune T5-Small on these augmented datasets, evaluating its performance against an established benchmark. Our findings reveal that the incorporation of synthetic rationales significantly improves the model's ability to comprehend natural language, leading to 1.3\% and 2.3\% higher classification accuracy, respectively, on the ANLI dataset, demonstrating the potential of leveraging LLMs for dataset augmentation. This approach not only enhances the performance of smaller models on complex tasks but also introduces a cost-effective method for fine-tuning smaller language models. By advancing our understanding of knowledge distillation and fine-tuning strategies, this work contributes to the ongoing effort to create more capable and efficient NLP systems.

[Arxiv](https://arxiv.org/abs/2409.12599)