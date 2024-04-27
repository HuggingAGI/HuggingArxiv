# 本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。

发布时间：2024年04月17日

`LLM应用` `计算机视觉`

> Exploring the Transferability of Visual Prompting for Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）虽展现出潜力，但在特定任务上的表现仍不及专业模型，亟需优化以提升其应用价值。传统微调方法需对每个模型单独训练，造成了巨大的计算和存储资源消耗。本文提出了一种创新框架，通过共享参数集针对特定下游任务进行优化，以提升各类MLLMs的性能。我们引入了“可转移视觉提示”（TVP）技术，这是一种简洁高效的解决方案，能够生成可在不同模型间转移并提升任务表现的视觉提示，且仅需在一个模型上进行训练。为解决现有方法中跨模型特征干扰的问题，我们提出了两大策略：一是“特征一致性对齐”，确保提示特征变化不破坏任务通用知识；二是“任务语义丰富化”，通过语言引导使提示图像富含更多任务特定语义。我们通过在六种先进MLLMs上进行的广泛实验验证了TVP的有效性，实验任务包括物体识别、计数、多模态推理及幻觉校正等。

> Although Multimodal Large Language Models (MLLMs) have demonstrated promising versatile capabilities, their performance is still inferior to specialized models on downstream tasks, which makes adaptation necessary to enhance their utility. However, fine-tuning methods require independent training for every model, leading to huge computation and memory overheads. In this paper, we propose a novel setting where we aim to improve the performance of diverse MLLMs with a group of shared parameters optimized for a downstream task. To achieve this, we propose Transferable Visual Prompting (TVP), a simple and effective approach to generate visual prompts that can transfer to different models and improve their performance on downstream tasks after trained on only one model. We introduce two strategies to address the issue of cross-model feature corruption of existing visual prompting methods and enhance the transferability of the learned prompts, including 1) Feature Consistency Alignment: which imposes constraints to the prompted feature changes to maintain task-agnostic knowledge; 2) Task Semantics Enrichment: which encourages the prompted images to contain richer task-specific semantics with language guidance. We validate the effectiveness of TVP through extensive experiments with 6 modern MLLMs on a wide variety of tasks ranging from object recognition and counting to multimodal reasoning and hallucination correction.

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/x1.png)

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/x2.png)

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/seed_0_lr_200_add_prompt_False_model_name_instructblip_dataset_cifar10.png)

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/seed_0_lr_200_add_prompt_True_model_name_instructblip_dataset_cifar10.png)

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/seed_0_lr_200_add_prompt_False_model_name_bliva_dataset_cifar10.png)

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/seed_0_lr_200_add_prompt_True_model_name_bliva_dataset_cifar10.png)

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/x3.png)

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/x4.png)

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/x5.png)

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/x6.png)

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/small_CLEVR_True.png)

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/small_Hatefulmemes_True.png)

![本文旨在探究视觉提示在多模态大型语言模型中的应用迁移性。](../../../paper_images/2404.11207/small_POPE_True.png)

[Arxiv](https://arxiv.org/abs/2404.11207)