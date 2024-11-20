# 借助自集成提升视觉推理的泛化能力

发布时间：2024年11月01日

`LLM应用`

> Improving Generalization in Visual Reasoning via Self-Ensemble

# 摘要

> 视觉推理的认知能力要求整合多模态感知处理以及关于世界的常识和外部知识。近些年来，众多大型视觉语言模型（LVLMs）纷纷涌现，在不同领域和任务的常识推理方面展现出强大的实力和高超的熟练度。不过，训练这类 LVLMs 耗费大量昂贵的资源。近期的方法不再于各类大型数据集上从零开始训练 LVLMs，而是着重探索如何利用众多不同 LVLMs 的能力，比如集成方法。在本研究中，我们提出了自集成这一全新方法，无需更新任何参数就能提升模型的泛化和视觉推理能力，是一种无需训练的方法。我们的关键发现是，意识到 LVLM 自身就能集成，无需其他 LVLMs，这有助于释放其内在能力。在各种基准测试中的大量实验表明，我们的方法在 SketchyVQA、Outside Knowledge VQA 和分布外 VQA 任务上达到了最先进（SOTA）的性能，成效显著。

> The cognitive faculty of visual reasoning necessitates the integration of multimodal perceptual processing and commonsense and external knowledge of the world. In recent years, a plethora of large vision-language models (LVLMs) have been proposed, demonstrating outstanding power and exceptional proficiency in commonsense reasoning across diverse domains and tasks. Nevertheless, training such LVLMs requires a lot of costly resources. Recent approaches, instead of training LVLMs from scratch on various large datasets, focus on exploring ways to take advantage of the capabilities of many different LVLMs, such as ensemble methods. In this work, we propose self-ensemble, a novel method that improves the generalization and visual reasoning of the model without updating any parameters, a training-free method. Our key insight is that we realized that LVLM itself can ensemble without the need for any other LVLMs, which helps to unlock their internal capabilities. Extensive experiments on various benchmarks demonstrate the effectiveness of our method in achieving state-of-the-art (SOTA) performance on SketchyVQA, Outside Knowledge VQA, and out-of-distribution VQA tasks.

[Arxiv](https://arxiv.org/abs/2410.20883)