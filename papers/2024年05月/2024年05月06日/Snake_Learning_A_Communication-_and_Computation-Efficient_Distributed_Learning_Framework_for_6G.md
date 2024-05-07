# Snake Learning，一个为第六代移动通信（6G）量身打造的分布式学习框架，以其卓越的通信和计算效率引领未来学习模式。

发布时间：2024年05月06日

`LLM应用` `6G通信` `人工智能`

> Snake Learning: A Communication- and Computation-Efficient Distributed Learning Framework for 6G

# 摘要

> 迈向 6G 的进程中，融合人工智能与尖端网络基础设施成为提升网络智能化和资源效率的重要策略。然而，诸如联邦学习与分割学习的现有分布式学习架构，在动态网络环境下面临同步要求高、通信成本高昂、计算资源消耗严重以及数据异质性等挑战，这些都限制了 6G 网络普及计算能力的发展，尤其是在模型参数和训练数据量日益增长的背景下。为有效应对这些挑战，本文提出了“Snake Learning”——一种经济高效的分布式学习框架。该框架考虑了 6G 网络中节点间计算能力的异质性和数据分布的本地化，通过在各个节点上顺序训练模型的特定层级，实现了逐层蛇形更新。这一机制大幅降低了模型训练过程中对存储、内存和通信的需求，同时在计算机视觉训练和大型语言模型微调任务中，无论是在同质还是异质数据分布下，都展现了出色的适应性和效率。

> In the evolution towards 6G, integrating Artificial Intelligence (AI) with advanced network infrastructure emerges as a pivotal strategy for enhancing network intelligence and resource utilization. Existing distributed learning frameworks like Federated Learning and Split Learning often struggle with significant challenges in dynamic network environments including high synchronization demands, costly communication overheads, severe computing resource consumption, and data heterogeneity across network nodes. These obstacles hinder the applications of ubiquitous computing capabilities of 6G networks, especially in light of the trend of escalating model parameters and training data volumes. To address these challenges effectively, this paper introduces "Snake Learning", a cost-effective distributed learning framework. Specifically, Snake Learning respects the heterogeneity of inter-node computing capability and local data distribution in 6G networks, and sequentially trains the designated part of model layers on individual nodes. This layer-by-layer serpentine update mechanism contributes to significantly reducing the requirements for storage, memory and communication during the model training phase, and demonstrates superior adaptability and efficiency for both Computer Vision (CV) training and Large Language Model (LLM) fine-tuning tasks across homogeneous and heterogeneous data distributions.

[Arxiv](https://arxiv.org/abs/2405.03372)