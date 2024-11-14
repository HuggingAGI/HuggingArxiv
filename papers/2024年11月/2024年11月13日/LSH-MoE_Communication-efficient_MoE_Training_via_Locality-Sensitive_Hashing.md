# LSH-MoE：通过局部敏感哈希实现通信高效的 MoE 训练

发布时间：2024年11月13日

`LLM应用` `人工智能` `模型训练`

> LSH-MoE: Communication-efficient MoE Training via Locality-Sensitive Hashing

# 摘要

> 更大的 Transformer 模型在各种任务上总是表现更好，但扩大模型规模需要更多成本。为了有效地扩大模型，混合专家（MoE）架构被广泛采用，它由一个门网络和一系列专家组成，通过将输入数据路由到固定数量的专家而不是全部专家来保持训练成本不变。在现有的大规模 MoE 训练系统中，专家会分布在不同的 GPU 中以实现并行化，因此输入数据需要额外的全对全通信来访问目标专家并进行相应的计算。然而，在评估常用 GPU 集群上三个主流 MoE 模型的训练过程时，我们发现全对全通信比例平均约为 45%，这显著阻碍了训练 MoE 模型的效率和可扩展性。

在本文中，我们提出了 LSH-MoE，这是一种使用局部敏感哈希（LSH）的通信高效的 MoE 训练框架。我们首先提出了现有系统中扩展 MoE 训练的问题，并强调了利用令牌相似性促进数据压缩的潜力。然后，我们引入了一种高效的基于 LSH 的压缩技术，它利用交叉多面体哈希进行快速聚类，并实现了基于残差的误差补偿方案以减轻压缩的不利影响。为了验证我们方法的有效性，我们在语言模型（例如 RoBERTa、GPT 和 T5）和视觉模型（例如 Swin）上进行了预训练和微调任务的实验。结果表明，我们的方法在不同任务上的速度比同类方法快 1.28 倍至 2.2 倍，表现出色。

> Larger transformer models always perform better on various tasks but require more costs to scale up the model size. To efficiently enlarge models, the mixture-of-experts (MoE) architecture is widely adopted, which consists of a gate network and a series of experts and keep the training cost constant by routing the input data to a fixed number of experts instead of all. In existing large-scale MoE training systems, experts would be distributed among different GPUs for parallelization, and thus input data requires additional all-to-all communications to access the target experts and conduct corresponding computations. However, upon evaluating the training process of three mainstream MoE models on commonly used GPU clusters, we found that the all-to-all communication ratio averaged around 45%, which significantly hinders the efficiency and scalability of training MoE models.
  In this paper, we propose LSH-MoE, a communication-efficient MoE training framework using locality-sensitive hashing (LSH). We first present the problems of scaling MoE training in existing systems and highlight the potential of exploiting token similarity to facilitate data compression. Then, we introduce an efficient LSH-based compression technique, which utilizes the cross-polytope hashing for rapid clustering and implements a residual-based error compensation scheme to alleviate the adverse impact of compression. To verify the effectiveness of our methods, we conduct experiments on both language models (e.g., RoBERTa, GPT, and T5) and vision models (e.g., Swin) for pre-training and fine-tuning tasks. The results demonstrate that our method substantially outperforms its counterparts across different tasks by 1.28x - 2.2x of speedup.

[Arxiv](https://arxiv.org/abs/2411.08446)