# GraphLoRA：结构感知的低秩对比适应，助力跨图迁移学习

发布时间：2024年09月25日

`LLM应用` `电子商务` `社交网络`

> GraphLoRA: Structure-Aware Contrastive Low-Rank Adaptation for Cross-Graph Transfer Learning

# 摘要

> 图神经网络 (GNN) 在处理电子商务和社交网络等领域的图分析任务方面表现出色。然而，GNN 在可转移性上存在挑战，限制了其在实际应用中的广泛使用。现有研究在 GNN 迁移学习中忽视了不同图数据集间的分布差异，导致跨分布迁移时效果不佳。如何将训练好的 GNN 有效应用于特征和结构各异的新图，仍是一个待解难题。借鉴低秩适应 (LoRA) 在大模型跨领域应用中的成功经验，我们提出了 GraphLoRA，一种高效且参数精简的 GNN 迁移方法。具体而言，我们首先通过结构感知最大均值差异 (SMMD) 对齐源图与目标图的节点特征分布。同时，通过在预训练 GNN 中引入低秩适应，注入少量可训练参数，有效弥合结构差异并防止遗忘。此外，我们还设计了结构感知的正则化目标，提升 GNN 在标签稀缺目标图上的适应能力。实验证明，GraphLoRA 在仅调整 20% 参数的情况下，即可在多个真实数据集上超越现有方法，甚至在不同领域间也能表现出色。代码已公开，详见 https://anonymous.4open.science/r/GraphLoRA。

> Graph Neural Networks (GNNs) have demonstrated remarkable proficiency in handling a range of graph analytical tasks across various domains, such as e-commerce and social networks. Despite their versatility, GNNs face significant challenges in transferability, limiting their utility in real-world applications. Existing research in GNN transfer learning overlooks discrepancies in distribution among various graph datasets, facing challenges when transferring across different distributions. How to effectively adopt a well-trained GNN to new graphs with varying feature and structural distributions remains an under-explored problem. Taking inspiration from the success of Low-Rank Adaptation (LoRA) in adapting large language models to various domains, we propose GraphLoRA, an effective and parameter-efficient method for transferring well-trained GNNs to diverse graph domains. Specifically, we first propose a Structure-aware Maximum Mean Discrepancy (SMMD) to align divergent node feature distributions across source and target graphs. Moreover, we introduce low-rank adaptation by injecting a small trainable GNN alongside the pre-trained one, effectively bridging structural distribution gaps while mitigating the catastrophic forgetting. Additionally, a structure-aware regularization objective is proposed to enhance the adaptability of the pre-trained GNN to target graph with scarce supervision labels. Extensive experiments on six real-world datasets demonstrate the effectiveness of GraphLoRA against eleven baselines by tuning only 20% of parameters, even across disparate graph domains. The code is available at https://anonymous.4open.science/r/GraphLoRA.

[Arxiv](https://arxiv.org/abs/2409.16670)