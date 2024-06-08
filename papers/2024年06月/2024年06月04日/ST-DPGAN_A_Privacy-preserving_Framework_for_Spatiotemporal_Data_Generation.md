# ST-DPGAN：时空数据生成的隐私保护框架

发布时间：2024年06月04日

`Agent

理由：这篇论文主要介绍了一种基于图-GAN的模型，用于生成隐私保护的时空数据。该模型通过融合时空注意力机制和时空反卷积结构，实现了差分隐私，并在多个真实数据集上验证了其有效性。虽然涉及到了大型语言模型（LLM），但论文的重点在于开发和应用一个特定的模型（Agent）来处理时空数据，而不是探讨LLM的理论或应用，也不是关于检索增强生成（RAG）的研究。因此，将其归类为Agent更为合适。` `隐私保护` `时空数据分析`

> ST-DPGAN: A Privacy-preserving Framework for Spatiotemporal Data Generation

# 摘要

> 时空数据在众多边缘设备中普遍存在，例如个人通信和金融交易设备。随着技术进步，人们越来越关注将时空分析与大型语言模型相结合。但时空数据往往涉及敏感信息，不宜公开给第三方。为此，我们开发了一种基于图-GAN的模型，旨在生成隐私保护的时空数据。该模型在判别器中融合了时空注意力机制，生成器则采用时空反卷积结构，有效提升了在添加高斯噪声时的训练效率，实现了差分隐私。通过在三个真实时空数据集上的大量实验，我们验证了模型的有效性。此方法在确保隐私的同时，不损数据实用性，使用生成数据训练的预测模型性能与原始数据训练的模型相媲美。

> Spatiotemporal data is prevalent in a wide range of edge devices, such as those used in personal communication and financial transactions. Recent advancements have sparked a growing interest in integrating spatiotemporal analysis with large-scale language models. However, spatiotemporal data often contains sensitive information, making it unsuitable for open third-party access. To address this challenge, we propose a Graph-GAN-based model for generating privacy-protected spatiotemporal data. Our approach incorporates spatial and temporal attention blocks in the discriminator and a spatiotemporal deconvolution structure in the generator. These enhancements enable efficient training under Gaussian noise to achieve differential privacy. Extensive experiments conducted on three real-world spatiotemporal datasets validate the efficacy of our model. Our method provides a privacy guarantee while maintaining the data utility. The prediction model trained on our generated data maintains a competitive performance compared to the model trained on the original data.

![ST-DPGAN：时空数据生成的隐私保护框架](../../../paper_images/2406.03404/x1.png)

![ST-DPGAN：时空数据生成的隐私保护框架](../../../paper_images/2406.03404/x2.png)

[Arxiv](https://arxiv.org/abs/2406.03404)