# 迈向公平RAG：探讨检索增强生成中公平排序的影响

发布时间：2024年09月17日

`RAG` `人工智能` `信息检索`

> Towards Fair RAG: On the Impact of Fair Ranking in Retrieval-Augmented Generation

# 摘要

> 如今，许多语言模型通过检索功能提升其响应能力，推动了检索增强生成 (RAG) 系统的普及。然而，尽管检索是 RAG 的核心，许多研究却忽略了公平排序的重要性，未能全面考虑各方利益。本文首次系统评估了集成公平排序的 RAG 系统，特别关注排名中各相关项目的公平曝光度 (项目侧公平性)，以促进相关项目提供者的公平发展。我们分析了九个不同 RAG 系统在七个数据集上的表现，发现这些系统不仅能保持高生成质量，甚至在许多情况下超越传统 RAG 系统，尽管公平性与系统有效性之间存在权衡。我们的研究为构建负责任且公平的 RAG 系统奠定了基础，并为未来研究指明了新方向。代码库和数据集已公开发布于 https://github.com/kimdanny/Fair-RAG。

> Many language models now enhance their responses with retrieval capabilities, leading to the widespread adoption of retrieval-augmented generation (RAG) systems. However, despite retrieval being a core component of RAG, much of the research in this area overlooks the extensive body of work on fair ranking, neglecting the importance of considering all stakeholders involved. This paper presents the first systematic evaluation of RAG systems integrated with fair rankings. We focus specifically on measuring the fair exposure of each relevant item across the rankings utilized by RAG systems (i.e., item-side fairness), aiming to promote equitable growth for relevant item providers. To gain a deep understanding of the relationship between item-fairness, ranking quality, and generation quality in the context of RAG, we analyze nine different RAG systems that incorporate fair rankings across seven distinct datasets. Our findings indicate that RAG systems with fair rankings can maintain a high level of generation quality and, in many cases, even outperform traditional RAG systems, despite the general trend of a tradeoff between ensuring fairness and maintaining system-effectiveness. We believe our insights lay the groundwork for responsible and equitable RAG systems and open new avenues for future research. We publicly release our codebase and dataset at https://github.com/kimdanny/Fair-RAG.

[Arxiv](https://arxiv.org/abs/2409.11598)