# 个性化以实现泛化：通过个性化实现通用的医学多模态泛化

发布时间：2024年11月12日

`其他` `医学成像`

> Personalize to generalize: Towards a universal medical multi-modality generalization through personalization

# 摘要

> 医学成像模式之间的差异，由不同的基本原理驱动，对多模态医学任务中的泛化构成了重大挑战。除了模态差距之外，个体差异，如器官大小和代谢率的差异，进一步阻碍了模型在模态和不同人群中有效泛化的能力。尽管个性化很重要，但现有的多模态泛化方法往往忽略个体差异，只关注共同的解剖特征。这种限制可能导致在各种医学任务中的泛化能力减弱。在本文中，我们揭示个性化对于多模态泛化至关重要。具体而言，我们提出了一种通过利用个体层面的约束和可学习的生物学先验来近似跨各种模态的潜在个性化不变表示${X}_h$以实现个性化泛化的方法。我们验证了学习个性化${X}_h$的可行性和益处，表明这种表示在各种多模态医学任务中具有高度的泛化性和可转移性。大量的实验结果一致表明，额外纳入的个性化显著提高了不同场景下的性能和泛化能力，证实了其有效性。

> The differences among medical imaging modalities, driven by distinct underlying principles, pose significant challenges for generalization in multi-modal medical tasks. Beyond modality gaps, individual variations, such as differences in organ size and metabolic rate, further impede a model's ability to generalize effectively across both modalities and diverse populations. Despite the importance of personalization, existing approaches to multi-modal generalization often neglect individual differences, focusing solely on common anatomical features. This limitation may result in weakened generalization in various medical tasks. In this paper, we unveil that personalization is critical for multi-modal generalization. Specifically, we propose an approach to achieve personalized generalization through approximating the underlying personalized invariant representation ${X}_h$ across various modalities by leveraging individual-level constraints and a learnable biological prior. We validate the feasibility and benefits of learning a personalized ${X}_h$, showing that this representation is highly generalizable and transferable across various multi-modal medical tasks. Extensive experimental results consistently show that the additionally incorporated personalization significantly improves performance and generalization across diverse scenarios, confirming its effectiveness.

[Arxiv](https://arxiv.org/abs/2411.06106)