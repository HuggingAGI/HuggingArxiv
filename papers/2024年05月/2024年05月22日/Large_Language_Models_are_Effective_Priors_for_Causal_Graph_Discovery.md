# 大型语言模型作为因果图发现的先验，展现出其有效性。

发布时间：2024年05月22日

`LLM应用

这篇论文主要探讨了如何利用大型语言模型（LLMs）作为先验信息的来源，以辅助因果图的发现。研究内容包括评估LLM在因果图发现中的表现、设计提示以引导模型预设因果图结构，以及开发算法将LLM的先验知识融入图发现过程中。这些应用层面的研究展示了LLMs在特定任务中的实际应用和改进效果，因此属于LLM应用分类。` `因果分析` `人工智能`

> Large Language Models are Effective Priors for Causal Graph Discovery

# 摘要

> 通过融合专家的背景知识，我们能更精准地从观察中揭示因果结构。近期，大型语言模型（LLMs）因其查询成本低于人类专家，逐渐成为先验信息的新来源。本研究首先提出了一套独立于下游算法的评估LLM对因果图发现判断的指标。接着，我们系统探讨了一系列提示设计，使模型能预设因果图的结构。最后，我们开发了一种将LLM先验融入图发现算法的方法，证实其在提升常识基准性能，尤其是在确定边方向性方面，具有显著效果。我们的研究不仅揭示了LLMs在这一领域的潜力，也指出了其局限性。

> Causal structure discovery from observations can be improved by integrating background knowledge provided by an expert to reduce the hypothesis space. Recently, Large Language Models (LLMs) have begun to be considered as sources of prior information given the low cost of querying them relative to a human expert. In this work, firstly, we propose a set of metrics for assessing LLM judgments for causal graph discovery independently of the downstream algorithm. Secondly, we systematically study a set of prompting designs that allows the model to specify priors about the structure of the causal graph. Finally, we present a general methodology for the integration of LLM priors in graph discovery algorithms, finding that they help improve performance on common-sense benchmarks and especially when used for assessing edge directionality. Our work highlights the potential as well as the shortcomings of the use of LLMs in this problem space.

[Arxiv](https://arxiv.org/abs/2405.13551)