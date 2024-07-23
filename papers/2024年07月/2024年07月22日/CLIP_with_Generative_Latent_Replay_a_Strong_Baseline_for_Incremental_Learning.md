# CLIP 与生成性潜在重放结合，为增量学习提供了一个强有力的基线方法。

发布时间：2024年07月22日

`LLM应用` `人工智能` `计算机视觉`

> CLIP with Generative Latent Replay: a Strong Baseline for Incremental Learning

# 摘要

> 随着Transformer和CLIP等视觉语言模型的兴起，大型预训练模型已成为提升持续学习性能的常用手段。为此，我们开发了多种提示策略，旨在微调Transformer模型而不引发灾难性遗忘。然而，这些策略在使模型适应与预训练领域差异较大的新领域并保持零-shot能力方面仍显不足。为此，我们提出了一种创新的持续生成训练方法，通过生成重放技术使提示与任务对齐，从而在适应视觉语言模型的同时减少遗忘。此外，我们还引入了一个新指标，用于评估持续学习基准中的零-shot能力。实验证明，我们的框架不仅能有效适应新任务，还能提升零-shot能力。深入分析显示，我们的方法能有效缩小与联合提示调整的差距。相关代码已公开在https://github.com/aimagelab/mammoth。

> With the emergence of Transformers and Vision-Language Models (VLMs) such as CLIP, large pre-trained models have become a common strategy to enhance performance in Continual Learning scenarios. This led to the development of numerous prompting strategies to effectively fine-tune transformer-based models without succumbing to catastrophic forgetting. However, these methods struggle to specialize the model on domains significantly deviating from the pre-training and preserving its zero-shot capabilities. In this work, we propose Continual Generative training for Incremental prompt-Learning, a novel approach to mitigate forgetting while adapting a VLM, which exploits generative replay to align prompts to tasks. We also introduce a new metric to evaluate zero-shot capabilities within CL benchmarks. Through extensive experiments on different domains, we demonstrate the effectiveness of our framework in adapting to new tasks while improving zero-shot capabilities. Further analysis reveals that our approach can bridge the gap with joint prompt tuning. The codebase is available at https://github.com/aimagelab/mammoth.

[Arxiv](https://arxiv.org/abs/2407.15793)