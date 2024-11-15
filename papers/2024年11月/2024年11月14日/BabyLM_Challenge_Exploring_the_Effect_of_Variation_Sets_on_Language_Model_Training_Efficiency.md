# BabyLM 挑战：探究变异集对语言模型训练效率的作用

发布时间：2024年11月14日

`LLM应用` `语言模型` `儿童语言`

> BabyLM Challenge: Exploring the Effect of Variation Sets on Language Model Training Efficiency

# 摘要

> 尽管当下的大型语言模型成绩斐然，但其数据效率仍是有待攻克的难题。近来有人指出，面向儿童的语言（CDS）能够提升基于 Transformer 神经网络的现代语言模型的训练数据效率。然而，CDS 的哪些具体特性能有效用于训练这些模型，目前尚不明确。在 BabyLM 挑战的情境中，我们着眼于变异集（VSs），也就是那些在 CDS 中随处可见的、由一连串表达相近意图但用词和结构稍有差异的话语所组成的集合。为评估 VSs 对训练数据效率的作用，我们用不同比例的人工 VSs 来扩充 CDS 数据，并利用这些数据集训练自回归模型 GPT-2。我们发现，VSs 的最佳比例取决于评估基准：BLiMP 和 GLUE 分数因 VSs 的存在而获益，EWOK 分数却并非如此。另外，结果会因诸如轮次数量和话语呈现顺序等多种因素而有所不同。总之，这些发现表明 VSs 对语言模型可能具有有益影响，同时也为进一步探索留下了余地。

> While current large language models have achieved a remarkable success, their data efficiency remains a challenge to overcome. Recently it has been suggested that child-directed speech (CDS) can improve training data efficiency of modern language models based on Transformer neural networks. However, it is not yet understood which specific properties of CDS are effective for training these models. In the context of the BabyLM Challenge, we focus on Variation Sets (VSs), sets of consecutive utterances expressing a similar intent with slightly different words and structures, which are ubiquitous in CDS. To assess the impact of VSs on training data efficiency, we augment CDS data with different proportions of artificial VSs and use these datasets to train an auto-regressive model, GPT-2. We find that the best proportion of VSs depends on the evaluation benchmark: BLiMP and GLUE scores benefit from the presence of VSs, but EWOK scores do not. Additionally, the results vary depending on multiple factors such as the number of epochs and the order of utterance presentation. Taken together, these findings suggest that VSs can have a beneficial influence on language models, while leaving room for further investigation.

[Arxiv](https://arxiv.org/abs/2411.09587)