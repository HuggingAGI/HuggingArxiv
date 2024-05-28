# TokenUnify：一种利用混合令牌预测进行高效自回归视觉预训练的扩展方法

发布时间：2024年05月27日

`LLM应用

这篇论文介绍了一种新的预训练方法**TokenUnify**，它结合了随机、下一及下一所有令牌预测，旨在减少视觉自回归中的累积误差。这种方法特别适用于处理图像数据，因为图像数据的非序列性使得传统的自回归下一令牌预测方法在视觉任务中效果不佳。论文中还提到了一个大规模、高分辨率的电子显微镜图像数据集，专门设计用于长序列空间相关性的研究，并展示了TokenUnify方法在神经元分割任务上的显著性能提升。此外，论文还提到了项目代码的公开，这表明了该研究的实际应用价值和开放性。因此，这篇论文属于LLM应用类别，因为它探讨了大型语言模型在视觉任务中的应用，并提出了一种新的预训练策略来优化这些任务的性能。` `神经科学` `电子显微镜`

> TokenUnify: Scalable Autoregressive Visual Pre-training with Mixture Token Prediction

# 摘要

> 自回归下一令牌预测虽为大型语言模型的标准预训练方法，但在视觉任务中因图像数据的非序列性而受限，导致误差累积。多数视觉模型依赖基于掩码自编码器（MAE）的预训练，却面临可扩展性难题。为此，我们创新性地提出了**TokenUnify**预训练方法，它巧妙融合了随机、下一及下一所有令牌预测。理论证明，TokenUnify能有效减少视觉自回归中的累积误差。结合TokenUnify，我们构建了一个包含超过1.2亿标注体素的大规模、高分辨率电子显微镜图像数据集，专为长序列空间相关性设计，成为当前最大的神经元分割数据集，并设定了实验验证的新基准。利用Mamba网络在长序列建模上的天然优势，TokenUnify不仅简化计算，更在EM神经元分割任务上实现了45%的性能飞跃，超越了MAE及传统自回归方法，成功连接了语言与视觉模型的预训练策略。项目代码已公开于\url{https://github.com/ydchen0806/TokenUnify}。

> Autoregressive next-token prediction is a standard pretraining method for large-scale language models, but its application to vision tasks is hindered by the non-sequential nature of image data, leading to cumulative errors. Most vision models employ masked autoencoder (MAE) based pretraining, which faces scalability issues. To address these challenges, we introduce \textbf{TokenUnify}, a novel pretraining method that integrates random token prediction, next-token prediction, and next-all token prediction. We provide theoretical evidence demonstrating that TokenUnify mitigates cumulative errors in visual autoregression. Cooperated with TokenUnify, we have assembled a large-scale electron microscopy (EM) image dataset with ultra-high resolution, ideal for creating spatially correlated long sequences. This dataset includes over 120 million annotated voxels, making it the largest neuron segmentation dataset to date and providing a unified benchmark for experimental validation. Leveraging the Mamba network inherently suited for long-sequence modeling on this dataset, TokenUnify not only reduces the computational complexity but also leads to a significant 45\% improvement in segmentation performance on downstream EM neuron segmentation tasks compared to existing methods. Furthermore, TokenUnify demonstrates superior scalability over MAE and traditional autoregressive methods, effectively bridging the gap between pretraining strategies for language and vision models. Code is available at \url{https://github.com/ydchen0806/TokenUnify}.

![TokenUnify：一种利用混合令牌预测进行高效自回归视觉预训练的扩展方法](../../../paper_images/2405.16847/x1.png)

![TokenUnify：一种利用混合令牌预测进行高效自回归视觉预训练的扩展方法](../../../paper_images/2405.16847/x2.png)

![TokenUnify：一种利用混合令牌预测进行高效自回归视觉预训练的扩展方法](../../../paper_images/2405.16847/x3.png)

![TokenUnify：一种利用混合令牌预测进行高效自回归视觉预训练的扩展方法](../../../paper_images/2405.16847/x4.png)

![TokenUnify：一种利用混合令牌预测进行高效自回归视觉预训练的扩展方法](../../../paper_images/2405.16847/mec.png)

![TokenUnify：一种利用混合令牌预测进行高效自回归视觉预训练的扩展方法](../../../paper_images/2405.16847/x5.png)

![TokenUnify：一种利用混合令牌预测进行高效自回归视觉预训练的扩展方法](../../../paper_images/2405.16847/x6.png)

[Arxiv](https://arxiv.org/abs/2405.16847)