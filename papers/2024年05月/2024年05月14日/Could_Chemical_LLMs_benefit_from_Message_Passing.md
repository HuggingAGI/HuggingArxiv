# 化学领域的 LLMs 是否能通过消息传递机制获得性能上的提升？这一问题引发了研究者们的广泛兴趣。消息传递作为一种信息交流的方式，在化学模型中可能扮演着关键角色，影响着模型的理解和预测能力。

发布时间：2024年05月14日

`LLM应用

这篇论文探讨了预训练语言模型（LLM）在分子文本处理中的应用，并提出了两种策略来研究信息融合对性能的影响。虽然它涉及到了模型融合和对比学习，但主要关注点是LLM在分子科学领域的应用，而不是Agent的行为、RAG（检索增强生成）的机制或LLM的理论基础。因此，最合适的分类是LLM应用。` `分子科学` `药物发现`

> Could Chemical LLMs benefit from Message Passing

# 摘要

> 预训练语言模型在分子文本处理上大放异彩，而消息传递神经网络则在分子科学领域展现了其坚韧与多才。然而，分子结构与其文本描述间的互动研究却寥寥无几。本文提出两种策略，旨在探究信息融合能否提升性能：一是对比学习，通过MPNN指导LM训练；二是模型融合，双剑合璧。实证分析揭示，在小型分子图谱上，这些融合策略超越了传统方法，但在大型图谱上，它们并未带来额外的性能提升。

> Pretrained language models (LMs) showcase significant capabilities in processing molecular text, while concurrently, message passing neural networks (MPNNs) demonstrate resilience and versatility in the domain of molecular science. Despite these advancements, we find there are limited studies investigating the bidirectional interactions between molecular structures and their corresponding textual representations. Therefore, in this paper, we propose two strategies to evaluate whether an information integration can enhance the performance: contrast learning, which involves utilizing an MPNN to supervise the training of the LM, and fusion, which exploits information from both models. Our empirical analysis reveals that the integration approaches exhibit superior performance compared to baselines when applied to smaller molecular graphs, while these integration approaches do not yield performance enhancements on large scale graphs.

[Arxiv](https://arxiv.org/abs/2405.08334)