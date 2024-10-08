# 通过重新参数化减轻损失峰值，实现大型语言模型的优化初始化。

发布时间：2024年10月07日

`LLM理论` `人工智能` `机器学习`

> Initialization of Large Language Models via Reparameterization to Mitigate Loss Spikes

# 摘要

> 损失尖峰是大型语言模型预训练中的常见问题，本文认为参数范数的非均匀性是导致这一现象的原因之一。在Transformer模型中，为了防止梯度问题，参数范数必须非均匀，这使得小范数参数对更新更为敏感。为此，我们提出了WeSaR技术，通过引入门参数，均匀调整参数范数，从而稳定训练过程。实验证明，WeSaR不仅提升了训练稳定性，还加速了训练速度，在多种方法中表现尤为出色。

> Loss spikes, a phenomenon in which the loss value diverges suddenly, is a fundamental issue in the pre-training of large language models. This paper supposes that the non-uniformity of the norm of the parameters is one of the causes of loss spikes. Here, in training of neural networks, the scale of the gradients is required to be kept constant throughout the layers to avoid the vanishing and exploding gradients problem. However, to meet these requirements in the Transformer model, the norm of the model parameters must be non-uniform, and thus, parameters whose norm is smaller are more sensitive to the parameter update. To address this issue, we propose a novel technique, weight scaling as reparameterization (WeSaR). WeSaR introduces a gate parameter per parameter matrix and adjusts it to the value satisfying the requirements. Because of the gate parameter, WeSaR sets the norm of the original parameters uniformly, which results in stable training. Experimental results with the Transformer decoders consisting of 130 million, 1.3 billion, and 13 billion parameters showed that WeSaR stabilizes and accelerates training and that it outperformed compared methods including popular initialization methods.

[Arxiv](https://arxiv.org/abs/2410.05052)