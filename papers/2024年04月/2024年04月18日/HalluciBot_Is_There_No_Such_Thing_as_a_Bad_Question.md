# HalluciBot：世上真有所谓的“坏问题”吗？

发布时间：2024年04月18日

`LLM应用` `人工智能`

> HalluciBot: Is There No Such Thing as a Bad Question?

# 摘要

> 幻觉一直是大型语言模型（LLMs）在机构采纳过程中面临的重大挑战。众多研究致力于分析生成后的阶段，包括通过反馈优化输出、审视对数输出值或从输出特征中提取线索。在此背景下，我们提出了 HalluciBot，这是一个模型，能够在 LLM 进行生成之前预测任何查询的幻觉概率。实质上，HalluciBot 在推理阶段不触发任何生成过程。为了验证 HalluciBot 的有效性，我们采用了多智能体蒙特卡洛模拟技术，并通过查询扰动器在训练阶段为每个查询生成 n 个变体。查询扰动器的设计灵感来源于我们对幻觉的新定义——“真实幻觉”。我们的训练方法针对 369,837 个查询的训练语料库，生成了 2,219,022 个预测估计，覆盖了 13 个多样化的数据集和 3 种问答情境。HalluciBot 能够预测幻觉的二元和多类概率，为评估查询的质量和其幻觉倾向提供了一种方法。因此，HalluciBot 不仅为在生成前修订或取消查询提供了可能，避免了不必要的计算资源浪费，还为评估用户对幻觉查询的责任提供了清晰的度量手段。

> Hallucination continues to be one of the most critical challenges in the institutional adoption journey of Large Language Models (LLMs). In this context, an overwhelming number of studies have focused on analyzing the post-generation phase - refining outputs via feedback, analyzing logit output values, or deriving clues via the outputs' artifacts. We propose HalluciBot, a model that predicts the probability of hallucination $\textbf{before generation}$, for any query imposed to an LLM. In essence, HalluciBot does not invoke any generation during inference. To derive empirical evidence for HalluciBot, we employ a Multi-Agent Monte Carlo Simulation using a Query Perturbator to craft $n$ variations per query at train time. The construction of our Query Perturbator is motivated by our introduction of a new definition of hallucination - $\textit{truthful hallucination}$. Our training methodology generated 2,219,022 estimates for a training corpus of 369,837 queries, spanning 13 diverse datasets and 3 question-answering scenarios. HalluciBot predicts both binary and multi-class probabilities of hallucination, enabling a means to judge the query's quality with regards to its propensity to hallucinate. Therefore, HalluciBot paves the way to revise or cancel a query before generation and the ensuing computational waste. Moreover, it provides a lucid means to measure user accountability for hallucinatory queries.

![HalluciBot：世上真有所谓的“坏问题”吗？](../../../paper_images/2404.12535/x1.png)

![HalluciBot：世上真有所谓的“坏问题”吗？](../../../paper_images/2404.12535/x2.png)

![HalluciBot：世上真有所谓的“坏问题”吗？](../../../paper_images/2404.12535/x3.png)

![HalluciBot：世上真有所谓的“坏问题”吗？](../../../paper_images/2404.12535/x4.png)

[Arxiv](https://arxiv.org/abs/2404.12535)