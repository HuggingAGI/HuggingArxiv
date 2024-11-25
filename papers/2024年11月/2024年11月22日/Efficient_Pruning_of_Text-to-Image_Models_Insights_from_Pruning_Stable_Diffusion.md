# 高效修剪文本到图像的模型：从修剪稳定扩散中获得的启示

发布时间：2024年11月22日

`其他` `图像生成` `模型压缩`

> Efficient Pruning of Text-to-Image Models: Insights from Pruning Stable Diffusion

# 摘要

> 随着文本转图像模型愈发强大和复杂，其规模的迅速扩张给广泛应用造成了重大阻碍，尤其是在资源受限的设备上。本文针对 Stable Diffusion 2 的训练后剪枝展开了开创性研究，以解决文本转图像领域对模型压缩的迫切需求。我们的研究探索了此前未曾涉足的多模态生成模型的剪枝技术，尤其分别考察了剪枝对文本部分和图像生成部分的影响。我们对模型或模型的单个部分在各种稀疏程度下的剪枝情况进行了全面对比。我们的成果带来了前所未有的发现。比如，与语言模型剪枝的常规趋势不同，我们发现在文本转图像的情境中，简单的幅度剪枝要优于更先进的技术。另外，我们的结果表明，Stable Diffusion 2 能够剪枝至 38.5%的稀疏度，且质量损失极小，大幅减小了模型规模。我们提出了一种最优剪枝配置，将文本编码器剪枝至 47.5%，将扩散生成器剪枝至 35%。这种配置在维持图像生成质量的同时，显著降低了计算需求。此外，我们的工作揭示了有关文本转图像模型中信息编码的有趣问题：我们观察到，超过某些阈值的剪枝会导致性能陡然下降（生成无法读取的图像），这表明特定的权重编码了关键的语义信息。这一发现为文本转图像模型中的模型压缩、互操作性和偏差识别等未来研究开辟了新的方向。通过为文本转图像模型的剪枝行为提供关键见解，我们的研究为开发更高效、更易获取的人工智能驱动的图像生成系统奠定了基础。

> As text-to-image models grow increasingly powerful and complex, their burgeoning size presents a significant obstacle to widespread adoption, especially on resource-constrained devices. This paper presents a pioneering study on post-training pruning of Stable Diffusion 2, addressing the critical need for model compression in text-to-image domain. Our study tackles the pruning techniques for the previously unexplored multi-modal generation models, and particularly examines the pruning impact on the textual component and the image generation component separately. We conduct a comprehensive comparison on pruning the model or the single component of the model in various sparsities. Our results yield previously undocumented findings. For example, contrary to established trends in language model pruning, we discover that simple magnitude pruning outperforms more advanced techniques in text-to-image context. Furthermore, our results show that Stable Diffusion 2 can be pruned to 38.5% sparsity with minimal quality loss, achieving a significant reduction in model size. We propose an optimal pruning configuration that prunes the text encoder to 47.5% and the diffusion generator to 35%. This configuration maintains image generation quality while substantially reducing computational requirements. In addition, our work uncovers intriguing questions about information encoding in text-to-image models: we observe that pruning beyond certain thresholds leads to sudden performance drops (unreadable images), suggesting that specific weights encode critical semantics information. This finding opens new avenues for future research in model compression, interoperability, and bias identification in text-to-image models. By providing crucial insights into the pruning behavior of text-to-image models, our study lays the groundwork for developing more efficient and accessible AI-driven image generation systems

[Arxiv](https://arxiv.org/abs/2411.15113)