# Diff-2-in-1：用扩散模型架起生成和密集感知的桥梁

发布时间：2024年11月07日

`其他` `视觉感知` `图像合成`

> Diff-2-in-1: Bridging Generation and Dense Perception with Diffusion Models

# 摘要

> 除了高保真图像合成之外，扩散模型最近在密集视觉感知任务中展现出了有前景的结果。然而，大多数现有的工作将扩散模型视为感知任务的独立组件，要么仅仅将它们用于现成的数据增强，要么仅仅作为特征提取器。与这些孤立且因此次优的努力相反，我们引入了一个统一、通用、基于扩散的框架 Diff-2-in-1，它可以通过对扩散去噪过程的独特利用，同时处理多模态数据生成和密集视觉感知。在这个框架内，我们通过利用去噪网络创建反映原始训练集分布的多模态数据，进一步通过多模态生成增强判别式视觉感知。重要的是，Diff-2-in-1 通过利用一种新颖的自我改进学习机制，优化了所创建的多样化和可靠数据的利用。全面的实验评估验证了我们框架的有效性，展示了在各种判别式骨干和以真实感和实用性为特征的高质量多模态数据生成方面的一致性能改进。

> Beyond high-fidelity image synthesis, diffusion models have recently exhibited promising results in dense visual perception tasks. However, most existing work treats diffusion models as a standalone component for perception tasks, employing them either solely for off-the-shelf data augmentation or as mere feature extractors. In contrast to these isolated and thus sub-optimal efforts, we introduce a unified, versatile, diffusion-based framework, Diff-2-in-1, that can simultaneously handle both multi-modal data generation and dense visual perception, through a unique exploitation of the diffusion-denoising process. Within this framework, we further enhance discriminative visual perception via multi-modal generation, by utilizing the denoising network to create multi-modal data that mirror the distribution of the original training set. Importantly, Diff-2-in-1 optimizes the utilization of the created diverse and faithful data by leveraging a novel self-improving learning mechanism. Comprehensive experimental evaluations validate the effectiveness of our framework, showcasing consistent performance improvements across various discriminative backbones and high-quality multi-modal data generation characterized by both realism and usefulness.

[Arxiv](https://arxiv.org/abs/2411.05005)