# 双层跨模态对比聚类

发布时间：2024年09月06日

`LLM应用` `计算机视觉`

> Dual-Level Cross-Modal Contrastive Clustering

# 摘要

> 图像聚类是无监督学习的核心任务，但现有方法多局限于图像本身的内在信息，忽略了外部知识对语义理解的提升。我们提出的双层跨模态对比聚类（DXMC）框架，通过引入外部文本信息构建语义空间，生成图像-文本对，并利用预训练模型获取嵌入，最终在跨模态和多层次上进行对比学习。实验结果显示，DXMC 在多个基准数据集上表现优异，有效填补了视觉与文本表示之间的鸿沟。

> Image clustering, which involves grouping images into different clusters without labels, is a key task in unsupervised learning. Although previous deep clustering methods have achieved remarkable results, they only explore the intrinsic information of the image itself but overlook external supervision knowledge to improve the semantic understanding of images. Recently, visual-language pre-trained model on large-scale datasets have been used in various downstream tasks and have achieved great results. However, there is a gap between visual representation learning and textual semantic learning, and how to properly utilize the representation of two different modalities for clustering is still a big challenge. To tackle the challenges, we propose a novel image clustering framwork, named Dual-level Cross-Modal Contrastive Clustering (DXMC). Firstly, external textual information is introduced for constructing a semantic space which is adopted to generate image-text pairs. Secondly, the image-text pairs are respectively sent to pre-trained image and text encoder to obtain image and text embeddings which subsquently are fed into four well-designed networks. Thirdly, dual-level cross-modal contrastive learning is conducted between discriminative representations of different modalities and distinct level. Extensive experimental results on five benchmark datasets demonstrate the superiority of our proposed method.

[Arxiv](https://arxiv.org/abs/2409.04561)