# 小巨人：大规模合成高质量嵌入数据

发布时间：2024年10月24日

`LLM应用` `数据生成` `模型训练`

> Little Giants: Synthesizing High-Quality Embedding Data at Scale

# 摘要

> 合成数据生成已成为一种越来越受欢迎的训练模型的方式，无需大型的、人工标注的数据集。对于像文本嵌入这样的任务，合成数据提供了多样化和可扩展的训练示例，显著降低了人工标注的成本。然而，目前大多数方法严重依赖像 GPT-4 这样的专有模型，对于生成大规模嵌入数据来说，这些模型昂贵且效率低下。在本文中，我们引入了 SPEED，这是一个将开源小模型（8B）对齐以有效生成大规模合成嵌入数据的框架。通过监督微调、偏好优化和自我改进，SPEED 使小型开源模型能够产生高质量的数据。值得注意的是，SPEED 仅使用不到 GPT API 调用的 1/10，当两者都仅在其合成数据上训练时，其性能优于最先进的嵌入模型 E5_mistral。使用这个高效的生成器，我们对对齐管道内的各种因素如何影响数据质量进行了全面研究，并揭示了合成嵌入数据的缩放规律。

> Synthetic data generation has become an increasingly popular way of training models without the need for large, manually labeled datasets. For tasks like text embedding, synthetic data offers diverse and scalable training examples, significantly reducing the cost of human annotation. However, most current approaches rely heavily on proprietary models like GPT-4, which are expensive and inefficient for generating large-scale embedding data. In this paper, we introduce SPEED, a framework that aligns open-source small models (8B) to efficiently generate large-scale synthetic embedding data. Through supervised fine-tuning, preference optimization, and self-improvement, SPEED enables small open-source models to produce high-quality data. Remarkably, SPEED uses only less than 1/10 of the GPT API calls, outperforming the state-of-the-art embedding model E5_mistral when both are trained solely on their synthetic data. Using this efficient generator, we conduct a comprehensive study on how various factors within the alignment pipeline impact data quality and reveal the scaling law for synthetic embedding data.

[Arxiv](https://arxiv.org/abs/2410.18634)