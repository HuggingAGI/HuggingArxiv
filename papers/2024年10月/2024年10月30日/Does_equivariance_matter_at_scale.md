# 等变性能在规模上重要吗？

发布时间：2024年10月30日

`其他` `大数据` `神经架构`

> Does equivariance matter at scale?

# 摘要

> 摘要：给定大数据集和足够的计算资源，为每个问题的结构和对称性设计神经架构是否有益？还是从数据中学习它们更有效？我们通过经验研究等变和非等变网络如何随计算和训练样本进行扩展。聚焦于刚体相互作用的基准问题和通用的变压器架构，我们进行了一系列实验，改变模型大小、训练步骤和数据集大小。我们找到了三个结论的证据。首先，等变性提高了数据效率，但使用数据增强训练非等变模型在足够的周期内可以缩小这一差距。其次，随着计算的扩展遵循幂律，在每个测试的计算预算下，等变模型的表现优于非等变模型。最后，等变和非等变模型在计算预算到模型大小和训练持续时间的最优分配上有所不同。

> 
Abstract:Given large data sets and sufficient compute, is it beneficial to design neural architectures for the structure and symmetries of each problem? Or is it more efficient to learn them from data? We study empirically how equivariant and non-equivariant networks scale with compute and training samples. Focusing on a benchmark problem of rigid-body interactions and on general-purpose transformer architectures, we perform a series of experiments, varying the model size, training steps, and dataset size. We find evidence for three conclusions. First, equivariance improves data efficiency, but training non-equivariant models with data augmentation can close this gap given sufficient epochs. Second, scaling with compute follows a power law, with equivariant models outperforming non-equivariant ones at each tested compute budget. Finally, the optimal allocation of a compute budget onto model size and training duration differs between equivariant and non-equivariant models.
    

[Arxiv](https://arxiv.org/pdf/2410.23179)