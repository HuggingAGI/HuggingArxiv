# 提取预训练 Transformer 模型的句子嵌入

发布时间：2024年08月15日

`LLM理论` `机器学习`

> Extracting Sentence Embeddings from Pretrained Transformer Models

# 摘要

> 预训练transformer模型在众多NLP任务中大放异彩，其句子级嵌入在增强检索生成中亦显关键。然而，常规的简单平均或提示模板是否能充分展现其深层含义？我们通过多种技术，从BERT的多层多token隐藏表示中提取最佳句子表示，并在多个STS、聚类和分类任务上验证了这些方法的有效性。结果显示，通过表示塑造技术，简单基线不仅与复杂BERT模型匹敌，甚至有所超越，为模型的性能提升开辟了新路径。

> Background/introduction: Pre-trained transformer models shine in many natural language processing tasks and therefore are expected to bear the representation of the input sentence or text meaning. These sentence-level embeddings are also important in retrieval-augmented generation. But do commonly used plain averaging or prompt templates surface it enough?
  Methods: Given 110M parameters BERT's hidden representations from multiple layers and multiple tokens we tried various ways to extract optimal sentence representations. We tested various token aggregation and representation post-processing techniques. We also tested multiple ways of using a general Wikitext dataset to complement BERTs sentence representations. All methods were tested on 8 Semantic Textual Similarity (STS), 6 short text clustering, and 12 classification tasks. We also evaluated our representation-shaping techniques on other static models, including random token representations.
  Results: Proposed representation extraction methods improved the performance on STS and clustering tasks for all models considered. Very high improvements for static token-based models, especially random embeddings for STS tasks almost reach the performance of BERT-derived representations.
  Conclusions: Our work shows that for multiple tasks simple baselines with representation shaping techniques reach or even outperform more complex BERT-based models or are able to contribute to their performance.

[Arxiv](https://arxiv.org/abs/2408.08073)