# 无需训练，通过加权模态融合与相似性实现零-shot跨模态检索

发布时间：2024年09月07日

`LLM应用`

> Training-free ZS-CIR via Weighted Modality Fusion and Similarity

# 摘要

> 组合图像检索 (CIR) 通过将查询表述为参考图像和修改文本的组合，因其捕捉用户意图的强大能力，成为一种新兴的图像搜索方式。然而，监督式训练 CIR 模型通常需要大量收集 (参考图像，文本修改器，目标图像) 三元组。现有的零-shot CIR (ZS-CIR) 方法虽无需特定下游数据集的训练，但仍需大规模图像-文本对的预训练。本文提出了一种无需训练的 ZS-CIR 方法——\textbf{Wei}ghted \textbf{Mo}dality fusion and similarity for \textbf{CIR} (WeiMoCIR)，假设图像和文本模态可通过简单加权平均有效融合，从而直接构建查询表示。此外，我们利用多模态大语言模型 (MLLMs) 为数据库图像生成标题，并通过加权平均将这些文本标题与图像信息结合，提升检索性能。该方法简便易行，已在 FashionIQ 和 CIRR 数据集上验证其有效性。

> Composed image retrieval (CIR), which formulates the query as a combination of a reference image and modified text, has emerged as a new form of image search due to its enhanced ability to capture users' intentions. However, training a CIR model in a supervised manner typically requires labor-intensive collection of (reference image, text modifier, target image) triplets. While existing zero-shot CIR (ZS-CIR) methods eliminate the need for training on specific downstream datasets, they still require additional pretraining with large-scale image-text pairs. In this paper, we introduce a training-free approach for ZS-CIR. Our approach, \textbf{Wei}ghted \textbf{Mo}dality fusion and similarity for \textbf{CIR} (WeiMoCIR), operates under the assumption that image and text modalities can be effectively combined using a simple weighted average. This allows the query representation to be constructed directly from the reference image and text modifier. To further enhance retrieval performance, we employ multimodal large language models (MLLMs) to generate image captions for the database images and incorporate these textual captions into the similarity computation by combining them with image information using a weighted average. Our approach is simple, easy to implement, and its effectiveness is validated through experiments on the FashionIQ and CIRR datasets.

[Arxiv](https://arxiv.org/abs/2409.04918)