# 通过逆值学习实现可迁移的训练后优化

发布时间：2024年10月28日

`LLM应用` `人工智能` `神经网络`

> Transferable Post-training via Inverse Value Learning

# 摘要

> 随着训练后流程所采用的数据集日益庞大，基础模型的规模持续扩张，现有算法在计算需求和实施方面面临的挑战大幅攀升。在本文中，我们建议利用一个独立的神经网络（也就是价值网络）来对训练后的对数几率层面的变化进行建模。通过在一个小型基础模型上使用示例训练此网络，该网络能够在推理时与其他预训练模型无缝融合，让它们实现类似的能力提升。我们系统地探究了在预训练权重和连接方案方面这一模式的最优做法。我们证实，所得的价值网络在同一系列中不同参数规模的预训练模型、同一系列中持续进行预训练的模型以及不同系列中具有不同词汇表的模型之间，都具有广泛的可迁移性。在某些情形下，其性能能够媲美全参数微调。另外，我们还探索了增强价值模型可迁移性以及避免对训练所用基础模型过度拟合的方法。

> As post-training processes utilize increasingly large datasets and base models continue to grow in size, the computational demands and implementation challenges of existing algorithms are escalating significantly. In this paper, we propose modeling the changes at the logits level during post-training using a separate neural network (i.e., the value network). After training this network on a small base model using demonstrations, this network can be seamlessly integrated with other pre-trained models during inference, enables them to achieve similar capability enhancements. We systematically investigate the best practices for this paradigm in terms of pre-training weights and connection schemes. We demonstrate that the resulting value network has broad transferability across pre-trained models of different parameter sizes within the same family, models undergoing continuous pre-training within the same family, and models with different vocabularies across families. In certain cases, it can achieve performance comparable to full-parameter fine-tuning. Furthermore, we explore methods to enhance the transferability of the value model and prevent overfitting to the base model used during training.

[Arxiv](https://arxiv.org/abs/2410.21027)