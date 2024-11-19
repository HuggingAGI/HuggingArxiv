# TEESlice：在攻击者持有预训练模型的情况下，于可信执行环境中守护敏感的神经网络模型

发布时间：2024年11月14日

`LLM应用` `计算机安全`

> TEESlice: Protecting Sensitive Neural Network Models in Trusted Execution Environments When Attackers have Pre-Trained Models

# 摘要

> 可信执行环境（TEE）用于守护设备上的模型。不过，由于计算速度受限，直接借助TEE来保障整个DNN模型的安全颇具难度。使用GPU能够加快DNN的运算速度，可市面上广泛可得的商用GPU通常缺少安全防护。为此，学者们推出了TSDP，这一方法能在TEE中保护隐私敏感权重，并把不敏感的权重转移到GPU上。然而，当下的方法未考虑到存在这样一种博学的对手，他们能够获取大量公开可用的预训练模型和数据集。本文探究了现有方法面对此类博学对手时的安全性，揭示了它们无法兑现安全承诺。于是，我们引入了一种全新的训练前分区策略，有效地将隐私敏感权重与模型的其他部分分离。我们的评估显示，我们的方法能够提供全面的模型保护，计算成本降低了十倍。除了传统的CNN模型，我们还展现了对大型语言模型的可扩展性。我们的方法能够将大型语言模型的私有功能压缩为轻量切片，并达到与屏蔽整个模型基线相同的保护水平。

> Trusted Execution Environments (TEE) are used to safeguard on-device models. However, directly employing TEEs to secure the entire DNN model is challenging due to the limited computational speed. Utilizing GPU can accelerate DNN's computation speed but commercial widely-available GPUs usually lack security protection. To this end, scholars introduce TSDP, a method that protects privacy-sensitive weights within TEEs and offloads insensitive weights to GPUs. Nevertheless, current methods do not consider the presence of a knowledgeable adversary who can access abundant publicly available pre-trained models and datasets. This paper investigates the security of existing methods against such a knowledgeable adversary and reveals their inability to fulfill their security promises. Consequently, we introduce a novel partition before training strategy, which effectively separates privacy-sensitive weights from other components of the model. Our evaluation demonstrates that our approach can offer full model protection with a computational cost reduced by a factor of 10. In addition to traditional CNN models, we also demonstrate the scalability to large language models. Our approach can compress the private functionalities of the large language model to lightweight slices and achieve the same level of protection as the shielding-whole-model baseline.

[Arxiv](https://arxiv.org/abs/2411.09945)