# 通过博弈论正则化实现多模态融合的平衡

发布时间：2024年11月11日

`其他` `多模态学习` `信息提取`

> Multimodal Fusion Balancing Through Game-Theoretic Regularization

# 摘要

> 多模态学习能够通过揭示数据源间的关键依存关系，让信息提取的全貌得以完善。但当下的系统无法充分借助多种模态来达成最优性能。这是由于模态竞争，即各模态争抢训练资源，使得部分模态未得到充分优化。我们发现，现有的平衡方法难以训练出比简单基线（如集成模型）更出色的多模态模型。这就引发了一个疑问：怎样才能保证多模态训练中的所有模态都得到充分训练，并且从新模态的学习中持续提升性能？本文提出了多模态竞争正则化器（MCR），这是一个受互信息（MI）分解启发的新损失组件，旨在避免多模态训练中竞争带来的不良影响。我们的主要贡献在于：1）在多模态学习中引入博弈论原则，每个模态如同一个参与者，竞相最大化其对最终结果的影响，从而实现MI项的自动平衡。2）为每个MI项精确上下限，以增强跨模态的任务相关独特及共享信息的提取。3）提出用于条件MI估计的潜在空间排列，大幅提升计算效率。MCR优于此前所有的训练策略，并且是首个持续超越集成基线以改进多模态学习的方法，清晰地表明组合模态在合成及大型真实世界的数据集中都能带来显著的性能提升。

> Multimodal learning can complete the picture of information extraction by uncovering key dependencies between data sources. However, current systems fail to fully leverage multiple modalities for optimal performance. This has been attributed to modality competition, where modalities strive for training resources, leaving some underoptimized. We show that current balancing methods struggle to train multimodal models that surpass even simple baselines, such as ensembles. This raises the question: how can we ensure that all modalities in multimodal training are sufficiently trained, and that learning from new modalities consistently improves performance? This paper proposes the Multimodal Competition Regularizer (MCR), a new loss component inspired by mutual information (MI) decomposition designed to prevent the adverse effects of competition in multimodal training. Our key contributions are: 1) Introducing game-theoretic principles in multimodal learning, where each modality acts as a player competing to maximize its influence on the final outcome, enabling automatic balancing of the MI terms. 2) Refining lower and upper bounds for each MI term to enhance the extraction of task-relevant unique and shared information across modalities. 3) Suggesting latent space permutations for conditional MI estimation, significantly improving computational efficiency. MCR outperforms all previously suggested training strategies and is the first to consistently improve multimodal learning beyond the ensemble baseline, clearly demonstrating that combining modalities leads to significant performance gains on both synthetic and large real-world datasets.

[Arxiv](https://arxiv.org/abs/2411.07335)