# FedsLLM：通信网络中大型语言模型的联邦分割学习

发布时间：2024年07月12日

`LLM应用` `无线通信` `联邦学习`

> FedsLLM: Federated Split Learning for Large Language Models over Communication Networks

# 摘要

> 本文针对无线通信网络中部署大型语言模型的挑战，创新性地结合低秩适应技术（LoRA）与分割联邦学习框架，提出了FedsLLM框架。该方法通过LoRA技术划分网络，减轻处理负载，并利用联邦服务器整合更新客户端模型。由于训练数据在无线网络中传输，训练延迟受学习精度和带宽分配影响。本文通过计算与通信优化，将优化问题简化为凸问题，寻求最优解，并提出精确解的引理。仿真显示，该优化算法平均降低延迟达47.63%，显著提升效率。

> Addressing the challenges of deploying large language models in wireless communication networks, this paper combines low-rank adaptation technology (LoRA) with the splitfed learning framework to propose the federated split learning for large language models (FedsLLM) framework. The method introduced in this paper utilizes LoRA technology to reduce processing loads by dividing the network into client subnetworks and server subnetworks. It leverages a federated server to aggregate and update client models. As the training data are transmitted through a wireless network between clients and both main and federated servers, the training delay is determined by the learning accuracy and the allocation of communication bandwidth. This paper models the minimization of the training delay by integrating computation and communication optimization, simplifying the optimization problem into a convex problem to find the optimal solution. Additionally, it presents a lemma that describes the precise solutions to this problem. Simulation results demonstrate that the proposed optimization algorithm reduces delays by an average of 47.63% compared to unoptimized scenarios.

[Arxiv](https://arxiv.org/abs/2407.09250)