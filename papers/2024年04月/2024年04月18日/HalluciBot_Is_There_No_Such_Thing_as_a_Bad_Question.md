# HalluciBot：世上真有所谓的“坏问题”吗？

发布时间：2024年04月18日

`LLM应用` `人工智能`

> HalluciBot: Is There No Such Thing as a Bad Question?

# 摘要

> 幻觉在大型语言模型（LLMs）的机构采纳之路上依旧是一个重大挑战。在此背景下，众多研究致力于分析生成后阶段——无论是通过反馈优化结果、解析对数输出值，还是从输出特征中寻找线索。我们提出了HalluciBot，这是一个在向LLM提出任何查询之前就能预测幻觉概率的模型。实质上，HalluciBot在推理时不进行任何生成操作。为了验证HalluciBot的有效性，我们采用了多智能体蒙特卡洛模拟，并通过查询扰动器在训练阶段为每个查询生成n个变体。这一查询扰动器的设计灵感来源于我们对幻觉的新定义——“真实幻觉”。我们的训练方法针对一个包含369,837个查询的训练语料库，生成了2,219,022个估计值，覆盖了13个多样化的数据集和3种问答情境。HalluciBot能够预测幻觉的二元和多类概率，从而评估查询可能导致幻觉的风险。这使得HalluciBot能够在生成之前对查询进行修订或取消，避免了不必要的计算资源浪费。同时，它还提供了一种明确的方法来评估用户对可能导致幻觉的查询的责任。

> Hallucination continues to be one of the most critical challenges in the institutional adoption journey of Large Language Models (LLMs). In this context, an overwhelming number of studies have focused on analyzing the post-generation phase - refining outputs via feedback, analyzing logit output values, or deriving clues via the outputs' artifacts. We propose HalluciBot, a model that predicts the probability of hallucination $\textbf{before generation}$, for any query imposed to an LLM. In essence, HalluciBot does not invoke any generation during inference. To derive empirical evidence for HalluciBot, we employ a Multi-Agent Monte Carlo Simulation using a Query Perturbator to craft $n$ variations per query at train time. The construction of our Query Perturbator is motivated by our introduction of a new definition of hallucination - $\textit{truthful hallucination}$. Our training methodology generated 2,219,022 estimates for a training corpus of 369,837 queries, spanning 13 diverse datasets and 3 question-answering scenarios. HalluciBot predicts both binary and multi-class probabilities of hallucination, enabling a means to judge the query's quality with regards to its propensity to hallucinate. Therefore, HalluciBot paves the way to revise or cancel a query before generation and the ensuing computational waste. Moreover, it provides a lucid means to measure user accountability for hallucinatory queries.

![HalluciBot：世上真有所谓的“坏问题”吗？](../../../paper_images/2404.12535/x1.png)

![HalluciBot：世上真有所谓的“坏问题”吗？](../../../paper_images/2404.12535/x2.png)

![HalluciBot：世上真有所谓的“坏问题”吗？](../../../paper_images/2404.12535/x3.png)

![HalluciBot：世上真有所谓的“坏问题”吗？](../../../paper_images/2404.12535/x4.png)

[Arxiv](https://arxiv.org/abs/2404.12535)