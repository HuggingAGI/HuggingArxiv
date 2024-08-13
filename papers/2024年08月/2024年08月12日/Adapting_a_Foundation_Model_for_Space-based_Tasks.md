# 针对太空任务调整基础模型

发布时间：2024年08月12日

`LLM应用` `太空探索` `机器人`

> Adapting a Foundation Model for Space-based Tasks

# 摘要

> 大型语言模型等基础模型具备智能特性，有望赋予机器人应对野外复杂任务的上下文理解能力。展望太空机器人的未来，我们面临三大挑战：地面操作的可扩展性、知识向新环境的迁移以及任务与数据的多模态性。为此，我们首先自动标记AI4Mars数据集，创建一个视觉问答数据集，并在此基础上微调预训练模型LLaVA，以增强模型在火星表面的空间推理与导航能力。研究表明，现有视觉-语言模型在太空应用中视觉推理能力不足，而在地球外数据上微调模型，即便训练数据有限，也能大幅提升响应质量。

> Foundation models, e.g., large language models, possess attributes of intelligence which offer promise to endow a robot with the contextual understanding necessary to navigate complex, unstructured tasks in the wild. In the future of space robotics, we see three core challenges which motivate the use of a foundation model adapted to space-based applications: 1) Scalability of ground-in-the-loop operations; 2) Generalizing prior knowledge to novel environments; and 3) Multi-modality in tasks and sensor data. Therefore, as a first-step towards building a foundation model for space-based applications, we automatically label the AI4Mars dataset to curate a language annotated dataset of visual-question-answer tuples. We fine-tune a pretrained LLaVA checkpoint on this dataset to endow a vision-language model with the ability to perform spatial reasoning and navigation on Mars' surface. In this work, we demonstrate that 1) existing vision-language models are deficient visual reasoners in space-based applications, and 2) fine-tuning a vision-language model on extraterrestrial data significantly improves the quality of responses even with a limited training dataset of only a few thousand samples.

[Arxiv](https://arxiv.org/abs/2408.05924)