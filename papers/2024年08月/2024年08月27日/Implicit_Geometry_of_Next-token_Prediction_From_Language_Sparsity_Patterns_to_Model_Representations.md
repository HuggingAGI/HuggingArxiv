# 探索下一个标记预测的隐式几何：揭秘语言稀疏模式与模型表示之间的联系

发布时间：2024年08月27日

`LLM理论` `人工智能`

> Implicit Geometry of Next-token Prediction: From Language Sparsity Patterns to Model Representations

# 摘要

> 在大规模文本语料库上进行的下一个词预测（NTP）已成为训练大型语言模型的主流方法。尽管如此，NTP如何影响语言模式与模型表示几何属性之间的映射仍是一个谜。我们提出了一种新颖的训练框架，将大型语言模型的训练视为稀疏概率标签向量上的软标签分类，并引入一种分析近似方法，以无限制地生成上下文嵌入。这一方法将NTP训练与对数域中的秩约束、核范数正则化优化相结合，为分析词和上下文嵌入的几何结构提供了框架。在庞大的嵌入空间中，我们观察到NTP倾向于学习具有稀疏加低秩结构的逻辑。稀疏部分捕捉了上下文-词对的共现频率，而正交低秩部分则随着训练的深入逐渐占据主导地位，仅依赖于共现矩阵的稀疏模式。结果是，当这些表示被投影到合适的子空间时，由相同下一词集跟随的上下文表示会发生崩溃，这一现象我们称之为子空间崩溃。我们在合成和小规模真实语言数据集上验证了这些发现。最后，我们提出了一些潜在的研究方向，旨在更深入地理解NTP在学习语言模式和规律性方面的作用。

> Next-token prediction (NTP) over large text corpora has become the go-to paradigm to train large language models. Yet, it remains unclear how NTP influences the mapping of linguistic patterns to geometric properties of the resulting model representations. We frame training of large language models as soft-label classification over sparse probabilistic label vectors, coupled with an analytical approximation that allows unrestricted generation of context embeddings. This approach links NTP training to rank-constrained, nuclear-norm regularized optimization in the logit domain, offering a framework for analyzing the geometry of word and context embeddings. In large embedding spaces, we find that NTP implicitly favors learning logits with a sparse plus low-rank structure. While the sparse component captures the co-occurrence frequency of context-word pairs, the orthogonal low-rank component, which becomes dominant as training progresses, depends solely on the sparsity pattern of the co-occurrence matrix. Consequently, when projected onto an appropriate subspace, representations of contexts that are followed by the same set of next-tokens collapse, a phenomenon we term subspace-collapse. We validate our findings on synthetic and small-scale real language datasets. Finally, we outline potential research directions aimed at deepening the understanding of NTP's influence on the learning of linguistic patterns and regularities.

[Arxiv](https://arxiv.org/abs/2408.15417)