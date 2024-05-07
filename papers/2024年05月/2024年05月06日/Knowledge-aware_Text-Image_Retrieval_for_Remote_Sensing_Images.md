# 为遥感图像设计的文本与图像知识感知检索系统

发布时间：2024年05月06日

`分类：Agent` `图像检索`

> Knowledge-aware Text-Image Retrieval for Remote Sensing Images

# 摘要

> 在庞大的地球观测数据库中进行图像检索并非易事，因为用户必须依靠查询图像来筛选数以千计的潜在匹配项。尽管利用文本信息辅助视觉查询提升了系统的易用性，但由于视觉信号的多样性，这些信号难以用简短的说明文字概括，这使得检索系统面临挑战。针对这一问题，我们提出了一种知识驱动的文本-图像检索（KTIR）方法，专门针对遥感图像。KTIR通过从外部知识库中提取相关信息，扩展了搜索查询中的文本内容，弥补了文本与图像之间的信息不对称，从而提高了匹配质量。此外，KTIR通过融合领域特定知识，增强了预训练的视觉-语言模型对遥感任务的适应能力。在三个广泛使用的遥感文本-图像检索基准测试中，KTIR方法展现出了多样化且一致的检索效果，性能超越了当前的顶尖检索技术。

> Image-based retrieval in large Earth observation archives is challenging because one needs to navigate across thousands of candidate matches only with the query image as a guide. By using text as information supporting the visual query, the retrieval system gains in usability, but at the same time faces difficulties due to the diversity of visual signals that cannot be summarized by a short caption only. For this reason, as a matching-based task, cross-modal text-image retrieval often suffers from information asymmetry between texts and images. To address this challenge, we propose a Knowledge-aware Text-Image Retrieval (KTIR) method for remote sensing images. By mining relevant information from an external knowledge graph, KTIR enriches the text scope available in the search query and alleviates the information gaps between texts and images for better matching. Moreover, by integrating domain-specific knowledge, KTIR also enhances the adaptation of pre-trained vision-language models to remote sensing applications. Experimental results on three commonly used remote sensing text-image retrieval benchmarks show that the proposed knowledge-aware method leads to varied and consistent retrievals, outperforming state-of-the-art retrieval methods.

[Arxiv](https://arxiv.org/abs/2405.03373)