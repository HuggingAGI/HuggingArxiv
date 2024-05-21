# DEMO：探索图像与文本匹配的高效统计方法

发布时间：2024年05月19日

`RAG

理由：这篇论文主要关注的是图像-文本匹配问题，并提出了一种新型的哈希方法（DEMO）来提升匹配效率。这种方法涉及到语义理解、无监督学习以及哈希技术的应用，这些都是检索增强生成（RAG）领域的关键技术。虽然论文中没有直接提到大型语言模型（LLM），但其研究内容与RAG领域中处理大规模数据和优化语义相似性框架的方法紧密相关。因此，将其归类为RAG是合适的。` `图像-文本匹配` `无监督学习`

> DEMO: A Statistical Perspective for Efficient Image-Text Matching

# 摘要

> 图像-文本匹配问题旨在通过语义理解桥接视觉与语言。近期，由于能处理大规模原始数据，无监督哈希方法备受瞩目。这些方法利用自然距离构建语义相似性框架，进而指导模型优化。但语义分布边界处的偏差可能导致优化过程中的错误累积。为此，我们提出了一种新型哈希方法——基于分布结构的挖掘与一致性学习（DEMO），以提升图像-文本匹配效率。DEMO从统计视角出发，通过多重视角增强来刻画图像，视作其内在语义分布的样本。我们采用非参数分布差异确保相似性结构的稳健与精确。同时，引入协同一致性学习，既在汉明空间中保持相似性结构，又以自监督方式促进不同方向检索分布的一致性。在三个图像-文本匹配基准数据集上的实验表明，DEMO的性能超越了许多现有技术。

> Image-text matching has been a long-standing problem, which seeks to connect vision and language through semantic understanding. Due to the capability to manage large-scale raw data, unsupervised hashing-based approaches have gained prominence recently. They typically construct a semantic similarity structure using the natural distance, which subsequently provides guidance to the model optimization process. However, the similarity structure could be biased at the boundaries of semantic distributions, causing error accumulation during sequential optimization. To tackle this, we introduce a novel hashing approach termed Distribution-based Structure Mining with Consistency Learning (DEMO) for efficient image-text matching. From a statistical view, DEMO characterizes each image using multiple augmented views, which are considered as samples drawn from its intrinsic semantic distribution. Then, we employ a non-parametric distribution divergence to ensure a robust and precise similarity structure. In addition, we introduce collaborative consistency learning which not only preserves the similarity structure in the Hamming space but also encourages consistency between retrieval distribution from different directions in a self-supervised manner. Through extensive experiments on three benchmark image-text matching datasets, we demonstrate that DEMO achieves superior performance compared with many state-of-the-art methods.

![DEMO：探索图像与文本匹配的高效统计方法](../../../paper_images/2405.11496/x1.png)

![DEMO：探索图像与文本匹配的高效统计方法](../../../paper_images/2405.11496/x2.png)

![DEMO：探索图像与文本匹配的高效统计方法](../../../paper_images/2405.11496/x3.png)

![DEMO：探索图像与文本匹配的高效统计方法](../../../paper_images/2405.11496/x4.png)

![DEMO：探索图像与文本匹配的高效统计方法](../../../paper_images/2405.11496/x5.png)

![DEMO：探索图像与文本匹配的高效统计方法](../../../paper_images/2405.11496/x6.png)

![DEMO：探索图像与文本匹配的高效统计方法](../../../paper_images/2405.11496/x7.png)

![DEMO：探索图像与文本匹配的高效统计方法](../../../paper_images/2405.11496/x8.png)

[Arxiv](https://arxiv.org/abs/2405.11496)