# 2M-NER：一种采用对比学习方法，针对多语言和多模态命名实体识别任务，实现语言与模态融合的技术。

发布时间：2024年04月25日

`Agent` `多模态学习`

> 2M-NER: Contrastive Learning for Multilingual and Multimodal NER with Language and Modal Fusion

# 摘要

> 命名实体识别（NER）是自然语言处理领域的基石，其核心在于识别并归类句子中的实体。它对于实体链接、问答系统和在线商品推荐等多个研究领域至关重要。最新研究揭示，融合多语言和多模态数据集能够显著提升NER的性能，这归功于语言迁移学习以及不同模态间共有的隐含特征。然而，由于缺少一个同时包含多语言和多模态特性的数据集，限制了对这两个要素结合的研究。本文旨在攻克更具挑战性的多语言多模态命名实体识别（MMNER）任务，探讨其潜在的研究价值和影响力。我们构建了一个包含四种语言（英、法、德、西）和两种模态（文本和图像）的大规模MMNER数据集。为解决这一挑战，我们提出了一个创新模型——2M-NER，该模型采用对比学习方法对齐文本与图像表示，并集成了一个多模态协作模块，以有效捕捉两种模态间的交互作用。广泛的实验结果显示，2M-NER在多语言多模态NER任务中取得了最高的F1分数，超越了其他基准模型。此外，我们通过深入分析发现，句子级别的对齐对NER模型构成了较大干扰，反映出我们数据集的高难度特性。

> Named entity recognition (NER) is a fundamental task in natural language processing that involves identifying and classifying entities in sentences into pre-defined types. It plays a crucial role in various research fields, including entity linking, question answering, and online product recommendation. Recent studies have shown that incorporating multilingual and multimodal datasets can enhance the effectiveness of NER. This is due to language transfer learning and the presence of shared implicit features across different modalities. However, the lack of a dataset that combines multilingualism and multimodality has hindered research exploring the combination of these two aspects, as multimodality can help NER in multiple languages simultaneously. In this paper, we aim to address a more challenging task: multilingual and multimodal named entity recognition (MMNER), considering its potential value and influence. Specifically, we construct a large-scale MMNER dataset with four languages (English, French, German and Spanish) and two modalities (text and image). To tackle this challenging MMNER task on the dataset, we introduce a new model called 2M-NER, which aligns the text and image representations using contrastive learning and integrates a multimodal collaboration module to effectively depict the interactions between the two modalities. Extensive experimental results demonstrate that our model achieves the highest F1 score in multilingual and multimodal NER tasks compared to some comparative and representative baselines. Additionally, in a challenging analysis, we discovered that sentence-level alignment interferes a lot with NER models, indicating the higher level of difficulty in our dataset.

[Arxiv](https://arxiv.org/abs/2404.17122)