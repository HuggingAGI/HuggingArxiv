# 本文探讨了如何利用大型语言模型来预测知识图谱补全中的关系。

发布时间：2024年05月04日

`LLM应用` `知识图谱` `关系预测`

> Relations Prediction for Knowledge Graph Completion using Large Language Models

# 摘要

> 知识图谱作为一种结构化表示事实的工具，已被广泛应用于多个领域。然而，由于其广泛的应用范围，知识图谱常常面临信息不全的挑战。关系预测任务旨在通过为节点对分配可能的关系来补全知识图谱。本研究中，我们通过知识图谱的节点名称来优化大型语言模型，以提升关系预测的性能。我们的方法仅依赖于节点名称，使得模型能够在归纳场景下有效运作。实验结果显示，我们的方法在一项广泛认可的知识图谱基准测试中刷新了记录。

> Knowledge Graphs have been widely used to represent facts in a structured format. Due to their large scale applications, knowledge graphs suffer from being incomplete. The relation prediction task obtains knowledge graph completion by assigning one or more possible relations to each pair of nodes. In this work, we make use of the knowledge graph node names to fine-tune a large language model for the relation prediction task. By utilizing the node names only we enable our model to operate sufficiently in the inductive settings. Our experiments show that we accomplish new scores on a widely used knowledge graph benchmark.

[Arxiv](https://arxiv.org/abs/2405.02738)