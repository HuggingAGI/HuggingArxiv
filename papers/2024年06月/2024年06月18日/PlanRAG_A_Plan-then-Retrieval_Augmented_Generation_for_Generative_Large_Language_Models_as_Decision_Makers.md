# PlanRAG：为决策型大型生成语言模型设计的先规划后检索增强生成策略

发布时间：2024年06月18日

`RAG

这篇论文主要介绍了一种名为PlanRAG的新技术，该技术结合了大型语言模型（LLMs）和检索增强生成技术，用于解决复杂的决策问题。PlanRAG技术通过迭代计划和检索增强生成，有效地处理了决策QA任务，并在特定的基准测试中取得了优于现有技术的性能。因此，这篇论文更符合RAG分类，因为它专注于检索增强生成技术的应用，而不是Agent的设计、LLM的理论研究或一般的LLM应用。` `决策支持系统` `游戏开发`

> PlanRAG: A Plan-then-Retrieval Augmented Generation for Generative Large Language Models as Decision Makers

# 摘要

> 本文探讨了如何运用大型语言模型（LLMs）解决涉及复杂数据分析的决策问题。我们定义了决策QA任务，即根据问题Q、规则R和数据库D，确定最佳决策d_{best}。为此，我们创建了决策QA基准DQA，包含“定位”与“建设”两场景，灵感源自《欧陆风云IV》与《维多利亚3》两款游戏。针对此任务，我们创新性地提出了迭代计划后检索增强生成技术（PlanRAG）。该技术先由语言模型制定决策计划，再由检索器生成数据分析查询。实验表明，PlanRAG在“定位”场景中超越现有技术15.8%，在“建设”场景中超越7.4%。相关代码与基准已公开于https://github.com/myeon9h/PlanRAG。

> In this paper, we conduct a study to utilize LLMs as a solution for decision making that requires complex data analysis. We define Decision QA as the task of answering the best decision, $d_{best}$, for a decision-making question $Q$, business rules $R$ and a database $D$. Since there is no benchmark that can examine Decision QA, we propose Decision QA benchmark, DQA. It has two scenarios, Locating and Building, constructed from two video games (Europa Universalis IV and Victoria 3) that have almost the same goal as Decision QA. To address Decision QA effectively, we also propose a new RAG technique called the iterative plan-then-retrieval augmented generation (PlanRAG). Our PlanRAG-based LM generates the plan for decision making as the first step, and the retriever generates the queries for data analysis as the second step. The proposed method outperforms the state-of-the-art iterative RAG method by 15.8% in the Locating scenario and by 7.4% in the Building scenario, respectively. We release our code and benchmark at https://github.com/myeon9h/PlanRAG.

![PlanRAG：为决策型大型生成语言模型设计的先规划后检索增强生成策略](../../../paper_images/2406.12430/x1.png)

![PlanRAG：为决策型大型生成语言模型设计的先规划后检索增强生成策略](../../../paper_images/2406.12430/x4.png)

![PlanRAG：为决策型大型生成语言模型设计的先规划后检索增强生成策略](../../../paper_images/2406.12430/x5.png)

![PlanRAG：为决策型大型生成语言模型设计的先规划后检索增强生成策略](../../../paper_images/2406.12430/x6.png)

![PlanRAG：为决策型大型生成语言模型设计的先规划后检索增强生成策略](../../../paper_images/2406.12430/x7.png)

![PlanRAG：为决策型大型生成语言模型设计的先规划后检索增强生成策略](../../../paper_images/2406.12430/x8.png)

![PlanRAG：为决策型大型生成语言模型设计的先规划后检索增强生成策略](../../../paper_images/2406.12430/x9.png)

![PlanRAG：为决策型大型生成语言模型设计的先规划后检索增强生成策略](../../../paper_images/2406.12430/x10.png)

![PlanRAG：为决策型大型生成语言模型设计的先规划后检索增强生成策略](../../../paper_images/2406.12430/x11.png)

![PlanRAG：为决策型大型生成语言模型设计的先规划后检索增强生成策略](../../../paper_images/2406.12430/x12.png)

[Arxiv](https://arxiv.org/abs/2406.12430)