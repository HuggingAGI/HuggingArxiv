# TREC 2024 RAG 赛道采用 AutoNuggetizer 框架的初始金块评估结果

发布时间：2024年11月14日

`RAG` `信息检索`

> Initial Nugget Evaluation Results for the TREC 2024 RAG Track with the AutoNuggetizer Framework

# 摘要

> 本报告初步呈现了 TREC 2024 检索增强生成（RAG）赛道的部分成果。我们已认定 RAG 评估是信息获取（乃至更广泛的自然语言处理和人工智能）持续发展的阻碍，期望能为攻克此领域的诸多难题贡献力量。我们在这项工作中探索的核心设想是，最初为 2003 年 TREC 问答赛道开发的金块评估方法，为评估 RAG 系统奠定了坚实基础。正因如此，我们致力于“重构”这一方法，尤其是运用大型语言模型来自动创建金块并将其自动分配给系统答案。我们将其称为 AutoNuggetizer 框架。在 TREC 的设定中，我们能够将全自动流程与手动流程进行校准，手动流程中，金块由人工评估员半手动创建，再手动分配给系统答案。基于 45 次运行中 21 个主题的初步结果，我们发现全自动金块评估所得分数与人工评估员（大多）手动金块评估之间存在显著的相关性。这表明我们的全自动评估流程可用于引导 RAG 系统的未来迭代。

> This report provides an initial look at partial results from the TREC 2024 Retrieval-Augmented Generation (RAG) Track. We have identified RAG evaluation as a barrier to continued progress in information access (and more broadly, natural language processing and artificial intelligence), and it is our hope that we can contribute to tackling the many challenges in this space. The central hypothesis we explore in this work is that the nugget evaluation methodology, originally developed for the TREC Question Answering Track in 2003, provides a solid foundation for evaluating RAG systems. As such, our efforts have focused on "refactoring" this methodology, specifically applying large language models to both automatically create nuggets and to automatically assign nuggets to system answers. We call this the AutoNuggetizer framework. Within the TREC setup, we are able to calibrate our fully automatic process against a manual process whereby nuggets are created by human assessors semi-manually and then assigned manually to system answers. Based on initial results across 21 topics from 45 runs, we observe a strong correlation between scores derived from a fully automatic nugget evaluation and a (mostly) manual nugget evaluation by human assessors. This suggests that our fully automatic evaluation process can be used to guide future iterations of RAG systems.

[Arxiv](https://arxiv.org/abs/2411.09607)