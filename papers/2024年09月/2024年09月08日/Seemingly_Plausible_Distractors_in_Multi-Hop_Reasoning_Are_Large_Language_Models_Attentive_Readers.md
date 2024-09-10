# 多跳推理中的合理干扰项：大型语言模型是否具备专注阅读的能力？

发布时间：2024年09月08日

`LLM理论` `人工智能`

> Seemingly Plausible Distractors in Multi-Hop Reasoning: Are Large Language Models Attentive Readers?

# 摘要

> 最先进的 LLM 具备多种能力，从阅读理解到高级数学和科学知识。本文聚焦于其多跳推理能力，即整合多源信息的能力。鉴于现有基准中的简化线索可能使模型绕过推理要求，我们研究了 LLM 是否利用这些线索。结果显示，LLM 确实以更微妙的方式绕过了多跳推理要求。基于此，我们设计了一个挑战性的多跳推理基准，生成看似合理但最终错误的推理链。评估显示，面对这些替代方案时，LLM 的 F1 分数下降了高达 45%。深入分析表明，尽管 LLM 忽略误导性词汇线索，但误导性推理路径仍构成重大挑战。

> State-of-the-art Large Language Models (LLMs) are accredited with an increasing number of different capabilities, ranging from reading comprehension, over advanced mathematical and reasoning skills to possessing scientific knowledge. In this paper we focus on their multi-hop reasoning capability: the ability to identify and integrate information from multiple textual sources.
  Given the concerns with the presence of simplifying cues in existing multi-hop reasoning benchmarks, which allow models to circumvent the reasoning requirement, we set out to investigate, whether LLMs are prone to exploiting such simplifying cues. We find evidence that they indeed circumvent the requirement to perform multi-hop reasoning, but they do so in more subtle ways than what was reported about their fine-tuned pre-trained language model (PLM) predecessors. Motivated by this finding, we propose a challenging multi-hop reasoning benchmark, by generating seemingly plausible multi-hop reasoning chains, which ultimately lead to incorrect answers. We evaluate multiple open and proprietary state-of-the-art LLMs, and find that their performance to perform multi-hop reasoning is affected, as indicated by up to 45% relative decrease in F1 score when presented with such seemingly plausible alternatives. We conduct a deeper analysis and find evidence that while LLMs tend to ignore misleading lexical cues, misleading reasoning paths indeed present a significant challenge.

[Arxiv](https://arxiv.org/abs/2409.05197)