# 利用 LLMs 假设缺失的因果变量

发布时间：2024年09月04日

`LLM应用` `科学研究` `人工智能`

> Hypothesizing Missing Causal Variables with LLMs

# 摘要

> 科学发现是推动人类智慧前行的引擎，它通过假设提出、实验设计、数据分析和假设迭代修正的循环过程实现。这一过程虽关键，但成本高昂，且高度依赖科学家的专业知识来提出假设并推动科学探索。因果关系的建立是这一过程中的核心。受此启发，我们提出了一项新任务：输入为包含缺失变量的部分因果图，输出则是关于这些缺失变量的假设，以完善该图。我们设计了一个包含不同难度和知识假设的基准测试。随着大型语言模型（LLM）在科学发现中的应用日益广泛，我们在此基准上测试了开源与封闭模型。结果显示，LLM在推测因果关系中的中介变量方面表现出色，但在直接推测因果和结果变量方面则稍显不足。此外，一些开源模型甚至在某些测试中超越了GPT-4。

> Scientific discovery is a catalyst for human intellectual advances, driven by the cycle of hypothesis generation, experimental design, data evaluation, and iterative assumption refinement. This process, while crucial, is expensive and heavily dependent on the domain knowledge of scientists to generate hypotheses and navigate the scientific cycle. Central to this is causality, the ability to establish the relationship between the cause and the effect. Motivated by the scientific discovery process, in this work, we formulate a novel task where the input is a partial causal graph with missing variables, and the output is a hypothesis about the missing variables to complete the partial graph. We design a benchmark with varying difficulty levels and knowledge assumptions about the causal graph. With the growing interest in using Large Language Models (LLMs) to assist in scientific discovery, we benchmark open-source and closed models on our testbed. We show the strong ability of LLMs to hypothesize the mediation variables between a cause and its effect. In contrast, they underperform in hypothesizing the cause and effect variables themselves. We also observe surprising results where some of the open-source models outperform the closed GPT-4 model.

[Arxiv](https://arxiv.org/abs/2409.02604)