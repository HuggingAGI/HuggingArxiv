# 联邦大型语言模型通过自适应重要性感知 LoRA 进行微调

发布时间：2024年11月10日

`LLM应用` `联邦学习` `新闻分类`

> Federated LLMs Fine-tuned with Adaptive Importance-Aware LoRA

# 摘要

> 对预训练的大型语言模型（LLMs）进行联邦微调能够在不同数据集上实现特定任务的适配，同时保护数据隐私。然而，模型的大尺寸和客户端资源的异质性带来了显著的计算和通信挑战。为了解决这些问题，在本文中，我们提出了一种新颖的异构自适应联邦低秩适配（LoRA）微调LLM框架（HAFL）。为了适应客户端资源的异质性，我们首先引入了一种基于重要性的参数截断方案，允许客户端具有不同的LoRA秩，并且使用平滑的敏感度分数作为重要性指标。尽管具有灵活性，但截断过程可能会导致性能下降。为了解决这个问题，我们开发了一种基于重要性的参数冻结方案。在这种方法中，云服务器和客户端都保持相同的LoRA秩，而客户端有选择地仅更新最重要的分解LoRA秩-1矩阵，其余部分保持冻结。为了减轻零填充聚合方法导致的信息稀释，我们提出了一种在分解的秩-1矩阵级别运行的自适应聚合方法。在20个新闻组分类任务上的实验表明，与基于截断的异构LoRA秩方案相比，我们的方法在通信量小的情况下快速收敛，并且在向客户端分配模型时避免了性能下降。此外，与零填充方法相比，我们的自适应聚合方法实现了更快的收敛。

> Federated fine-tuning of pre-trained Large Language Models (LLMs) enables task-specific adaptation across diverse datasets while preserving data privacy. However, the large model size and heterogeneity in client resources pose significant computational and communication challenges. To address these issues, in this paper, we propose a novel Heterogeneous Adaptive Federated Low-Rank Adaptation (LoRA) fine-tuned LLM framework (HAFL). To accommodate client resource heterogeneity, we first introduce an importance-based parameter truncation scheme, which allows clients to have different LoRA ranks, and smoothed sensitivity scores are used as importance indicators. Despite its flexibility, the truncation process may cause performance degradation. To tackle this problem, we develop an importance-based parameter freezing scheme. In this approach, both the cloud server and clients maintain the same LoRA rank, while clients selectively update only the most important decomposed LoRA rank-1 matrices, keeping the rest frozen. To mitigate the information dilution caused by the zero-padding aggregation method, we propose an adaptive aggregation approach that operates at the decomposed rank-1 matrix level. Experiments on the 20 News Group classification task show that our method converges quickly with low communication size, and avoids performance degradation when distributing models to clients compared to truncation-based heterogeneous LoRA rank scheme. Additionally, our adaptive aggregation method achieves faster convergence compared to the zero-padding approach.

[Arxiv](https://arxiv.org/abs/2411.06581)