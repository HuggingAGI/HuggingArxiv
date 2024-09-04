# 革新陈旧嵌入：利用校正器网络提升密集检索器的训练效果

发布时间：2024年09月03日

`LLM应用` `信息检索`

> A Fresh Take on Stale Embeddings: Improving Dense Retriever Training with Corrector Networks

# 摘要

> 在密集检索领域，深度编码器不仅为输入和目标生成嵌入，还利用softmax函数在大规模候选目标（如信息检索中的文本段落）上构建分布。然而，随着目标数量的激增、目标编码器计算成本的增加以及因持续训练导致的目标嵌入缓存过时，训练这些编码器变得愈发困难。为此，我们提出了一种简便且极具扩展性的解决方案：通过训练一个小型参数校正网络，调整那些过时的缓存目标嵌入，从而实现精确的softmax近似，并有效采样最新且高得分的“硬负例”。我们还从理论上探讨了所提目标校正器的泛化能力，分析了网络复杂度、缓存表示的陈旧度与训练数据量之间的关系。实验结果显示，在大型密集检索基准数据集及检索增强型语言模型的问答任务中，即便在训练期间不对目标嵌入进行额外更新，我们的方法依然能与当前最佳技术相媲美，同时大幅降低重新嵌入的计算成本，达到4至80倍的效率提升。

> In dense retrieval, deep encoders provide embeddings for both inputs and targets, and the softmax function is used to parameterize a distribution over a large number of candidate targets (e.g., textual passages for information retrieval). Significant challenges arise in training such encoders in the increasingly prevalent scenario of (1) a large number of targets, (2) a computationally expensive target encoder model, (3) cached target embeddings that are out-of-date due to ongoing training of target encoder parameters. This paper presents a simple and highly scalable response to these challenges by training a small parametric corrector network that adjusts stale cached target embeddings, enabling an accurate softmax approximation and thereby sampling of up-to-date high scoring "hard negatives." We theoretically investigate the generalization properties of our proposed target corrector, relating the complexity of the network, staleness of cached representations, and the amount of training data. We present experimental results on large benchmark dense retrieval datasets as well as on QA with retrieval augmented language models. Our approach matches state-of-the-art results even when no target embedding updates are made during training beyond an initial cache from the unsupervised pre-trained model, providing a 4-80x reduction in re-embedding computational cost.

[Arxiv](https://arxiv.org/abs/2409.01890)