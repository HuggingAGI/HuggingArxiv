# LaVin-DiT: 大型视觉扩散Transformer

发布时间：2024年11月18日

`其他` `计算机视觉` `人工智能`

> LaVin-DiT: Large Vision Diffusion Transformer

# 摘要

> 这篇论文呈现了大型视觉扩散Transformer（LaVin-DiT），这一可扩展且统一的基础模型旨在生成框架下应对超20个计算机视觉任务。现有的大型视觉模型直接从自然语言处理架构改编而来，依赖低效的自回归技术，还破坏了视觉数据所必需的空间关系，而LaVin-DiT引入关键创新以优化视觉任务的生成表现。其一，为应对视觉数据的高维度，融入了时空变分自编码器，将数据编码至连续的潜在空间。其二，针对生成建模，研发了联合扩散Transformer，逐步产出视觉输出。其三，就统一的多任务训练而言，实施了上下文学习。输入-目标对充当任务上下文，引导扩散Transformer在潜在空间中使输出与特定任务对齐。在推理时，特定任务的上下文集和作为查询的测试数据让LaVin-DiT无需微调就能跨任务泛化。在众多视觉数据集上训练，模型参数从0.1B拓展至3.4B，在各类视觉任务中彰显出显著的可扩展性和顶尖性能。此工作为大型视觉基础模型开辟了新路径，突显了扩散Transformer的广阔潜力。代码和模型将会开源。

> This paper presents the Large Vision Diffusion Transformer (LaVin-DiT), a scalable and unified foundation model designed to tackle over 20 computer vision tasks in a generative framework. Unlike existing large vision models directly adapted from natural language processing architectures, which rely on less efficient autoregressive techniques and disrupt spatial relationships essential for vision data, LaVin-DiT introduces key innovations to optimize generative performance for vision tasks. First, to address the high dimensionality of visual data, we incorporate a spatial-temporal variational autoencoder that encodes data into a continuous latent space. Second, for generative modeling, we develop a joint diffusion transformer that progressively produces vision outputs. Third, for unified multi-task training, in-context learning is implemented. Input-target pairs serve as task context, which guides the diffusion transformer to align outputs with specific tasks within the latent space. During inference, a task-specific context set and test data as queries allow LaVin-DiT to generalize across tasks without fine-tuning. Trained on extensive vision datasets, the model is scaled from 0.1B to 3.4B parameters, demonstrating substantial scalability and state-of-the-art performance across diverse vision tasks. This work introduces a novel pathway for large vision foundation models, underscoring the promising potential of diffusion transformers. The code and models will be open-sourced.

[Arxiv](https://arxiv.org/abs/2411.11505)