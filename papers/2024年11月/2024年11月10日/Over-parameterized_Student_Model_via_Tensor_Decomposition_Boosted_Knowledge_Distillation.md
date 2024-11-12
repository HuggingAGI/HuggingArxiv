# 通过张量分解的过度参数化学生模型促进知识蒸馏

发布时间：2024年11月10日

`LLM应用` `计算机视觉`

> Over-parameterized Student Model via Tensor Decomposition Boosted Knowledge Distillation

# 摘要

> 增加的训练参数使大型预训练模型能够在各种下游任务中表现出色。然而，与这些模型相关的大量计算需求阻碍了它们在社区内的广泛采用。我们专注于知识蒸馏（KD），在其中训练一个紧凑的学生模型来模仿一个更大的教师模型，促进大型模型的知识转移。与之前的许多工作不同，我们在训练期间扩大学生模型的参数，以受益于过度参数化而不增加推理延迟。特别是，我们提出了一种张量分解策略，通过将其参数矩阵有效地、几乎无损地分解为更高维的张量，有效地对相对较小的学生模型进行过度参数化。为了确保效率，我们进一步引入了张量约束损失，以使学生模型和教师模型之间的高维张量对齐。综合实验验证了我们的方法在各种 KD 任务（涵盖计算机视觉和自然语言处理领域）中的显著性能提升。我们的代码可在 https://github.com/intell-sci-comput/OPDF 获得。

> Increased training parameters have enabled large pre-trained models to excel in various downstream tasks. Nevertheless, the extensive computational requirements associated with these models hinder their widespread adoption within the community. We focus on Knowledge Distillation (KD), where a compact student model is trained to mimic a larger teacher model, facilitating the transfer of knowledge of large models. In contrast to much of the previous work, we scale up the parameters of the student model during training, to benefit from overparameterization without increasing the inference latency. In particular, we propose a tensor decomposition strategy that effectively over-parameterizes the relatively small student model through an efficient and nearly lossless decomposition of its parameter matrices into higher-dimensional tensors. To ensure efficiency, we further introduce a tensor constraint loss to align the high-dimensional tensors between the student and teacher models. Comprehensive experiments validate the significant performance enhancement by our approach in various KD tasks, covering computer vision and natural language processing areas. Our code is available at https://github.com/intell-sci-comput/OPDF.

[Arxiv](https://arxiv.org/abs/2411.06448)