# FLARE：结合语言模型与协作架构，提升推荐系统性能

发布时间：2024年09月18日

`LLM应用` `电子商务` `推荐系统`

> FLARE: Fusing Language Models and Collaborative Architectures for Recommender Enhancement

# 摘要

> 混合推荐系统结合物品ID和文本描述，有望提升准确性。然而，以往研究多聚焦于小规模数据集和简单模型。本文推出Flare，一种创新混合推荐系统，融合语言模型mT5与协同过滤模型Bert4Rec，通过Perceiver网络实现。Flare能有效整合协同与内容信息，提升推荐质量。我们分两阶段评估Flare：首先在小型数据集上，Flare表现出色；接着在大型现实数据集上，引入新基线。此外，Flare支持用户反馈，通过批评机制优化推荐。我们还利用批评评估模型语言理解及推荐任务适应性。

> Hybrid recommender systems, combining item IDs and textual descriptions, offer potential for improved accuracy. However, previous work has largely focused on smaller datasets and model architectures. This paper introduces Flare (Fusing Language models and collaborative Architectures for Recommender Enhancement), a novel hybrid recommender that integrates a language model (mT5) with a collaborative filtering model (Bert4Rec) using a Perceiver network. This architecture allows Flare to effectively combine collaborative and content information for enhanced recommendations.
  We conduct a two-stage evaluation, first assessing Flare's performance against established baselines on smaller datasets, where it demonstrates competitive accuracy. Subsequently, we evaluate Flare on a larger, more realistic dataset with a significantly larger item vocabulary, introducing new baselines for this setting. Finally, we showcase Flare's inherent ability to support critiquing, enabling users to provide feedback and refine recommendations. We further leverage critiquing as an evaluation method to assess the model's language understanding and its transferability to the recommendation task.

[Arxiv](https://arxiv.org/abs/2409.11699)