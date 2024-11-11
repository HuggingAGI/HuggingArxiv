# 文本预处理管道如何影响本体句法匹配？

发布时间：2024年11月06日

`LLM应用` `本体匹配` `文本预处理`

> How Does A Text Preprocessing Pipeline Affect Ontology Syntactic Matching?

# 摘要

> 通用的文本预处理管道，包括标记化、规范化、停用词去除和词干提取/词形还原，已在许多本体匹配（OM）系统中实现。然而，文本预处理缺乏标准化导致映射结果的多样性。在本文中，我们研究了文本预处理管道在句法层面上对 OM 任务的影响。我们对 8 个本体对齐评估倡议（OAEI）跟踪库的 49 个不同对齐进行的实验表明：（1）标记化和规范化目前比停用词去除和词干提取/词形还原更有效；（2）词形还原和词干提取的选择因任务而异。我们建议单独使用词形还原或词干提取，并进行事后修正。我们发现（3）波特词干提取器和雪球词干提取器的表现优于兰卡斯特词干提取器；（4）词性标注对词形还原没有帮助。为了修复在 OM 任务中效果不佳的停用词去除和词干提取/词形还原，我们提出了一种新颖的基于上下文的管道修复方法，显著提高了匹配的正确性和整体匹配性能。我们还讨论了在大型语言模型（LLM）的新时代中使用文本预处理管道的情况。

> The generic text preprocessing pipeline, comprising Tokenisation, Normalisation, Stop Words Removal, and Stemming/Lemmatisation, has been implemented in many ontology matching (OM) systems. However, the lack of standardisation in text preprocessing creates diversity in mapping results. In this paper, we investigate the effect of the text preprocessing pipeline on OM tasks at syntactic levels. Our experiments on 8 Ontology Alignment Evaluation Initiative (OAEI) track repositories with 49 distinct alignments indicate: (1) Tokenisation and Normalisation are currently more effective than Stop Words Removal and Stemming/Lemmatisation; and (2) The selection of Lemmatisation and Stemming is task-specific. We recommend standalone Lemmatisation or Stemming with post-hoc corrections. We find that (3) Porter Stemmer and Snowball Stemmer perform better than Lancaster Stemmer; and that (4) Part-of-Speech (POS) Tagging does not help Lemmatisation. To repair less effective Stop Words Removal and Stemming/Lemmatisation used in OM tasks, we propose a novel context-based pipeline repair approach that significantly improves matching correctness and overall matching performance. We also discuss the use of text preprocessing pipeline in the new era of large language models (LLMs).

[Arxiv](https://arxiv.org/abs/2411.03962)