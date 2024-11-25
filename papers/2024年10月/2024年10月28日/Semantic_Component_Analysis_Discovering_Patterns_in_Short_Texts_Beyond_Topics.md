# 语义成分分析：探寻短文本中超越主题的规律

发布时间：2024年10月28日

`其他` `文本分析` `社交网络`

> Semantic Component Analysis: Discovering Patterns in Short Texts Beyond Topics

# 摘要

> 主题建模是文本分析的关键方法，然而现有方式存在局限，要么假定每份文档仅有一个主题，要么难以有效拓展至大型、嘈杂的短文本数据集。我们推出了语义成分分析（SCA）这一全新的主题建模技术，它通过在短文本中发掘多个细腻的语义成分（而非单一主题）来突破这些限制，我们在基于聚类的主题建模框架中引入分解步骤达成了这一目标。在多个 Twitter 数据集上进行测评，SCA 在一致性和多样性方面与前沿方法 BERTopic 不相上下，同时能发现至少两倍的语义成分，且保持近乎为零的噪声率，在包括一种代表性不足的语言在内的多种语言中均具有可扩展性和有效性。

> Topic modeling is a key method in text analysis, but existing approaches are limited by assuming one topic per document or fail to scale efficiently for large, noisy datasets of short texts. We introduce Semantic Component Analysis (SCA), a novel topic modeling technique that overcomes these limitations by discovering multiple, nuanced semantic components beyond a single topic in short texts which we accomplish by introducing a decomposition step to the clustering-based topic modeling framework. Evaluated on multiple Twitter datasets, SCA matches the state-of-the-art method BERTopic in coherence and diversity, while uncovering at least double the semantic components and maintaining a noise rate close to zero while staying scalable and effective across languages, including an underrepresented one.

[Arxiv](https://arxiv.org/abs/2410.21054)