# 为大型语言模型量身定制的无线联合学习

发布时间：2024年04月19日

`分类：LLM应用` `无线网络` `联邦学习`

> Personalized Wireless Federated Learning for Large Language Models

# 摘要

> 大型语言模型（LLMs）为自然语言处理任务带来了革命性的变化。但在无线网络的应用上，它们仍需克服隐私和安全保护机制不足的挑战。联邦学习（FL）作为解决这些问题的潜在方案，尽管在处理大规模异构数据、训练资源消耗以及通信成本高昂等方面存在挑战。为了应对这些挑战，我们首先对比了LLMs在无线网络中的不同学习阶段及其特点。随后，我们提出了两种低通信开销的个性化无线联邦微调方法：（1）个性化联邦指令微调（PFIT），利用强化学习优化本地LLMs，通过多样化的奖励模型实现个性化；（2）个性化联邦任务微调（PFTT），结合全局适配器和本地低秩适应（LoRA）技术，协作优化本地LLMs，并通过本地LoRA实现个性化而不依赖数据聚合。最终，通过模拟实验验证了这两种方法的有效性，并深入探讨了当前面临的开放性问题。

> Large Language Models (LLMs) have revolutionized natural language processing tasks. However, their deployment in wireless networks still face challenges, i.e., a lack of privacy and security protection mechanisms. Federated Learning (FL) has emerged as a promising approach to address these challenges. Yet, it suffers from issues including inefficient handling with big and heterogeneous data, resource-intensive training, and high communication overhead. To tackle these issues, we first compare different learning stages and their features of LLMs in wireless networks. Next, we introduce two personalized wireless federated fine-tuning methods with low communication overhead, i.e., (1) Personalized Federated Instruction Tuning (PFIT), which employs reinforcement learning to fine-tune local LLMs with diverse reward models to achieve personalization; (2) Personalized Federated Task Tuning (PFTT), which can leverage global adapters and local Low-Rank Adaptations (LoRA) to collaboratively fine-tune local LLMs, where the local LoRAs can be applied to achieve personalization without aggregation. Finally, we perform simulations to demonstrate the effectiveness of the proposed two methods and comprehensively discuss open issues.

![为大型语言模型量身定制的无线联合学习](../../../paper_images/2404.13238/FedLLM0_2.png)

![为大型语言模型量身定制的无线联合学习](../../../paper_images/2404.13238/FedLLM2_1.png)

![为大型语言模型量身定制的无线联合学习](../../../paper_images/2404.13238/FedLLM1_1.png)

![为大型语言模型量身定制的无线联合学习](../../../paper_images/2404.13238/PFIT_exp3_2.jpg)

![为大型语言模型量身定制的无线联合学习](../../../paper_images/2404.13238/PFTT_exp3_3.jpg)

[Arxiv](https://arxiv.org/abs/2404.13238)