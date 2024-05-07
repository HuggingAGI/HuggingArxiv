# GeoContrastNet：一种对比关键值边缘学习方法，旨在实现对文档的深入理解，而不受语言限制。

发布时间：2024年05月05日

`Agent` `文档理解`

> GeoContrastNet: Contrastive Key-Value Edge Learning for Language-Agnostic Document Understanding

# 摘要

> 本论文提出了 GeoContrastNet，一个不受语言限制的结构化文档理解框架，它通过融合对比学习目标与图注意力网络（GATs），特别强调了几何特征的重要性。我们创新性地将几何边特征与视觉特征相结合，构建了一个两阶段的 GAT 框架，不仅在链接预测和语义实体识别上取得了显著成效。研究结果表明，融合几何与视觉特征的方法，能够在性能精度和效率上与依赖于光学字符识别（OCR）的大型文档理解模型相媲美。这一方法突出了页面半结构化布局中文本实体间关系布局信息的核心价值。具体而言，模型在 FUNSD 数据集中识别表单的键值关系，以及在 RVLCDIP 商业发票的表格布局中揭示空间关系方面表现出色。我们的代码和预训练模型将在 GitHub 官方仓库开放获取。

> This paper presents GeoContrastNet, a language-agnostic framework to structured document understanding (DU) by integrating a contrastive learning objective with graph attention networks (GATs), emphasizing the significant role of geometric features. We propose a novel methodology that combines geometric edge features with visual features within an overall two-staged GAT-based framework, demonstrating promising results in both link prediction and semantic entity recognition performance. Our findings reveal that combining both geometric and visual features could match the capabilities of large DU models that rely heavily on Optical Character Recognition (OCR) features in terms of performance accuracy and efficiency. This approach underscores the critical importance of relational layout information between the named text entities in a semi-structured layout of a page. Specifically, our results highlight the model's proficiency in identifying key-value relationships within the FUNSD dataset for forms and also discovering the spatial relationships in table-structured layouts for RVLCDIP business invoices. Our code and pretrained models will be accessible on our official GitHub.

[Arxiv](https://arxiv.org/abs/2405.03104)