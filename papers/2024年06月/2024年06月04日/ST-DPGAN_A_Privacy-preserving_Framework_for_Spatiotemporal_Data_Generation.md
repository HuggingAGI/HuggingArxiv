# ST-DPGAN：时空数据生成的隐私保护之框架

发布时间：2024年06月04日

`LLM应用

这篇论文主要关注的是结合时空数据分析与大规模语言模型的应用，特别是在保护隐私的前提下生成和使用时空数据。论文中提到的基于图-GAN的模型，以及其在时空数据生成中的应用，都是为了在保持数据实用性的同时确保隐私安全。这与LLM（大型语言模型）的应用领域紧密相关，尤其是在处理和分析敏感数据时如何利用LLM技术。因此，这篇论文应归类于LLM应用。` `隐私保护` `时空数据分析`

> ST-DPGAN: A Privacy-preserving Framework for Spatiotemporal Data Generation

# 摘要

> 时空数据在众多边缘设备中普遍存在，涵盖个人通信至金融交易。随着技术进步，结合时空分析与大规模语言模型的研究日益受到关注。但时空数据常携敏感信息，不宜公开。为此，我们开发了一种基于图-GAN的模型，旨在生成隐私保护的时空数据。该模型在判别器中融入时空注意力机制，生成器则采用时空反卷积技术，有效结合高斯噪声实现差分隐私训练。通过在三大真实数据集上的实验，我们验证了模型的有效性，确保了隐私的同时不失数据实用性。使用此数据训练的预测模型，其性能与基于原始数据训练的模型不相上下。

> Spatiotemporal data is prevalent in a wide range of edge devices, such as those used in personal communication and financial transactions. Recent advancements have sparked a growing interest in integrating spatiotemporal analysis with large-scale language models. However, spatiotemporal data often contains sensitive information, making it unsuitable for open third-party access. To address this challenge, we propose a Graph-GAN-based model for generating privacy-protected spatiotemporal data. Our approach incorporates spatial and temporal attention blocks in the discriminator and a spatiotemporal deconvolution structure in the generator. These enhancements enable efficient training under Gaussian noise to achieve differential privacy. Extensive experiments conducted on three real-world spatiotemporal datasets validate the efficacy of our model. Our method provides a privacy guarantee while maintaining the data utility. The prediction model trained on our generated data maintains a competitive performance compared to the model trained on the original data.

![ST-DPGAN：时空数据生成的隐私保护之框架](../../../paper_images/2406.03404/x1.png)

![ST-DPGAN：时空数据生成的隐私保护之框架](../../../paper_images/2406.03404/x2.png)

[Arxiv](https://arxiv.org/abs/2406.03404)