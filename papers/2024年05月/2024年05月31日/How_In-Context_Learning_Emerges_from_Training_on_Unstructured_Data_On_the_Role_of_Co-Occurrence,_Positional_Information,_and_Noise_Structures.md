# 非结构化数据训练如何孕育情境学习：共现、位置信息与噪声结构的奥秘

发布时间：2024年05月31日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在非结构化文本数据上的无监督训练中如何展现上下文学习（ICL）能力。它通过理论证明和实证验证，揭示了ICL的产生机制，并分析了位置信息和噪声结构对ICL泛化能力的影响。此外，论文还讨论了ICL失效的情况及其理论解释。这些内容主要集中在LLMs的理论研究上，因此适合归类为LLM理论。` `机器学习`

> How In-Context Learning Emerges from Training on Unstructured Data: On the Role of Co-Occurrence, Positional Information, and Noise Structures

# 摘要

> Transformer等大型语言模型（LLMs）展现出卓越的上下文学习（ICL）能力，能在不更新参数的情况下，依据输入-输出序列对新查询进行预测。尽管众多理论试图阐释ICL，但它们往往聚焦于类似ICL任务的结构化训练数据，例如回归。实际上，这些模型是在与ICL任务差异较大的非结构化文本数据上进行无监督训练的。因此，我们探究了ICL如何在非结构化数据的无监督训练中显现。我们发现，通过连续词袋（CBOW）等经典语言模型对共现信息进行建模，ICL便能自然产生，这一发现得到了我们的理论证明和实证验证。此外，我们明确了位置信息和噪声结构对于ICL泛化至未见数据的重要性。最后，我们揭示了ICL失效的案例，并提供了理论解释，指出LLMs在识别特定任务时，其ICL能力可能对训练数据的结构高度敏感。

> Large language models (LLMs) like transformers have impressive in-context learning (ICL) capabilities; they can generate predictions for new queries based on input-output sequences in prompts without parameter updates. While many theories have attempted to explain ICL, they often focus on structured training data similar to ICL tasks, such as regression. In practice, however, these models are trained in an unsupervised manner on unstructured text data, which bears little resemblance to ICL tasks. To this end, we investigate how ICL emerges from unsupervised training on unstructured data. The key observation is that ICL can arise simply by modeling co-occurrence information using classical language models like continuous bag of words (CBOW), which we theoretically prove and empirically validate. Furthermore, we establish the necessity of positional information and noise structure to generalize ICL to unseen data. Finally, we present instances where ICL fails and provide theoretical explanations; they suggest that the ICL ability of LLMs to identify certain tasks can be sensitive to the structure of the training data.

![非结构化数据训练如何孕育情境学习：共现、位置信息与噪声结构的奥秘](../../../paper_images/2406.00131/icl_fig.png)

![非结构化数据训练如何孕育情境学习：共现、位置信息与噪声结构的奥秘](../../../paper_images/2406.00131/one-layer.png)

![非结构化数据训练如何孕育情境学习：共现、位置信息与噪声结构的奥秘](../../../paper_images/2406.00131/five-layer.png)

[Arxiv](https://arxiv.org/abs/2406.00131)