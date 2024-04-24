# 采用优化的距离权重和窗口大小调整策略，提升词嵌入学习效果。

发布时间：2024年04月22日

`分类：LLM理论` `词嵌入`

> Learning Word Embedding with Better Distance Weighting and Window Size Scheduling

# 摘要

> 分布式词表示（即词嵌入）在自然语言处理（NLP）领域占据核心地位。Word2Vec作为一项广受欢迎的词嵌入技术，能够在大规模数据集上高效地学习词汇的分布式表示。尽管如此，Word2Vec在处理中心词与上下文词之间的距离关系时存在不足。为此，我们引入了两种创新方法：可学习公式权重（LFW）和基于时代的动态窗口大小（EDWS），旨在将距离信息整合进Word2Vec的两种主流模型——连续词袋（CBOW）和连续跳字（Skip-gram）模型中。在CBOW模型中，LFW通过一个包含可学习参数的公式来计算与词间影响力和距离相关的权重，进而进行平均池化，这为NLP文本建模的未来研究提供了新的视角。对于Skip-gram模型，我们优化了其动态窗口大小策略，以便更均衡地引入距离信息。实验结果表明，LFW和EDWS在提升Word2Vec的性能上效果显著，超越了先前的顶尖方法。

> Distributed word representation (a.k.a. word embedding) is a key focus in natural language processing (NLP). As a highly successful word embedding model, Word2Vec offers an efficient method for learning distributed word representations on large datasets. However, Word2Vec lacks consideration for distances between center and context words. We propose two novel methods, Learnable Formulated Weights (LFW) and Epoch-based Dynamic Window Size (EDWS), to incorporate distance information into two variants of Word2Vec, the Continuous Bag-of-Words (CBOW) model and the Continuous Skip-gram (Skip-gram) model. For CBOW, LFW uses a formula with learnable parameters that best reflects the relationship of influence and distance between words to calculate distance-related weights for average pooling, providing insights for future NLP text modeling research. For Skip-gram, we improve its dynamic window size strategy to introduce distance information in a more balanced way. Experiments prove the effectiveness of LFW and EDWS in enhancing Word2Vec's performance, surpassing previous state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2404.14631)