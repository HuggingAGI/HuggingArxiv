# BIOSCAN-5M：昆虫生物多样性研究的多模态数据集

发布时间：2024年06月18日

`Agent

理由：这篇论文主要介绍了BIOSCAN-5M昆虫数据集，并设计了多个实验来探究如何利用多模态数据提升分类与聚类的准确性。这些实验包括使用DNA条形码序列预训练掩码语言模型、零样本迁移学习任务以及通过对比学习构建多模态共享的嵌入空间。这些工作更偏向于开发和应用特定的数据集和模型来解决实际问题，即通过机器学习方法来理解和监测昆虫多样性，因此更符合Agent类别的定义，即应用特定的技术和方法来解决实际问题。` `生物多样性` `机器学习`

> BIOSCAN-5M: A Multimodal Dataset for Insect Biodiversity

# 摘要

> 在全球范围内，为了更好地理解和监测昆虫多样性，本文向机器学习界介绍了BIOSCAN-5M昆虫数据集，并设立了多项基准任务。该数据集包含超过500万昆虫标本的多模态信息，不仅涵盖了图像数据，还增加了分类标签、核酸条形码序列及地理信息，极大地丰富了生物数据集的内容。我们设计了三个实验，旨在探究多模态数据如何提升分类与聚类的准确性。首先，我们利用BIOSCAN-5M的DNA条形码序列预训练了一个掩码语言模型，并评估了这一庞大参考库对物种和属级分类的贡献。其次，我们提出了一项零样本迁移学习任务，结合图像与DNA条形码，通过自监督学习得到的特征嵌入进行聚类，探索这些嵌入是否能揭示有意义的生物集群。最后，我们通过对比学习，整合DNA条形码、图像及分类信息，构建了一个多模态共享的嵌入空间，使得分类任务能够综合利用多种信息源。BIOSCAN-5M昆虫数据集的代码库已公开，地址为{\url{https://github.com/zahrag/BIOSCAN-5M}}。

> As part of an ongoing worldwide effort to comprehend and monitor insect biodiversity, this paper presents the BIOSCAN-5M Insect dataset to the machine learning community and establish several benchmark tasks. BIOSCAN-5M is a comprehensive dataset containing multi-modal information for over 5 million insect specimens, and it significantly expands existing image-based biological datasets by including taxonomic labels, raw nucleotide barcode sequences, assigned barcode index numbers, and geographical information. We propose three benchmark experiments to demonstrate the impact of the multi-modal data types on the classification and clustering accuracy. First, we pretrain a masked language model on the DNA barcode sequences of the \mbox{BIOSCAN-5M} dataset, and demonstrate the impact of using this large reference library on species- and genus-level classification performance. Second, we propose a zero-shot transfer learning task applied to images and DNA barcodes to cluster feature embeddings obtained from self-supervised learning, to investigate whether meaningful clusters can be derived from these representation embeddings. Third, we benchmark multi-modality by performing contrastive learning on DNA barcodes, image data, and taxonomic information. This yields a general shared embedding space enabling taxonomic classification using multiple types of information and modalities. The code repository of the BIOSCAN-5M Insect dataset is available at {\url{https://github.com/zahrag/BIOSCAN-5M}}

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x1.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x2.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/BIOSCAN_5M_Insect_Dataset_lat_lon_map.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x3.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x4.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x5.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x6.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x7.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x8.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x9.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x10.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x11.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x12.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x13.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x14.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x15.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x16.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x17.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x18.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x19.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x20.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x21.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x22.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x23.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x24.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x25.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x26.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x27.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x28.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x29.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x30.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x31.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x32.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x33.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x34.png)

![BIOSCAN-5M：昆虫生物多样性研究的多模态数据集](../../../paper_images/2406.12723/x35.png)

[Arxiv](https://arxiv.org/abs/2406.12723)