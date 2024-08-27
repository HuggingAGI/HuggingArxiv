# 探究大型语言模型在异质图领域的应用潜力

发布时间：2024年08月26日

`LLM应用` `人工智能` `图神经网络`

> Exploring the Potential of Large Language Models for Heterophilic Graphs

# 摘要

> 图神经网络 (GNNs) 在基于图的学习任务中不可或缺。传统 GNN 架构基于同质性假设，即相连节点共享相似特征，但这限制了其在异质图中的应用。现有方法忽视了节点文本数据的价值，这些数据能深化对异质图的理解。借助大型语言模型 (LLMs)，我们有望通过利用 LLMs 的广泛知识，更有效地利用文本数据来增强 GNNs。本研究提出一个两阶段框架：LLM 增强的边缘判别和 LLM 引导的边缘重加权，旨在优化异质图的节点分类。实验证明，这一框架有效且可行，同时我们通过模型蒸馏技术，确保了实际应用中的高效性。

> Graph Neural Networks (GNNs) are essential for various graph-based learning tasks. Notably, classical GNN architectures operate under the assumption of homophily, which posits that connected nodes are likely to share similar features. However, this assumption limits the effectiveness of GNNs in handling heterophilic graphs where connected nodes often exhibit dissimilar characteristics. Existing approaches for homophily graphs such as non-local neighbor extension and architectural refinement overlook the rich textual data associated with nodes, which could unlock deeper insights into these heterophilic contexts. With advancements in Large Language Models (LLMs), there is significant promise to enhance GNNs by leveraging the extensive open-world knowledge within LLMs to more effectively interpret and utilize textual data for characterizing heterophilic graphs. In this work, we explore the potential of LLMs for modeling heterophilic graphs and propose a novel two-stage framework: LLM-enhanced edge discriminator and LLM-guided edge reweighting. Specifically, in the first stage, we fine-tune the LLM to better identify homophilic and heterophilic edges based on the textual information of their nodes. In the second stage, we adaptively manage message propagation in GNNs for different edge types based on node features, structures, and heterophilic or homophilic characteristics. To cope with the computational demands when deploying LLMs in practical scenarios, we further explore model distillation techniques to fine-tune smaller, more efficient models that maintain competitive performance. Extensive experiments validate the effectiveness of our framework, demonstrating the feasibility of using LLMs to enhance GNNs for node classification on heterophilic graphs.

[Arxiv](https://arxiv.org/abs/2408.14134)