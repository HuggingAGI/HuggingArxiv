# ResearchArena：评估大型语言模型在作为研究代理时，收集与组织信息的效能基准

发布时间：2024年06月12日

`Agent

这篇论文介绍了一个名为 ResearchArena 的基准，专门用于评估大型语言模型（LLMs）代理在学术调查任务中的能力。该基准特别关注代理在信息发现、信息选择和信息组织三个阶段的表现，并提供了一个包含大量学术论文的离线环境来评估代理的能力。这表明论文主要关注的是如何利用LLMs作为代理来执行特定任务，即学术调查，因此属于Agent分类。` `学术研究`

> ResearchArena: Benchmarking LLMs' Ability to Collect and Organize Information as Research Agents

# 摘要

> 大型语言模型（LLMs）在自然语言处理的多项任务中展现了卓越性能，但面对需要特定领域专业知识和高级分析技能的任务，如针对特定主题进行研究调查，仍显不足。为此，我们开发了ResearchArena，一个专门评估LLM代理进行学术调查能力的基准，这是学术研究的第一步。该基准将调查过程细分为三个阶段：信息发现、信息选择和信息组织，并构建了一个包含1200万篇学术论文和7900篇调查论文的离线环境，用以评估代理在定位相关材料、评估论文重要性及构建知识结构方面的能力。初步评估显示，现有基于LLM的方法在关键词检索技术面前表现不佳，揭示了未来研究的新方向。

> Large language models (LLMs) have exhibited remarkable performance across various tasks in natural language processing. Nevertheless, challenges still arise when these tasks demand domain-specific expertise and advanced analytical skills, such as conducting research surveys on a designated topic. In this research, we develop ResearchArena, a benchmark that measures LLM agents' ability to conduct academic surveys, an initial step of academic research process. Specifically, we deconstructs the surveying process into three stages 1) information discovery: locating relevant papers, 2) information selection: assessing papers' importance to the topic, and 3) information organization: organizing papers into meaningful structures. In particular, we establish an offline environment comprising 12.0M full-text academic papers and 7.9K survey papers, which evaluates agents' ability to locate supporting materials for composing the survey on a topic, rank the located papers based on their impact, and organize these into a hierarchical knowledge mind-map. With this benchmark, we conduct preliminary evaluations of existing techniques and find that all LLM-based methods under-performing when compared to basic keyword-based retrieval techniques, highlighting substantial opportunities for future research.

![ResearchArena：评估大型语言模型在作为研究代理时，收集与组织信息的效能基准](../../../paper_images/2406.10291/collection_typology.png)

![ResearchArena：评估大型语言模型在作为研究代理时，收集与组织信息的效能基准](../../../paper_images/2406.10291/x1.png)

![ResearchArena：评估大型语言模型在作为研究代理时，收集与组织信息的效能基准](../../../paper_images/2406.10291/x2.png)

![ResearchArena：评估大型语言模型在作为研究代理时，收集与组织信息的效能基准](../../../paper_images/2406.10291/x3.png)

![ResearchArena：评估大型语言模型在作为研究代理时，收集与组织信息的效能基准](../../../paper_images/2406.10291/x4.png)

[Arxiv](https://arxiv.org/abs/2406.10291)