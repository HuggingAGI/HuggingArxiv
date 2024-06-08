# 跨域图数据扩展：以扩散模型为例的精彩展示

发布时间：2024年06月03日

`Agent

这篇论文介绍了一种名为UniAug的图结构增强器，它基于扩散模型，并能够自适应地辅助下游任务。该研究的重点在于开发一个能够处理图数据异质性的通用工具，并通过预训练和自适应优化来提升多个下游任务的性能。这与Agent分类相符，因为Agent通常指的是能够自主执行任务、做出决策并适应环境的实体或系统。在这篇论文中，UniAug作为一个Agent，通过其预训练的扩散模型在图数据上执行增强任务，从而在不同的下游应用中提升性能。` `图数据处理` `跨领域应用`

> Cross-Domain Graph Data Scaling: A Showcase with Diffusion Models

# 摘要

> 自然语言和图像模型随着数据量的增加，性能也随之提升，这一现象使得大规模预训练在海量数据上大放异彩。然而，由于图数据的异质性，现有的图预训练方法在数据扩展上遇到了难题。为此，我们开发了UniAug，一种基于扩散模型的通用图结构增强器，旨在捕捉图数据的多样性，并自适应地辅助下游任务。我们首先在多个领域的数千个图上预训练一个离散扩散模型，以掌握图的结构特征。在下游应用中，我们利用预训练的扩散模型进行图结构增强，通过引导生成实现自适应优化。这一策略在多个下游任务中以即插即用的方式，持续提升了性能。据我们所知，这是首次在跨领域图中展示数据扩展图结构增强器的研究。

> Models for natural language and images benefit from data scaling behavior: the more data fed into the model, the better they perform. This 'better with more' phenomenon enables the effectiveness of large-scale pre-training on vast amounts of data. However, current graph pre-training methods struggle to scale up data due to heterogeneity across graphs. To achieve effective data scaling, we aim to develop a general model that is able to capture diverse data patterns of graphs and can be utilized to adaptively help the downstream tasks. To this end, we propose UniAug, a universal graph structure augmentor built on a diffusion model. We first pre-train a discrete diffusion model on thousands of graphs across domains to learn the graph structural patterns. In the downstream phase, we provide adaptive enhancement by conducting graph structure augmentation with the help of the pre-trained diffusion model via guided generation. By leveraging the pre-trained diffusion model for structure augmentation, we consistently achieve performance improvements across various downstream tasks in a plug-and-play manner. To the best of our knowledge, this study represents the first demonstration of a data-scaling graph structure augmentor on graphs across domains.

![跨域图数据扩展：以扩散模型为例的精彩展示](../../../paper_images/2406.01899/x1.png)

![跨域图数据扩展：以扩散模型为例的精彩展示](../../../paper_images/2406.01899/x2.png)

![跨域图数据扩展：以扩散模型为例的精彩展示](../../../paper_images/2406.01899/x3.png)

![跨域图数据扩展：以扩散模型为例的精彩展示](../../../paper_images/2406.01899/x4.png)

![跨域图数据扩展：以扩散模型为例的精彩展示](../../../paper_images/2406.01899/x5.png)

![跨域图数据扩展：以扩散模型为例的精彩展示](../../../paper_images/2406.01899/x6.png)

[Arxiv](https://arxiv.org/abs/2406.01899)