# TruthEval：评估大型语言模型真实性与可靠性的数据集

发布时间：2024年06月03日

`LLM应用

理由：这篇论文关注的是大型语言模型（LLM）的评估问题，特别是通过一个名为TruthEval的数据集来评估LLM在处理敏感话题陈述时的表现。这种评估方法直接应用于LLM的实际使用场景中，以检验其处理特定类型信息的能力，因此属于LLM应用类别。论文并未深入探讨LLM的理论基础或机制，也没有涉及Agent或RAG的相关内容。` `模型评估`

> TruthEval: A Dataset to Evaluate LLM Truthfulness and Reliability

# 摘要

> 大型语言模型（LLM）的评估是当前研究的热点，但现有基准未能全面反映其能力。我们精心挑选了一套名为TruthEval的敏感话题陈述，用于评估LLM。这些陈述经过人工筛选，确保了真实性。我们通过这个数据集初步分析，揭示了LLM在处理简单问题时的不足，表明它们在理解基本问题上的局限性。

> Large Language Model (LLM) evaluation is currently one of the most important areas of research, with existing benchmarks proving to be insufficient and not completely representative of LLMs' various capabilities. We present a curated collection of challenging statements on sensitive topics for LLM benchmarking called TruthEval. These statements were curated by hand and contain known truth values. The categories were chosen to distinguish LLMs' abilities from their stochastic nature. We perform some initial analyses using this dataset and find several instances of LLMs failing in simple tasks showing their inability to understand simple questions.

![TruthEval：评估大型语言模型真实性与可靠性的数据集](../../../paper_images/2406.01855/x1.png)

[Arxiv](https://arxiv.org/abs/2406.01855)