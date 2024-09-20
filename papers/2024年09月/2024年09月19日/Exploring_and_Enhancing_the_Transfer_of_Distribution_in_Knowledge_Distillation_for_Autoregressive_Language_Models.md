# 探索并提升自回归语言模型在知识蒸馏中分布转移的传递效果

发布时间：2024年09月19日

`LLM理论` `人工智能` `机器学习`

> Exploring and Enhancing the Transfer of Distribution in Knowledge Distillation for Autoregressive Language Models

# 摘要

> 知识蒸馏 (KD) 通过训练小模型模仿大模型，在自回归语言模型中，KD 的成功主要依赖于反向 KL 和学生生成的输出 (SGO)。然而，反向 KL 虽能模仿部分特征，却无法捕捉大部分行为；SGO 则计算成本高且优化困难。为此，我们提出了在线知识蒸馏 (OKD)，教师网络集成小模块与学生模型同步训练，无需策略采样，仅需少量参数更新，动态适应学生分布，提升蒸馏效果。实验表明，OKD 在多种模型架构和大小上均表现优异，训练时间最多缩短四倍。

> Knowledge distillation (KD) is a technique that compresses large teacher models by training smaller student models to mimic them. The success of KD in auto-regressive language models mainly relies on Reverse KL for mode-seeking and student-generated output (SGO) to combat exposure bias. Our theoretical analyses and experimental validation reveal that while Reverse KL effectively mimics certain features of the teacher distribution, it fails to capture most of its behaviors. Conversely, SGO incurs higher computational costs and presents challenges in optimization, particularly when the student model is significantly smaller than the teacher model. These constraints are primarily due to the immutable distribution of the teacher model, which fails to adjust adaptively to models of varying sizes. We introduce Online Knowledge Distillation (OKD), where the teacher network integrates small online modules to concurrently train with the student model. This strategy abolishes the necessity for on-policy sampling and merely requires minimal updates to the parameters of the teacher's online module during training, thereby allowing dynamic adaptation to the student's distribution to make distillation better. Extensive results across multiple generation datasets show that OKD achieves or exceeds the performance of leading methods in various model architectures and sizes, reducing training time by up to fourfold.

[Arxiv](https://arxiv.org/abs/2409.12512)