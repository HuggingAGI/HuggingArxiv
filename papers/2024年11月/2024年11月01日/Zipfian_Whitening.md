# 齐普夫白化

发布时间：2024年11月01日

`LLM理论` `神经模型`

> Zipfian Whitening

# 摘要

> 摘要：神经模型中的词嵌入空间是倾斜的，对此进行纠正可以提高任务性能。我们指出，大多数用于建模、纠正和测量嵌入空间对称性的方法都隐含地假设词频是均匀的；实际上，词频遵循高度不均匀的分布，即齐普夫定律。令人惊讶的是，仅仅按照遵循齐普夫定律的经验词频进行主成分分析（PCA）白化就显著提高了任务性能，超过了已有的基线。从理论角度来看，我们的方法和现有方法都可以清晰分类：词表示根据具有均匀或齐普夫基础度量的指数族分布。通过采用后一种方法，从信息几何的角度以及不平衡分类的损失函数方面来看，我们可以自然地强调信息丰富的低频词的向量范数。此外，我们的理论证实，流行的自然语言处理方法，如跳过-gram 负采样、WhiteningBERT 和无头语言模型之所以效果良好，是因为它们的词嵌入将经验词频编码到基础概率模型中。

> 
Abstract:The word embedding space in neural models is skewed, and correcting this can improve task performance. We point out that most approaches for modeling, correcting, and measuring the symmetry of an embedding space implicitly assume that the word frequencies are uniform; in reality, word frequencies follow a highly non-uniform distribution, known as Zipf's law. Surprisingly, simply performing PCA whitening weighted by the empirical word frequency that follows Zipf's law significantly improves task performance, surpassing established baselines. From a theoretical perspective, both our approach and existing methods can be clearly categorized: word representations are distributed according to an exponential family with either uniform or Zipfian base measures. By adopting the latter approach, we can naturally emphasize informative low-frequency words in terms of their vector norm, which becomes evident from the information-geometric perspective, and in terms of the loss functions for imbalanced classification. Additionally, our theory corroborates that popular natural language processing methods, such as skip-gram negative sampling, WhiteningBERT, and headless language models, work well just because their word embeddings encode the empirical word frequency into the underlying probabilistic model.
    

[Arxiv](https://arxiv.org/pdf/2411.00680)