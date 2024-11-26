# 向量量化中的表示坍缩问题

发布时间：2024年11月25日

`其他` `机器学习` `生成模型`

> Representation Collapsing Problems in Vector Quantization

# 摘要

> 向量量化是机器学习里的一项技术，能把连续的表示离散成一组离散向量。它在大型语言模型、扩散模型及其他生成模型的数据表示标记化中被广泛运用。尽管如此，生成模型中向量量化的特性和行为在很大程度上仍未被充分探究。在本次研究中，我们对向量量化中的表示崩溃进行了探讨——这是一种关键的退化情况，即码本标记或潜在嵌入因收敛到有限的值子集而丧失判别力。这种崩溃从根本上削弱了模型捕捉多样数据模式的能力。借助合成和真实数据集，我们明确了每种崩溃的严重程度和触发条件。我们的分析显示，受限的初始化和有限的编码器容量会造成标记崩溃和嵌入崩溃。基于这些发现，我们提出了旨在缓解每种崩溃的可能解决方案。据我们所知，这是针对向量量化中表示崩溃问题的首次全面研究。

> Vector quantization is a technique in machine learning that discretizes continuous representations into a set of discrete vectors. It is widely employed in tokenizing data representations for large language models, diffusion models, and other generative models. Despite its prevalence, the characteristics and behaviors of vector quantization in generative models remain largely underexplored. In this study, we investigate representation collapse in vector quantization - a critical degradation where codebook tokens or latent embeddings lose their discriminative power by converging to a limited subset of values. This collapse fundamentally compromises the model's ability to capture diverse data patterns. By leveraging both synthetic and real datasets, we identify the severity of each type of collapses and triggering conditions. Our analysis reveals that restricted initialization and limited encoder capacity result in tokens collapse and embeddings collapse. Building on these findings, we propose potential solutions aimed at mitigating each collapse. To the best of our knowledge, this is the first comprehensive study examining representation collapsing problems in vector quantization.

[Arxiv](https://arxiv.org/abs/2411.16550)