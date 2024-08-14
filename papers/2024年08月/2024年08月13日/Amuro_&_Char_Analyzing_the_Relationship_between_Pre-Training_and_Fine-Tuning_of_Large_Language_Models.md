# Amuro & Char: 探讨大型语言模型预训练与微调的关联

发布时间：2024年08月13日

`LLM理论` `人工智能` `机器学习`

> Amuro & Char: Analyzing the Relationship between Pre-Training and Fine-Tuning of Large Language Models

# 摘要

> 随着大型语言模型的发展，预训练-对齐范式应运而生，即先在大规模文本上预训练模型，再通过调整使其符合人类偏好或适应特定任务。我们通过微调多个预训练阶段的模型，深入探究了预训练与微调的关联。研究涵盖18个数据集，结果显示：持续预训练虽潜移默化地提升模型，但效果在微调后才显著；额外微调使原本表现平平的数据集进步显著，超越了预训练时的佼佼者；监督微调虽大幅提升模型性能，却可能导致遗忘先前掌握的领域知识及未涉及的任务；微调后的模型对评估提示异常敏感，但这一问题可通过深化预训练得以缓解。

> The development of large language models leads to the formation of a pre-train-then-align paradigm, in which the model is typically pre-trained on a large text corpus and undergoes a tuning stage to align the model with human preference or downstream tasks. In this work, we investigate the relationship between pre-training and fine-tuning by fine-tuning multiple intermediate pre-trained model checkpoints. Our results on 18 datasets suggest that i) continual pre-training improves the model in a latent way that unveils after fine-tuning; ii) with extra fine-tuning, the datasets that the model does not demonstrate capability gain much more than those that the model performs well during the pre-training stage; iii) although model benefits significantly through supervised fine-tuning, it may forget previously known domain knowledge and the tasks that are not seen during fine-tuning; iv) the model resembles high sensitivity to evaluation prompts after supervised fine-tuning, but this sensitivity can be alleviated by more pre-training.

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/teaser.jpeg)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x1.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x2.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x3.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x4.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x5.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x6.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x7.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x8.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x9.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x10.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x11.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x12.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x13.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x14.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x15.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x16.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x17.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x18.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x19.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x20.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x21.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x22.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x23.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x24.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x25.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x26.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x27.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x28.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x29.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x30.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x31.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x32.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x33.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x34.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x35.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x36.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x37.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x38.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x39.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x40.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x41.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x6.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x42.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x43.png)

![Amuro & Char: 探讨大型语言模型预训练与微调的关联](../../../paper_images/2408.06663/x44.png)

[Arxiv](https://arxiv.org/abs/2408.06663)