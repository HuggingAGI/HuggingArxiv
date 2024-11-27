# 朝着视频扩散 Transformer 的精确缩放规律进发

发布时间：2024年11月25日

`其他` `模型训练`

> Towards Precise Scaling Laws for Video Diffusion Transformers

# 摘要

> 由于视频扩散变压器训练成本高昂，所以在给定的数据和计算预算内达到其最优性能极为关键。这就要求在大规模训练前，精准确定最佳的模型规模和训练超参数。尽管在语言模型中会运用缩放定律来预测性能，但它们在视觉生成模型中的存在及精确推导尚未被充分探究。在本文中，我们对视频扩散变压器的缩放定律进行了系统分析，并确认了其存在。而且，我们发现，与语言模型不同，视频扩散模型对学习率和批量大小这两个超参数更为敏感，而这两个超参数通常未被精确建模。针对此，我们提出了一种新的缩放定律，能够预测任何模型规模和计算预算的最优超参数。在这些最优设置下，在 1e10 TFlops 的计算预算内，相较于传统缩放方法，我们实现了相当的性能，并将推理成本降低了 40.1%。此外，我们还在验证损失、任何模型规模和计算预算之间建立了更通用、更精确的关系。这使得能够对非最优模型规模进行性能预测，这在实际推理成本约束下或许也颇具吸引力，达成了更优的权衡。

> Achieving optimal performance of video diffusion transformers within given data and compute budget is crucial due to their high training costs. This necessitates precisely determining the optimal model size and training hyperparameters before large-scale training. While scaling laws are employed in language models to predict performance, their existence and accurate derivation in visual generation models remain underexplored. In this paper, we systematically analyze scaling laws for video diffusion transformers and confirm their presence. Moreover, we discover that, unlike language models, video diffusion models are more sensitive to learning rate and batch size, two hyperparameters often not precisely modeled. To address this, we propose a new scaling law that predicts optimal hyperparameters for any model size and compute budget. Under these optimal settings, we achieve comparable performance and reduce inference costs by 40.1% compared to conventional scaling methods, within a compute budget of 1e10 TFlops. Furthermore, we establish a more generalized and precise relationship among validation loss, any model size, and compute budget. This enables performance prediction for non-optimal model sizes, which may also be appealed under practical inference cost constraints, achieving a better trade-off.

[Arxiv](https://arxiv.org/abs/2411.17470)