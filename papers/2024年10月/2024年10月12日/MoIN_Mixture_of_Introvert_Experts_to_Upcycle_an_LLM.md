# MoIN：内向专家混合体，助力 LLM 升级

发布时间：2024年10月12日

`LLM理论` `人工智能` `云计算`

> MoIN: Mixture of Introvert Experts to Upcycle an LLM

# 摘要

> 本文旨在通过将预训练数据分组并训练专家模型，来升级现有的大型语言模型，而无需全面重新预训练。这些“内向”专家作为轻量级适配器，独立处理查询，避免了传统专家混合模型中的复杂协作。通过冻结基础模型，我们实现了训练和推理的极致并行化，所有专家可并行训练，推理时专家分布在不同GPU上，高效处理请求。我们已验证了这一方法的可行性。

> The goal of this paper is to improve (upcycle) an existing large language model without the prohibitive requirements of continued pre-training of the full-model. The idea is to split the pre-training data into semantically relevant groups and train an expert on each subset. An expert takes the form of a lightweight adapter added on the top of a frozen base model. During inference, an incoming query is first routed to the most relevant expert which is then loaded onto the base model for the forward pass. Unlike typical Mixture of Experts (MoE) models, the experts in our method do not work with other experts for a single query. Hence, we dub them "introvert" experts. Freezing the base model and keeping the experts as lightweight adapters allows extreme parallelism during training and inference. Training of all experts can be done in parallel without any communication channels between them. Similarly, the inference can also be heavily parallelized by distributing experts on different GPUs and routing each request to the GPU containing its relevant expert. We implement a proof-of-concept version of this method and show the validity of our approach.

[Arxiv](https://arxiv.org/abs/2410.09687)