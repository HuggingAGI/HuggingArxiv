# 引导大型语言模型利用自身信号界定知识边界

发布时间：2024年06月16日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）中的“幻觉”问题，即模型在知识边界上的训练不足导致的内容虚构现象。论文提出了一种名为CoKE的方法，旨在帮助LLMs识别并表达自己的知识边界，从而减少幻觉的发生。这种方法通过探查LLMs的自信程度来揭示其知识边界，并利用这些信息来引导模型更好地表达其知识限制。这是一个理论性的研究，因为它关注的是LLMs的内部机制和改进方法，而不是直接的应用或实际的Agent行为。因此，它属于LLM理论分类。` `人工智能`

> Teaching Large Language Models to Express Knowledge Boundary from Their Own Signals

# 摘要

> 大型语言模型（LLMs）虽成就斐然，但其偶尔的内容虚构——我们称之为“幻觉”——却成了应用的绊脚石。这种幻觉源于LLMs在知识边界上的训练不足，导致它们难以坦承无知。本文致力于让LLMs学会识别并表达自己的知识边界，以减少在无知时虚构信息的幻觉。我们提出的CoKE方法，首先通过一系列问题来探查LLMs的自信程度，进而揭示其知识边界，然后利用这些探查结果来引导LLMs表达其知识边界。实验证明，CoKE使LLMs在回答已知问题的同时，能够拒绝未知问题，显著提升了其在特定领域及跨领域的表现。

> Large language models (LLMs) have achieved great success, but their occasional content fabrication, or hallucination, limits their practical application. Hallucination arises because LLMs struggle to admit ignorance due to inadequate training on knowledge boundaries. We call it a limitation of LLMs that they can not accurately express their knowledge boundary, answering questions they know while admitting ignorance to questions they do not know. In this paper, we aim to teach LLMs to recognize and express their knowledge boundary, so they can reduce hallucinations caused by fabricating when they do not know. We propose CoKE, which first probes LLMs' knowledge boundary via internal confidence given a set of questions, and then leverages the probing results to elicit the expression of the knowledge boundary. Extensive experiments show CoKE helps LLMs express knowledge boundaries, answering known questions while declining unknown ones, significantly improving in-domain and out-of-domain performance.

![引导大型语言模型利用自身信号界定知识边界](../../../paper_images/2406.10881/x1.png)

![引导大型语言模型利用自身信号界定知识边界](../../../paper_images/2406.10881/x2.png)

![引导大型语言模型利用自身信号界定知识边界](../../../paper_images/2406.10881/x3.png)

![引导大型语言模型利用自身信号界定知识边界](../../../paper_images/2406.10881/x4.png)

[Arxiv](https://arxiv.org/abs/2406.10881)