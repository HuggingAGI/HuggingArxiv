# 序列推荐中的扩散式对比学习：本研究探索了一种新颖的基于扩散过程的对比学习方法，旨在提升序列推荐的性能。通过模拟信息在序列数据中的传播，该方法能够更有效地捕捉用户行为模式，从而为用户提供更精准的推荐。

发布时间：2024年05月15日

`Agent

这篇论文主要探讨了在序列推荐系统中应用基于扩散过程的对比学习方法，以提高推荐系统的性能。它提出了一种新的增强技术，旨在生成语义连贯的用户序列变体，并利用上下文信息来改善序列的表示学习。这种方法可以被视为一种智能代理（Agent），因为它在推荐系统中执行特定的任务（生成增强序列），以优化系统的性能。因此，这篇论文更适合归类到Agent分类中。` `推荐系统` `用户行为分析`

> Diffusion-based Contrastive Learning for Sequential Recommendation

# 摘要

> 对比学习在缓解数据稀疏性问题和提升推荐系统性能方面展现了显著效果。现有方法多采用随机增强技术来生成原始序列的变体，旨在缩小同一用户不同变体表示之间的距离。然而，这些随机增强方法（例如掩码或替换）往往忽略了同一用户不同变体间的语义连贯性，导致语义不一致的序列却拥有相似的表示。此外，多数增强技术未能充分利用上下文信息，而这对理解序列语义至关重要。为此，我们提出了一种基于扩散过程的对比学习方法，用于序列推荐。具体而言，对于用户序列，我们首先选取特定位置，然后利用上下文信息通过引导扩散模型生成替代项目。通过反复应用此方法，我们能够为同一用户创造出语义连贯的增强视图，从而提升对比学习的效能。为了确保扩散模型与推荐模型在表示空间上的一致性，我们采用端到端训练策略，共享项目嵌入。在五个标准数据集上的大量实验结果表明，我们的方法表现卓越。

> Contrastive learning has been effectively applied to alleviate the data sparsity issue and enhance recommendation performance.The majority of existing methods employ random augmentation to generate augmented views of original sequences. The learning objective then aims to minimize the distance between representations of different views for the same user. However, these random augmentation strategies (e.g., mask or substitution) neglect the semantic consistency of different augmented views for the same user, leading to semantically inconsistent sequences with similar representations. Furthermore, most augmentation methods fail to utilize context information, which is critical for understanding sequence semantics. To address these limitations, we introduce a diffusion-based contrastive learning approach for sequential recommendation. Specifically, given a user sequence, we first select some positions and then leverage context information to guide the generation of alternative items via a guided diffusion model. By repeating this approach, we can get semantically consistent augmented views for the same user, which are used to improve the effectiveness of contrastive learning. To maintain cohesion between the representation spaces of both the diffusion model and the recommendation model, we train the entire framework in an end-to-end fashion with shared item embeddings. Extensive experiments on five benchmark datasets demonstrate the superiority of our proposed method.

[Arxiv](https://arxiv.org/abs/2405.09369)