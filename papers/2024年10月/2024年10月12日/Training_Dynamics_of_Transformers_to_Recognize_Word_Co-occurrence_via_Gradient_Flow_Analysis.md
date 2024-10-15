# 通过梯度流分析，揭示 Transformer 识别词共现的训练动态

发布时间：2024年10月12日

`LLM理论` `人工智能` `机器学习`

> Training Dynamics of Transformers to Recognize Word Co-occurrence via Gradient Flow Analysis

# 摘要

> 理解变压器的训练动态对于揭示大型语言模型的强大能力至关重要。本研究聚焦于浅层变压器在识别单词共现任务中的训练过程。与文献中常见的简化方法不同，我们深入分析了从随机初始化开始，同时训练三个注意力矩阵和一个线性 MLP 层的梯度流动。通过构建耦合动力系统框架，我们揭示了训练过程中的关键动态。研究发现，梯度流自然地将训练分为两个阶段：第一阶段，线性 MLP 迅速对齐目标信号以实现准确分类，而注意力机制几乎不变；第二阶段，注意力矩阵与 MLP 协同演化，扩大分类边际并使损失接近最小值。我们还提出了“梯度自动平衡”的新特性，确保不同样本的损失同步下降，从而验证了接近最小训练损失的理论。实验结果进一步支持了我们的理论分析。

> Understanding the training dynamics of transformers is important to explain the impressive capabilities behind large language models. In this work, we study the dynamics of training a shallow transformer on a task of recognizing co-occurrence of two designated words. In the literature of studying training dynamics of transformers, several simplifications are commonly adopted such as weight reparameterization, attention linearization, special initialization, and lazy regime. In contrast, we analyze the gradient flow dynamics of simultaneously training three attention matrices and a linear MLP layer from random initialization, and provide a framework of analyzing such dynamics via a coupled dynamical system. We establish near minimum loss and characterize the attention model after training. We discover that gradient flow serves as an inherent mechanism that naturally divide the training process into two phases. In Phase 1, the linear MLP quickly aligns with the two target signals for correct classification, whereas the softmax attention remains almost unchanged. In Phase 2, the attention matrices and the MLP evolve jointly to enlarge the classification margin and reduce the loss to a near minimum value. Technically, we prove a novel property of the gradient flow, termed \textit{automatic balancing of gradients}, which enables the loss values of different samples to decrease almost at the same rate and further facilitates the proof of near minimum training loss. We also conduct experiments to verify our theoretical results.

[Arxiv](https://arxiv.org/abs/2410.09605)