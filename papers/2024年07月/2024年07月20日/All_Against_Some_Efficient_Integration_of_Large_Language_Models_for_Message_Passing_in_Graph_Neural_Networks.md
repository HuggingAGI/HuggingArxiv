# 全面对抗部分：优化图神经网络中消息传递的大型语言模型集成

发布时间：2024年07月20日

`LLM应用` `人工智能` `图数据处理`

> All Against Some: Efficient Integration of Large Language Models for Message Passing in Graph Neural Networks

# 摘要

> 图神经网络 (GNNs) 因其处理图结构数据的广泛应用而备受瞩目。同时，大型语言模型 (LLMs) 凭借其深厚的预训练知识和强大的语义理解能力，在视觉和文本数据应用中展现出卓越潜力。本文探讨了如何高效利用 LLMs 处理图结构数据，这一领域在 LLM 研究中尚属空白。我们提出的 E-LLaGNN 框架，通过有选择地增强部分节点，优化了图学习的消息传递过程。具体而言，E-LLaGNN 通过 LLMs 精选高质量邻域，并结合多样化提示进行特征增强，最终利用传统 GNN 架构完成信息聚合。我们还设计了多种策略，以减少 LLMs 在处理大规模节点时的计算和内存负担。实验表明，E-LLaGNN 在多个图数据集上表现优异，不仅优化了深度 GNNs 的梯度流动，还实现了无需 LLM 的推理能力。

> Graph Neural Networks (GNNs) have attracted immense attention in the past decade due to their numerous real-world applications built around graph-structured data. On the other hand, Large Language Models (LLMs) with extensive pretrained knowledge and powerful semantic comprehension abilities have recently shown a remarkable ability to benefit applications using vision and text data. In this paper, we investigate how LLMs can be leveraged in a computationally efficient fashion to benefit rich graph-structured data, a modality relatively unexplored in LLM literature. Prior works in this area exploit LLMs to augment every node features in an ad-hoc fashion (not scalable for large graphs), use natural language to describe the complex structural information of graphs, or perform computationally expensive finetuning of LLMs in conjunction with GNNs. We propose E-LLaGNN (Efficient LLMs augmented GNNs), a framework with an on-demand LLM service that enriches message passing procedure of graph learning by enhancing a limited fraction of nodes from the graph. More specifically, E-LLaGNN relies on sampling high-quality neighborhoods using LLMs, followed by on-demand neighborhood feature enhancement using diverse prompts from our prompt catalog, and finally information aggregation using message passing from conventional GNN architectures. We explore several heuristics-based active node selection strategies to limit the computational and memory footprint of LLMs when handling millions of nodes. Through extensive experiments & ablation on popular graph benchmarks of varying scales (Cora, PubMed, ArXiv, & Products), we illustrate the effectiveness of our E-LLaGNN framework and reveal many interesting capabilities such as improved gradient flow in deep GNNs, LLM-free inference ability etc.

![全面对抗部分：优化图神经网络中消息传递的大型语言模型集成](../../../paper_images/2407.14996/x1.png)

![全面对抗部分：优化图神经网络中消息传递的大型语言模型集成](../../../paper_images/2407.14996/x2.png)

![全面对抗部分：优化图神经网络中消息传递的大型语言模型集成](../../../paper_images/2407.14996/x3.png)

![全面对抗部分：优化图神经网络中消息传递的大型语言模型集成](../../../paper_images/2407.14996/x4.png)

[Arxiv](https://arxiv.org/abs/2407.14996)