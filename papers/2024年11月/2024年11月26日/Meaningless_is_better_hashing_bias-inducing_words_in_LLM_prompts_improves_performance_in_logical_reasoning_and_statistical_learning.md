# “无意义反而更好”：在 LLM 提示中对那些会导致偏差的词进行哈希处理，能够提升逻辑推理和统计学习的表现。

发布时间：2024年11月26日

`LLM应用` `语言模型` `认知科学`

> Meaningless is better: hashing bias-inducing words in LLM prompts improves performance in logical reasoning and statistical learning

# 摘要

> 这篇论文引入了一种新方法，叫做“哈希”，就是在大型语言模型（LLMs）里，用类似哈希的无意义标识符去掩盖那些可能引发偏差的词，从而降低认知偏差和对外部知识的依赖。这个方法在三组总共 490 个提示的实验中进行了测试。通过卡方检验的统计分析显示，在涵盖 LLama、ChatGPT、Copilot、Gemini 和 Mixtral 模型的所有测试场景中都有显著改善。在第一个实验里，哈希降低了“琳达”问题修改版中用于评估对认知偏差敏感性的谬误率。在第二个实验中，它提升了频繁项集提取任务中的 LLM 结果。在第三个实验中，我们发现当“琳达”问题以表格形式而非文本形式呈现时，哈希依然有效，这意味着该技术在各种输入表示中都行得通。总之，这个方法能减少偏差、整合外部知识。不过，虽然偏差减少了，但不同类型的 LLM 模型中幻觉率的降低情况并不一致。这些发现表明，掩盖引发偏差的术语能提升 LLM 的性能，只是其有效性因模型和任务而异。

> This paper introduces a novel method, referred to as "hashing", which involves masking potentially bias-inducing words in large language models (LLMs) with hash-like meaningless identifiers to reduce cognitive biases and reliance on external knowledge. The method was tested across three sets of experiments involving a total of 490 prompts. Statistical analysis using chi-square tests showed significant improvements in all tested scenarios, which covered LLama, ChatGPT, Copilot, Gemini and Mixtral models. In the first experiment, hashing decreased the fallacy rate in a modified version of the "Linda" problem aimed at evaluating susceptibility to cognitive biases. In the second experiment, it improved LLM results on the frequent itemset extraction task. In the third experiment, we found hashing is also effective when the Linda problem is presented in a tabular format rather than text, indicating that the technique works across various input representations. Overall, the method was shown to improve bias reduction and incorporation of external knowledge. Despite bias reduction, hallucination rates were inconsistently reduced across types of LLM models. These findings suggest that masking bias-inducing terms can improve LLM performance, although its effectiveness is model- and task-dependent.

[Arxiv](https://arxiv.org/abs/2411.17304)