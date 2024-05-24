# PerLLM：借助边缘与云的协同，为多样化的LLM服务量身定制推理调度策略

发布时间：2024年05月23日

`Agent

理由：这篇论文主要介绍了一个名为 PerLLM 的框架，该框架通过边缘-云协作，为多样化的 LLM 服务提供个性化推理调度。它采用基于约束满足机制的上限置信区间算法来优化调度和资源分配。这个框架可以被视为一个智能代理（Agent），因为它能够根据任务需求和资源动态性进行自主决策和调度，以提高处理效率和降低能源成本。因此，这篇论文更适合归类到Agent分类中。` `云计算` `边缘计算`

> PerLLM: Personalized Inference Scheduling with Edge-Cloud Collaboration for Diverse LLM Services

# 摘要

> 随着大型语言模型用户激增，带宽有限的云服务器难以实时应对海量LLM服务。为此，边缘-云架构应运而生，旨在提升处理效率。但任务需求的多样性与资源动态性给推理调度带来挑战，导致资源浪费。本文介绍的PerLLM框架，通过边缘-云协作，为多样化的LLM服务提供个性化推理调度。面对多重约束与协作决策的复杂性，PerLLM采用基于约束满足机制的上限置信区间算法。它能在边缘-云架构中优化调度和资源分配，确保满足处理时限的同时，大幅降低能源成本。实验证明，PerLLM能有效满足个性化服务需求，吞吐量提升2.2倍、2.1倍和1.6倍，能源成本降低超过50%。

> With the rapid growth in the number of large language model (LLM) users, it is difficult for bandwidth-constrained cloud servers to simultaneously process massive LLM services in real-time. Recently, edge-cloud infrastructures have been used to improve the processing efficiency of large-scale LLM services. However, the diversity of task requirements and the dynamics of resources pose great challenges to inference scheduling, leading to the wastage of many resources. In this paper, we present PerLLM, a personalized inference scheduling framework with edge-cloud collaboration designed for diverse LLM services. For the complexity of multiple constraints and the decision-making process of edge-cloud collaboration, we integrate the upper confidence bound algorithm based on the constraint satisfaction mechanism in PerLLM. For diverse LLM services, PerLLM can optimize service scheduling and resource allocation solutions within the edge-cloud infrastructure to meet processing time requirements while minimizing energy costs. Experimental results from different model deployments show that PerLLM can effectively meet the processing time requirements of personalized services. Compared to other methods, PerLLM achieves 2.2x, 2.1x, and 1.6x throughput and reduces the energy cost by more than 50%.

[Arxiv](https://arxiv.org/abs/2405.14636)