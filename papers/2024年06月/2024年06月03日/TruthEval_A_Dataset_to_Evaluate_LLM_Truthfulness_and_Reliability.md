# TruthEval：专为评估大型语言模型真实性与可靠性而设计的数据集

发布时间：2024年06月03日

`LLM应用

这篇论文摘要讨论了大型语言模型（LLM）的评估问题，特别是通过一套名为TruthEval的敏感话题陈述来评估LLM的能力。这种方法旨在更全面地反映LLM的能力，并揭示了LLM在处理简单问题时的局限性。这种评估方法和发现直接关联到LLM的应用层面，即如何更好地理解和改进LLM在实际应用中的表现。因此，这篇论文应归类为LLM应用。` `人工智能评估` `敏感话题处理`

> TruthEval: A Dataset to Evaluate LLM Truthfulness and Reliability

# 摘要

> 大型语言模型（LLM）的评估是当前研究的热点，但现有基准测试未能全面反映其能力。我们精心挑选了一套名为TruthEval的敏感话题陈述，用于评估LLM。这些陈述经过人工审核，确保真实性。我们通过这些数据进行初步分析，发现LLM在处理简单问题时表现不佳，揭示了它们在理解基础问题上的局限性。

> Large Language Model (LLM) evaluation is currently one of the most important areas of research, with existing benchmarks proving to be insufficient and not completely representative of LLMs' various capabilities. We present a curated collection of challenging statements on sensitive topics for LLM benchmarking called TruthEval. These statements were curated by hand and contain known truth values. The categories were chosen to distinguish LLMs' abilities from their stochastic nature. We perform some initial analyses using this dataset and find several instances of LLMs failing in simple tasks showing their inability to understand simple questions.

![TruthEval：专为评估大型语言模型真实性与可靠性而设计的数据集](../../../paper_images/2406.01855/x1.png)

[Arxiv](https://arxiv.org/abs/2406.01855)