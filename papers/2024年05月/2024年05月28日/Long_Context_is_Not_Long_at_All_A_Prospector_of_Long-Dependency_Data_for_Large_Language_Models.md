# 长依赖并非遥不可及：探索大型语言模型中的长上下文数据

发布时间：2024年05月28日

`LLM应用

这篇论文介绍了一种名为**ProLong**的数据挖掘框架，旨在提升大型语言模型（LLMs）的长上下文建模能力。该框架通过评估和筛选训练样本，以增强LLMs在处理长跨度上下文时的性能。这种方法直接应用于LLMs的训练和优化过程中，属于LLM应用的范畴。` `机器学习`

> Long Context is Not Long at All: A Prospector of Long-Dependency Data for Large Language Models

# 摘要

> 在大型语言模型（LLMs）的众多应用中，长上下文建模能力至关重要。然而，仅通过长上下文窗口直接训练LLMs，并不能充分提升这一能力，因为部分训练样本在长跨度上下文中缺乏强烈的语义联系。为此，本研究开发了一种名为**ProLong**的数据挖掘框架，它能为每个训练样本赋予一个长依赖性评分，进而筛选出那些更有助于提升LLMs长上下文建模能力的样本。我们首先利用delta困惑度来评估文档内文本段间的**依赖强度**，随后结合**依赖距离**调整这一指标，以考虑长上下文间的空间关系。最后，通过**依赖特异性**指标校正结果，避免重复模式带来的无关依赖。此外，我们还提出了一种随机抽样策略，以提高ProLong的计算效率。多基准测试的综合实验结果显示，ProLong能有效识别出具有长依赖性的文档，而基于这些文档训练的LLMs在长上下文建模方面表现出了显著的提升。

> Long-context modeling capabilities are important for large language models (LLMs) in various applications. However, directly training LLMs with long context windows is insufficient to enhance this capability since some training samples do not exhibit strong semantic dependencies across long contexts. In this study, we propose a data mining framework \textbf{ProLong} that can assign each training sample with a long dependency score, which can be used to rank and filter samples that are more advantageous for enhancing long-context modeling abilities in LLM training. Specifically, we first use delta perplexity scores to measure the \textit{Dependency Strength} between text segments in a given document. Then we refine this metric based on the \textit{Dependency Distance} of these segments to incorporate spatial relationships across long-contexts. Final results are calibrated with a \textit{Dependency Specificity} metric to prevent trivial dependencies introduced by repetitive patterns. Moreover, a random sampling approach is proposed to optimize the computational efficiency of ProLong. Comprehensive experiments on multiple benchmarks indicate that ProLong effectively identifies documents that carry long dependencies and LLMs trained on these documents exhibit significantly enhanced long-context modeling capabilities.

![长依赖并非遥不可及：探索大型语言模型中的长上下文数据](../../../paper_images/2405.17915/x1.png)

![长依赖并非遥不可及：探索大型语言模型中的长上下文数据](../../../paper_images/2405.17915/x2.png)

![长依赖并非遥不可及：探索大型语言模型中的长上下文数据](../../../paper_images/2405.17915/x3.png)

![长依赖并非遥不可及：探索大型语言模型中的长上下文数据](../../../paper_images/2405.17915/x4.png)

![长依赖并非遥不可及：探索大型语言模型中的长上下文数据](../../../paper_images/2405.17915/x5.png)

[Arxiv](https://arxiv.org/abs/2405.17915)