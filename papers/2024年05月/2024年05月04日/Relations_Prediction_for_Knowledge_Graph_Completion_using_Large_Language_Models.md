# 本文探讨了利用大型语言模型来预测知识图谱补全中的关系。

发布时间：2024年05月04日

`分类：LLM应用

这篇论文讨论了如何通过优化大型语言模型来提升知识图谱中的关系预测性能。这属于LLM应用的范畴，因为它探讨了如何将大型语言模型应用于特定的任务（关系预测），并展示了实验结果和性能提升。` `知识图谱` `关系预测`

> Relations Prediction for Knowledge Graph Completion using Large Language Models

# 摘要

> 知识图谱作为一种结构化呈现事实的工具，已被广泛应用于多个领域。然而，大规模应用的知识图谱常因信息不全而受限。关系预测任务旨在通过为节点对分配可能的关系来补全知识图谱。本研究中，我们通过知识图谱的节点名称来优化一个大型语言模型，以提升关系预测的性能。这种方法使我们的模型在归纳学习场景下表现出色。实验结果揭示了我们的模型在一项知名知识图谱基准测试中刷新了得分记录。

> Knowledge Graphs have been widely used to represent facts in a structured format. Due to their large scale applications, knowledge graphs suffer from being incomplete. The relation prediction task obtains knowledge graph completion by assigning one or more possible relations to each pair of nodes. In this work, we make use of the knowledge graph node names to fine-tune a large language model for the relation prediction task. By utilizing the node names only we enable our model to operate sufficiently in the inductive settings. Our experiments show that we accomplish new scores on a widely used knowledge graph benchmark.

[Arxiv](https://arxiv.org/abs/2405.02738)