# 蜜蜂计划：一个基于基础嵌入模型的可扩展模块化框架，专为构建多模态肿瘤学数据集而设计。

发布时间：2024年05月13日

`Agent

理由：这篇论文介绍了一个名为HoneyBee的框架，它是一个可扩展的模块化系统，用于生成多模态肿瘤学数据集的嵌入。这个框架可以被视为一个智能代理（Agent），因为它能够处理复杂的医学数据，生成有用的嵌入，并支持机器学习应用。它通过融合多种数据类型并利用基础模型来生成代表性嵌入，从而在医学领域内执行特定的任务，这与Agent的概念相符。此外，HoneyBee的设计目的是为了推动肿瘤学研究的发展，这表明它是一个专注于特定应用领域的Agent。` `肿瘤学` `机器学习`

> HoneyBee: A Scalable Modular Framework for Creating Multimodal Oncology Datasets with Foundational Embedding Models

# 摘要

> 为了开发精准的肿瘤学机器学习模型，我们需要大规模且高质量的多模态数据集。然而，由于医学数据的复杂性和多样性，创建这样的数据集颇具挑战。为此，我们推出了HoneyBee，一个可扩展的模块化框架，它利用基础模型来生成代表性嵌入，从而构建多模态肿瘤学数据集。HoneyBee融合了临床记录、影像数据和患者结果等多种数据类型，并通过数据预处理和基于变压器的架构来捕捉原始医学数据的关键特征和关联。这些嵌入以结构化形式存储，便于使用Hugging Face数据集和PyTorch数据加载器进行访问。向量数据库则支持机器学习应用的高效查询和检索。我们通过实验验证了HoneyBee生成的嵌入的质量和代表性，证明了其有效性。该框架不仅可扩展至其他医学领域，而且旨在通过提供高质量、即刻可用于机器学习的数据集来推动肿瘤学研究的发展。HoneyBee是一个持续发展的开源项目，其代码、数据集和模型均可在项目仓库中获取。

> Developing accurate machine learning models for oncology requires large-scale, high-quality multimodal datasets. However, creating such datasets remains challenging due to the complexity and heterogeneity of medical data. To address this challenge, we introduce HoneyBee, a scalable modular framework for building multimodal oncology datasets that leverages foundational models to generate representative embeddings. HoneyBee integrates various data modalities, including clinical records, imaging data, and patient outcomes. It employs data preprocessing techniques and transformer-based architectures to generate embeddings that capture the essential features and relationships within the raw medical data. The generated embeddings are stored in a structured format using Hugging Face datasets and PyTorch dataloaders for accessibility. Vector databases enable efficient querying and retrieval for machine learning applications. We demonstrate the effectiveness of HoneyBee through experiments assessing the quality and representativeness of the embeddings. The framework is designed to be extensible to other medical domains and aims to accelerate oncology research by providing high-quality, machine learning-ready datasets. HoneyBee is an ongoing open-source effort, and the code, datasets, and models are available at the project repository.

[Arxiv](https://arxiv.org/abs/2405.07460)