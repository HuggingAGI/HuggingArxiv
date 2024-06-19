# BIOSCAN-5M：昆虫生物多样性研究的多模态数据集

发布时间：2024年06月18日

`Agent

理由：这篇论文主要介绍了BIOSCAN-5M昆虫数据集，并探讨了如何利用多模态数据（包括DNA条形码、图像和分类信息）进行分类和聚类任务。虽然涉及到了预训练语言模型和自监督学习，但这些技术的应用主要是为了解决特定的生物多样性监测问题，而不是专注于语言模型本身的理论研究或应用。因此，这篇论文更符合Agent分类，因为它描述了一个具体的应用场景，其中机器学习模型被用作解决特定问题的工具或代理。` `生物多样性` `数据集`

> BIOSCAN-5M: A Multimodal Dataset for Insect Biodiversity

# 摘要

> 本文向机器学习界介绍了BIOSCAN-5M昆虫数据集，并设立了几个基准任务，以支持全球对昆虫生物多样性的理解和监测。该数据集包含超过500万昆虫标本的多模态信息，包括分类标签、DNA条形码序列、索引号及地理信息，极大地丰富了现有的生物数据集。我们设计了三个实验来探究多模态数据对分类和聚类的影响：首先，我们利用BIOSCAN-5M的DNA条形码预训练了一个语言模型，并评估了其对物种和属级分类的提升效果；其次，我们通过零样本迁移学习，结合图像和DNA条形码，探索了自监督学习特征嵌入的聚类潜力；最后，我们通过对比学习整合DNA条形码、图像及分类信息，创建了一个多模态共享嵌入空间，以支持基于多种信息的分类。BIOSCAN-5M数据集的代码库已公开，地址为{\url{https://github.com/zahrag/BIOSCAN-5M}}。

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