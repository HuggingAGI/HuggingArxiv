# EACO-RAG：具备自适应知识更新的边缘辅助与协作式 RAG

发布时间：2024年10月26日

`RAG` `物联网`

> EACO-RAG: Edge-Assisted and Collaborative RAG with Adaptive Knowledge Update

# 摘要

> 大型语言模型正在给网络、移动和物联网系统带来变革，推动着智能且可扩展的解决方案。然而，随着检索增强生成（RAG）系统的不断拓展，它们面临着与可扩展性相关的显著挑战，比如延迟增加和通信开销增大。为应对这些问题，我们提出了 EACO-RAG，这是一个借助边缘辅助的分布式 RAG 系统，它利用了自适应知识更新和节点间协作。通过在边缘节点分布向量数据集并优化检索流程，EACO-RAG 大幅降低了延迟和资源消耗，同时提升了响应的准确性。该系统运用带有安全在线贝叶斯方法的多臂老虎机框架，以平衡性能与成本。大量的实验评估显示，EACO-RAG 在响应时间和资源效率上都超越了传统的集中式 RAG 系统。EACO-RAG 成功地将延迟和资源支出降低到与本地 RAG 系统相近甚至更低的水平，同时显著提高了准确性。本研究首次对边缘辅助的分布式 RAG 架构展开了系统探索，为大规模分布式环境提供了一种可扩展且性价比高的解决方案。

> Large Language Models are revolutionizing Web, mobile, and Web of Things systems, driving intelligent and scalable solutions. However, as Retrieval-Augmented Generation (RAG) systems expand, they encounter significant challenges related to scalability, including increased delay and communication overhead. To address these issues, we propose EACO-RAG, an edge-assisted distributed RAG system that leverages adaptive knowledge updates and inter-node collaboration. By distributing vector datasets across edge nodes and optimizing retrieval processes, EACO-RAG significantly reduces delay and resource consumption while enhancing response accuracy. The system employs a multi-armed bandit framework with safe online Bayesian methods to balance performance and cost. Extensive experimental evaluation demonstrates that EACO-RAG outperforms traditional centralized RAG systems in both response time and resource efficiency. EACO-RAG effectively reduces delay and resource expenditure to levels comparable to, or even lower than, those of local RAG systems, while significantly improving accuracy. This study presents the first systematic exploration of edge-assisted distributed RAG architectures, providing a scalable and cost-effective solution for large-scale distributed environments.

[Arxiv](https://arxiv.org/abs/2410.20299)