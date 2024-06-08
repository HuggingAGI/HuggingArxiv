# ST-DPGAN：时空数据生成的隐私保护之框架

发布时间：2024年06月04日

`Agent

理由：这篇论文主要关注的是如何处理和保护时空数据中的隐私问题，并提出了一种基于图-GAN的模型来生成隐私保护的时空数据。虽然涉及到了大规模语言模型，但重点在于模型的应用，即如何处理时空数据以保护隐私，而不是对语言模型本身的理论研究或应用。因此，这篇论文更符合Agent分类，即关注模型在特定任务（如隐私保护）中的应用和效果。` `隐私保护` `时空数据分析`

> ST-DPGAN: A Privacy-preserving Framework for Spatiotemporal Data Generation

# 摘要

> 时空数据在众多边缘设备中普遍存在，涉及个人通信和金融交易等领域。随着技术进步，人们越来越关注如何将时空分析与大规模语言模型相结合。然而，时空数据往往涉及敏感信息，不宜公开给第三方。为此，我们提出了一种基于图-GAN的模型，旨在生成隐私保护的时空数据。该模型在判别器中融入空间与时间注意力机制，生成器则采用时空反卷积结构，这些创新使得模型能在高斯噪声环境下高效训练，确保差分隐私。通过在三个真实时空数据集上的广泛测试，我们证明了模型的有效性。我们的方法在保障隐私的同时，确保了数据的有效性，使用我们生成的数据训练的预测模型与原始数据训练的模型相比，性能毫不逊色。

> Spatiotemporal data is prevalent in a wide range of edge devices, such as those used in personal communication and financial transactions. Recent advancements have sparked a growing interest in integrating spatiotemporal analysis with large-scale language models. However, spatiotemporal data often contains sensitive information, making it unsuitable for open third-party access. To address this challenge, we propose a Graph-GAN-based model for generating privacy-protected spatiotemporal data. Our approach incorporates spatial and temporal attention blocks in the discriminator and a spatiotemporal deconvolution structure in the generator. These enhancements enable efficient training under Gaussian noise to achieve differential privacy. Extensive experiments conducted on three real-world spatiotemporal datasets validate the efficacy of our model. Our method provides a privacy guarantee while maintaining the data utility. The prediction model trained on our generated data maintains a competitive performance compared to the model trained on the original data.

![ST-DPGAN：时空数据生成的隐私保护之框架](../../../paper_images/2406.03404/x1.png)

![ST-DPGAN：时空数据生成的隐私保护之框架](../../../paper_images/2406.03404/x2.png)

[Arxiv](https://arxiv.org/abs/2406.03404)