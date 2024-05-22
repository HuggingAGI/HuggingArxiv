# 大规模语言模型中的定向度量结构探索

发布时间：2024年05月20日

`LLM理论

这篇论文深入探讨了大型语言模型（LLM）的数学结构，特别是通过分析文本扩展的条件概率分布，并使用-log概率来揭示文本空间的度量结构。论文中构建了度量多面体，并通过Yoneda嵌入实现等距映射，探讨了文本向量的生成以及与文本扩展相关的对偶性定理。这些内容涉及LLM的理论基础和数学分析，因此属于LLM理论分类。` `数学理论`

> Directed Metric Structures arising in Large Language Models

# 摘要

> 大型语言模型，作为变换器神经网络，被训练来预测语料库中给定文本的下一个单词，确保最可能的预测与训练文本中的实际单词一致。本文深入探讨了这种文本扩展的条件概率分布所隐含的数学结构。通过将视角从概率转向-log概率，我们揭示了子文本顺序如何完全编码在文本空间$\mathcal{L}$上的-log概率所定义的度量结构中。我们构建了度量多面体$P(\mathcal{L})$，并通过Yoneda嵌入实现等距映射，将文本映射至特定极值射线的生成元。我们阐释了$P(\mathcal{L})$是这些生成元的$(\min,+)$线性跨度，并满足一组$(\min+)$线性方程。进一步，我们证明了$P(\mathcal{L})$能够兼容新增文本，并据此近似出文本向量，作为该文本中单词向量的玻尔兹曼加权线性组合。我们还揭示了一个对偶性定理，表明文本扩展与限制虽表面迥异，却能生成等距的多面体。此外，我们证明了$P(\mathcal{L})$是Isbell完备化（即文本极值射线生成元的$(\max,+)$跨度）的格闭包。所有这些构造在范畴论中均有对应，尽管本文未直接运用范畴论。范畴论的解释在附录中简要阐述。最后，我们探讨了语法到语义问题如何契合于一个广为人知的数学对偶性框架。

> Large Language Models are transformer neural networks which are trained to produce a probability distribution on the possible next words to given texts in a corpus, in such a way that the most likely word predicted is the actual word in the training text. In this paper we find what is the mathematical structure defined by such conditional probability distributions of text extensions. Changing the view point from probabilities to -log probabilities we observe that the subtext order is completely encoded in a metric structure defined on the space of texts $\mathcal{L}$, by -log probabilities. We then construct a metric polyhedron $P(\mathcal{L})$ and an isometric embedding (called Yoneda embedding) of $\mathcal{L}$ into $P(\mathcal{L})$ such that texts map to generators of certain special extremal rays. We explain that $P(\mathcal{L})$ is a $(\min,+)$ (tropical) linear span of these extremal ray generators. The generators also satisfy a system of $(\min+)$ linear equations. We then show that $P(\mathcal{L})$ is compatible with adding more text and from this we derive an approximation of a text vector as a Boltzmann weighted linear combination of the vectors for words in that text. We then prove a duality theorem showing that texts extensions and text restrictions give isometric polyhedra (even though they look a priory very different). Moreover we prove that $P(\mathcal{L})$ is the lattice closure of (a version of) the so called, Isbell completion of $\mathcal{L}$ which turns out to be the $(\max,+)$ span of the text extremal ray generators. All constructions have interpretations in category theory but we don't use category theory explicitly. The categorical interpretations are briefly explained in an appendix. In the final appendix we describe how the syntax to semantics problem could fit in a general well known mathematical duality.

[Arxiv](https://arxiv.org/abs/2405.12264)