# 随着多模态大型语言模型的兴起，我们需重新审视图像检索中的稀疏词汇表示。

发布时间：2024年08月29日

`LLM应用` `图像检索`

> Rethinking Sparse Lexical Representations for Image Retrieval in the Age of Rising Multi-Modal Large Language Models

# 摘要

> 本文重新审视了图像检索中的稀疏词汇表示。借助支持视觉提示的多模态大型语言模型（M-LLM），我们能提取图像特征并转换为文本数据，进而运用自然语言处理中的高效稀疏检索算法进行图像检索。为提升LLM的图像特征提取能力，我们采用了关键扩展的数据增强技术，并通过相关性度量分析其效果。实验表明，在基于关键词的图像检索场景中，我们的方法在MS-COCO、PASCAL VOC和NUS-WIDE数据集上，相比传统视觉-语言模型方法，精确度和召回率更胜一筹。此外，通过迭代地将关键词融入搜索查询，检索性能得以进一步提升。

> In this paper, we rethink sparse lexical representations for image retrieval. By utilizing multi-modal large language models (M-LLMs) that support visual prompting, we can extract image features and convert them into textual data, enabling us to utilize efficient sparse retrieval algorithms employed in natural language processing for image retrieval tasks. To assist the LLM in extracting image features, we apply data augmentation techniques for key expansion and analyze the impact with a metric for relevance between images and textual data. We empirically show the superior precision and recall performance of our image retrieval method compared to conventional vision-language model-based methods on the MS-COCO, PASCAL VOC, and NUS-WIDE datasets in a keyword-based image retrieval scenario, where keywords serve as search queries. We also demonstrate that the retrieval performance can be improved by iteratively incorporating keywords into search queries.

[Arxiv](https://arxiv.org/abs/2408.16296)