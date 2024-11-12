# 聚类算法和 RAG 利用大型 LLM 增强半监督文本分类

发布时间：2024年11月09日

`RAG` `文本分类` `数据生成`

> Clustering Algorithms and RAG Enhancing Semi-Supervised Text Classification with Large LLMs

# 摘要

> 这篇论文介绍了一种用于文本分类的创新半监督学习方法，解决了数据丰富但有标签示例有限的挑战。我们的方法将少样本学习与检索增强生成（RAG）和传统的统计聚类相结合，能够从最少数量的有标签实例中进行有效学习，同时生成高质量的有标签数据。据我们所知，我们是第一个在文本数据生成中结合 RAG 和聚类的。我们在路透社和科学网数据集上的实验展示了最先进的性能，仅使用少样本增强数据产生的结果几乎与使用完全有标签的数据集所取得的结果相当。值得注意的是，对于复杂的文本文档分类任务，实现了 95.41％和 82.43％的准确率，其中类别数量可能超过 100 个。

> This paper introduces an innovative semi-supervised learning approach for text classification, addressing the challenge of abundant data but limited labeled examples. Our methodology integrates few-shot learning with retrieval-augmented generation (RAG) and conventional statistical clustering, enabling effective learning from a minimal number of labeled instances while generating high-quality labeled data. To the best of our knowledge, we are the first to incorporate RAG alongside clustering in text data generation. Our experiments on the Reuters and Web of Science datasets demonstrate state-of-the-art performance, with few-shot augmented data alone producing results nearly equivalent to those achieved with fully labeled datasets. Notably, accuracies of 95.41\% and 82.43\% were achieved for complex text document classification tasks, where the number of categories can exceed 100.

[Arxiv](https://arxiv.org/abs/2411.06175)