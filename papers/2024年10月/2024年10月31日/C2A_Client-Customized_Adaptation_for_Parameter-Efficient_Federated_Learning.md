# C2A：用于参数高效联邦学习的客户端定制化适配

发布时间：2024年10月31日

`LLM应用` `联邦学习` `超网络`

> C2A: Client-Customized Adaptation for Parameter-Efficient Federated Learning

# 摘要

> 尽管预训练语言模型（PLMs）在各领域通用性强，但它们庞大的内存占用给联邦学习（FL）带来了巨大挑战，因为在联邦学习中训练模型得在服务器和客户端间分布。在联邦学习背景下使用参数高效微调（PEFT）或许是绕过这类限制的潜在办法。然而，我们发现，典型的PEFT在联邦学习场景中常因客户端间的异质性而深受影响，致使收敛不稳定且缓慢。本文中，我们提出了客户端定制适应（C2A），这是一种基于新型超网络的联邦学习框架，能依据客户端信息生成特定的适配器。鉴于超网络在通过学习采用输入的不同特征来生成定制权重方面的有效性，C2A能最大程度发挥共享模型参数的效用，同时将客户端异质性导致的分歧最小化。为验证C2A的有效性，我们在涉及标签和语言分布异质性的联邦学习场景中展开了广泛评估。综合评估结果明确显示，在联邦学习场景中，C2A在效率和效果上都表现出色。

> Despite the versatility of pre-trained language models (PLMs) across domains, their large memory footprints pose significant challenges in federated learning (FL), where the training model has to be distributed between a server and clients. One potential solution to bypass such constraints might be the use of parameter-efficient fine-tuning (PEFT) in the context of FL. However, we have observed that typical PEFT tends to severely suffer from heterogeneity among clients in FL scenarios, resulting in unstable and slow convergence. In this paper, we propose Client-Customized Adaptation (C2A), a novel hypernetwork-based FL framework that generates client-specific adapters by conditioning the client information. With the effectiveness of the hypernetworks in generating customized weights through learning to adopt the different characteristics of inputs, C2A can maximize the utility of shared model parameters while minimizing the divergence caused by client heterogeneity. To verify the efficacy of C2A, we perform extensive evaluations on FL scenarios involving heterogeneity in label and language distributions. Comprehensive evaluation results clearly support the superiority of C2A in terms of both efficiency and effectiveness in FL scenarios.

[Arxiv](https://arxiv.org/abs/2411.00311)