# 为冷启动内容推荐而设计的通用物品表示学习

发布时间：2024年04月21日

`分类：RAG` `推荐系统` `机器学习`

> General Item Representation Learning for Cold-start Content Recommendations

# 摘要

> 冷启动商品推荐一直是推荐领域的难题。传统上，人们倾向于采用基于内容的方法，但往往未能充分利用原始内容中的丰富信息。本文提出了一种新颖的领域无关的商品表示学习框架，旨在解决冷启动推荐问题。该框架采用基于 Transformer 的架构，实现了不同特征之间的自然多模态对齐。我们设计的模型无需依赖分类标签即可端到端训练，避免了收集标签的高昂成本，同时优化了推荐场景下的表示学习。通过在电影和新闻推荐的真实世界数据集上的广泛测试，我们证实了该方法在捕捉用户细微偏好方面超越了现有的最先进方法，并且具有跨领域的广泛适用性。

> Cold-start item recommendation is a long-standing challenge in recommendation systems. A common remedy is to use a content-based approach, but rich information from raw contents in various forms has not been fully utilized. In this paper, we propose a domain/data-agnostic item representation learning framework for cold-start recommendations, naturally equipped with multimodal alignment among various features by adopting a Transformer-based architecture. Our proposed model is end-to-end trainable completely free from classification labels, not just costly to collect but suboptimal for recommendation-purpose representation learning. From extensive experiments on real-world movie and news recommendation benchmarks, we verify that our approach better preserves fine-grained user taste than state-of-the-art baselines, universally applicable to multiple domains at large scale.

![为冷启动内容推荐而设计的通用物品表示学习](../../../paper_images/2404.13808/x1.png)

![为冷启动内容推荐而设计的通用物品表示学习](../../../paper_images/2404.13808/x2.png)

![为冷启动内容推荐而设计的通用物品表示学习](../../../paper_images/2404.13808/x3.png)

![为冷启动内容推荐而设计的通用物品表示学习](../../../paper_images/2404.13808/x4.png)

![为冷启动内容推荐而设计的通用物品表示学习](../../../paper_images/2404.13808/x5.png)

[Arxiv](https://arxiv.org/abs/2404.13808)