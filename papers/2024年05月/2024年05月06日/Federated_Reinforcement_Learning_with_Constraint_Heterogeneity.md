# 在约束异质性条件下的联合强化学习研究

发布时间：2024年05月06日

`分类：Agent` `联邦学习`

> Federated Reinforcement Learning with Constraint Heterogeneity

# 摘要

> 本研究探讨了一种具有约束多样性的联邦强化学习（FedRL）问题。我们旨在解决一个涉及多重约束的强化学习挑战，其中N个训练代理分散在N个不同的环境之中，这些环境对约束信号的获取受限，且各代理需协同进化出满足所有约束的策略。这类学习问题在大型语言模型（LLM）的微调和医疗健康应用中尤为常见。为应对这一挑战，我们提出了一种基于传统策略梯度的联邦原始-对偶策略优化方法。具体而言，我们引入了N个局部拉格朗日函数，供代理进行本地策略更新，并安排这些代理定期就本地策略进行交流。我们特别关注两种算法实例：FedNPG和FedPPO，其中FedNPG证明了其以$\tilde{O}(1/\sqrt{T})$的速率实现全局收敛，而FedPPO则展示了其利用深度神经网络高效处理复杂学习任务的能力。

> We study a Federated Reinforcement Learning (FedRL) problem with constraint heterogeneity. In our setting, we aim to solve a reinforcement learning problem with multiple constraints while $N$ training agents are located in $N$ different environments with limited access to the constraint signals and they are expected to collaboratively learn a policy satisfying all constraint signals. Such learning problems are prevalent in scenarios of Large Language Model (LLM) fine-tuning and healthcare applications. To solve the problem, we propose federated primal-dual policy optimization methods based on traditional policy gradient methods. Specifically, we introduce $N$ local Lagrange functions for agents to perform local policy updates, and these agents are then scheduled to periodically communicate on their local policies. Taking natural policy gradient (NPG) and proximal policy optimization (PPO) as policy optimization methods, we mainly focus on two instances of our algorithms, ie, {FedNPG} and {FedPPO}. We show that FedNPG achieves global convergence with an $\tilde{O}(1/\sqrt{T})$ rate, and FedPPO efficiently solves complicated learning tasks with the use of deep neural networks.

[Arxiv](https://arxiv.org/abs/2405.03236)