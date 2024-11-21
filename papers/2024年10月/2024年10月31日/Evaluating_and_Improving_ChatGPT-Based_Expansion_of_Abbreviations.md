# 评估并改进基于 ChatGPT 的缩写扩展情况

发布时间：2024年10月31日

`LLM应用` `软件工程` `软件开发`

> Evaluating and Improving ChatGPT-Based Expansion of Abbreviations

# 摘要

> 源代码标识符往往包含缩写。这些缩写可能降低源代码的可读性，从而妨碍软件应用的维护。正因如此，人们渴望有准确且自动化的方法来扩展源代码中的缩写，缩写扩展也已被深入探究。然而，就我们所知，现有的大多数方法都是启发式的，它们中没有一个运用了深度学习技术，更别提最先进的大型语言模型（LLMs）了。LLMs 在各类软件工程任务中展现出前沿的性能，所以它有自动扩展缩写的潜力。为此，在本文中，我们针对基于 LLM 的缩写扩展展开了首次实证研究。我们在一个公共基准上的评估结果显示，ChatGPT 的准确性远低于最先进的方法，精度和召回率分别降低了 28.2％和 27.8％。我们手动分析了失败案例，找出了失败的根本原因：1. 缺乏上下文 2. 无法识别缩写。针对第一个原因，我们探究了各种上下文的影响，发现周边的源代码是最佳选择。针对第二个原因，我们设计了一种迭代方法，用于识别并在提示中明确标记遗漏的缩写。最后，我们提出了一个后置条件检查，以排除违反常识的不正确扩展。所有这些措施共同使得基于 ChatGPT 的缩写扩展能与最先进的方法媲美，同时避免了最先进方法所必需的昂贵的源代码解析和深度分析。

> Source code identifiers often contain abbreviations. Such abbreviations may reduce the readability of the source code, which in turn hinders the maintenance of the software applications. To this end, accurate and automated approaches to expanding abbreviations in source code are desirable and abbreviation expansion has been intensively investigated. However, to the best of our knowledge, most existing approaches are heuristics, and none of them has even employed deep learning techniques, let alone the most advanced large language models (LLMs). LLMs have demonstrated cutting-edge performance in various software engineering tasks, and thus it has the potential to expand abbreviation automatically. To this end, in this paper, we present the first empirical study on LLM-based abbreviation expansion. Our evaluation results on a public benchmark suggest that ChatGPT is substantially less accurate than the state-of-the-art approach, reducing precision and recall by 28.2\% and 27.8\%, respectively. We manually analyzed the failed cases, and discovered the root causes for the failures: 1) Lack of contexts and 2) Inability to recognize abbreviations. In response to the first cause, we investigated the effect of various contexts and found surrounding source code is the best selection. In response to the second cause, we designed an iterative approach that identifies and explicitly marks missed abbreviations in prompts. Finally, we proposed a post-condition checking to exclude incorrect expansions that violate commonsense. All such measures together make ChatGPT-based abbreviation expansion comparable to the state of the art while avoiding expensive source code parsing and deep analysis that are indispensable for state-of-the-art approaches.

[Arxiv](https://arxiv.org/abs/2410.23866)