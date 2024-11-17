# 针对任何低秩语言模型的模型窃取

发布时间：2024年11月11日

`LLM理论` `机器学习` `语言模型`

> Model Stealing for Any Low-Rank Language Model

# 摘要

> 模型窃取，指学习者通过精心挑选的查询来恢复未知模型，这在机器学习中是个关键问题，因其威胁到专有模型的安全和训练数据的隐私。近些年来，窃取大型语言模型（LLMs）备受关注。本文中，我们旨在通过研究一个简单且数学上易处理的设定，来构建对窃取语言模型的理论认知。我们对隐马尔可夫模型（HMMs）以及更普遍的低秩语言模型的窃取进行了研究。
  我们假定学习者在由 Kakade、Krishnamurthy、Mahajan 和 Zhang 引入的条件查询模型中操作。我们的主要成果是在条件查询模型中的一种高效算法，用于学习任何低秩分布。也就是说，我们的算法能够成功窃取任何输出分布为低秩的语言模型。这改进了 Kakade、Krishnamurthy、Mahajan 和 Zhang 之前的成果，他们之前的成果还要求未知分布具有高“保真度”，而这一属性仅在特定情况下成立。我们的算法有两个关键要点：其一，我们通过在一组指数大维度的向量中构建重心支撑来表示每个时间步的条件分布。其二，为从我们的表示中采样，我们迭代求解一系列凸优化问题，这些问题涉及相对熵中的投影，以避免在序列长度上的误差累积。这是个有趣的例子，至少在理论上，允许机器学习模型在推理时解决更复杂的问题，能大幅提升其性能。

> Model stealing, where a learner tries to recover an unknown model via carefully chosen queries, is a critical problem in machine learning, as it threatens the security of proprietary models and the privacy of data they are trained on. In recent years, there has been particular interest in stealing large language models (LLMs). In this paper, we aim to build a theoretical understanding of stealing language models by studying a simple and mathematically tractable setting. We study model stealing for Hidden Markov Models (HMMs), and more generally low-rank language models.
  We assume that the learner works in the conditional query model, introduced by Kakade, Krishnamurthy, Mahajan and Zhang. Our main result is an efficient algorithm in the conditional query model, for learning any low-rank distribution. In other words, our algorithm succeeds at stealing any language model whose output distribution is low-rank. This improves upon the previous result by Kakade, Krishnamurthy, Mahajan and Zhang, which also requires the unknown distribution to have high "fidelity", a property that holds only in restricted cases. There are two key insights behind our algorithm: First, we represent the conditional distributions at each timestep by constructing barycentric spanners among a collection of vectors of exponentially large dimension. Second, for sampling from our representation, we iteratively solve a sequence of convex optimization problems that involve projection in relative entropy to prevent compounding of errors over the length of the sequence. This is an interesting example where, at least theoretically, allowing a machine learning model to solve more complex problems at inference time can lead to drastic improvements in its performance.

[Arxiv](https://arxiv.org/abs/2411.07536)