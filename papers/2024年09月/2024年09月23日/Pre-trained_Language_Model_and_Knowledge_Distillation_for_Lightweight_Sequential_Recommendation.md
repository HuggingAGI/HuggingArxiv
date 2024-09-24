# 预训练语言模型结合知识蒸馏，助力轻量级序列推荐

发布时间：2024年09月23日

`LLM应用` `电子商务` `推荐系统`

> Pre-trained Language Model and Knowledge Distillation for Lightweight Sequential Recommendation

# 摘要

> 顺序推荐模型通过分析用户的历史行为来提供个性化推荐。虽然之前的算法利用神经网络提取用户兴趣特征，表现不俗，但由于数据集稀疏，常采用小规模网络，泛化能力有限。近期，基于大型预训练语言模型的推荐算法崭露头角，但面对推荐系统的实时需求，如何在实际场景中快速应用这些模型仍是一大挑战。为此，我们提出了一种结合预训练语言模型和知识蒸馏的顺序推荐算法。该算法通过跨领域知识转移和知识蒸馏，实现轻量级推理。具体分为两个阶段：首先，在推荐数据集上微调预训练模型，将知识迁移至推荐任务；其次，通过蒸馏将知识传递给轻量级模型。实验结果显示，该算法不仅提升了推荐准确性，还能及时响应推荐需求。

> Sequential recommendation models user interests based on historical behaviors to provide personalized recommendation. Previous sequential recommendation algorithms primarily employ neural networks to extract features of user interests, achieving good performance. However, due to the recommendation system datasets sparsity, these algorithms often employ small-scale network frameworks, resulting in weaker generalization capability. Recently, a series of sequential recommendation algorithms based on large pre-trained language models have been proposed. Nonetheless, given the real-time demands of recommendation systems, the challenge remains in applying pre-trained language models for rapid recommendations in real scenarios. To address this, we propose a sequential recommendation algorithm based on a pre-trained language model and knowledge distillation. The key of proposed algorithm is to transfer pre-trained knowledge across domains and achieve lightweight inference by knowledge distillation. The algorithm operates in two stages: in the first stage, we fine-tune the pre-trained language model on the recommendation dataset to transfer the pre-trained knowledge to the recommendation task; in the second stage, we distill the trained language model to transfer the learned knowledge to a lightweight model. Extensive experiments on multiple public recommendation datasets show that the proposed algorithm enhances recommendation accuracy and provide timely recommendation services.

[Arxiv](https://arxiv.org/abs/2409.14810)