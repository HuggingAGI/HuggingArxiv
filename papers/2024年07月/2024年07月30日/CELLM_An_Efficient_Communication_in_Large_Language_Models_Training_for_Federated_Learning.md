# CELLM：联邦学习中大型语言模型训练的高效通信策略

发布时间：2024年07月30日

`LLM应用` `信息技术` `人工智能`

> CELLM: An Efficient Communication in Large Language Models Training for Federated Learning

# 摘要

> 联邦学习（FL）是一种新兴的模型训练方式，客户端设备协同训练模型而不共享数据，通过仅传输模型权重更新来保障隐私和安全。然而，客户端数据分布的差异导致统计异质性问题。大型语言模型（LLM）因其处理大量噪声数据的能力，为解决这一问题提供了可能。尽管LLM有助于解决联邦学习中的非I.I.D.客户端问题，但也加剧了本地计算资源有限和通信成本高昂的挑战。本论文致力于开发FL中LLM的高效训练方法，采用低秩适应（LoRA）减轻计算负担，并通过稀疏更新大幅降低通信成本。我们的方法在保持高实用性的同时，将通信成本降低了LoRA的10倍和稀疏LoRA基线的5倍。我们强调在联邦LLM训练中精确应用稀疏性和选择合适配置的重要性。

> Federated Learning (FL) is a recent model training paradigm in which client devices collaboratively train a model without ever aggregating their data. Crucially, this scheme offers users potential privacy and security benefits by only ever communicating updates to the model weights to a central server as opposed to traditional machine learning (ML) training which directly communicates and aggregates data. However, FL training suffers from statistical heterogeneity as clients may have differing local data distributions. Large language models (LLMs) offer a potential solution to this issue of heterogeneity given that they have consistently been shown to be able to learn on vast amounts of noisy data. While LLMs are a promising development for resolving the consistent issue of non-I.I.D. Clients in federated settings exacerbate two other bottlenecks in FL: limited local computing and expensive communication. This thesis aims to develop efficient training methods for LLMs in FL. To this end, we employ two critical techniques in enabling efficient training. First, we use low-rank adaptation (LoRA) to reduce the computational load of local model training. Second, we communicate sparse updates throughout training to significantly cut down on communication costs. Taken together, our method reduces communication costs by up to 10x over vanilla LoRA and up to 5x over more complex sparse LoRA baselines while achieving greater utility. We emphasize the importance of carefully applying sparsity and picking effective rank and sparsity configurations for federated LLM training.

[Arxiv](https://arxiv.org/abs/2407.20557)