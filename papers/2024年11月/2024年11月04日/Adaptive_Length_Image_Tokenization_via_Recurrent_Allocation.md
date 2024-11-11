# 通过循环分配的自适应长度图像标记化

发布时间：2024年11月04日

`其他` `计算机视觉` `图像压缩`

> Adaptive Length Image Tokenization via Recurrent Allocation

# 摘要

> 当前的视觉系统通常为图像分配固定长度的表示，而不管信息内容如何。这与人类智能——甚至大型语言模型——形成对比，它们根据熵、上下文和熟悉度分配不同的表示能力。受此启发，我们提出了一种为 2D 图像学习可变长度标记表示的方法。我们的编码器 - 解码器架构递归地处理 2D 图像标记，在多次递归展开的迭代中将它们提炼为 1D 潜在标记。每次迭代都细化 2D 标记，更新现有的 1D 潜在标记，并通过添加新标记自适应地增加表示能力。这使得能够将图像压缩为数量可变的标记，范围从 32 到 256。我们使用重建损失和 FID 指标验证我们的标记器，表明标记数量与图像熵、熟悉度和下游任务要求一致。在每次迭代中具有增加的表示能力的递归标记处理显示出标记专业化的迹象，揭示了对象/部分发现的潜力。

> Current vision systems typically assign fixed-length representations to images, regardless of the information content. This contrasts with human intelligence - and even large language models - which allocate varying representational capacities based on entropy, context and familiarity. Inspired by this, we propose an approach to learn variable-length token representations for 2D images. Our encoder-decoder architecture recursively processes 2D image tokens, distilling them into 1D latent tokens over multiple iterations of recurrent rollouts. Each iteration refines the 2D tokens, updates the existing 1D latent tokens, and adaptively increases representational capacity by adding new tokens. This enables compression of images into a variable number of tokens, ranging from 32 to 256. We validate our tokenizer using reconstruction loss and FID metrics, demonstrating that token count aligns with image entropy, familiarity and downstream task requirements. Recurrent token processing with increasing representational capacity in each iteration shows signs of token specialization, revealing potential for object / part discovery.

[Arxiv](https://arxiv.org/abs/2411.02393)