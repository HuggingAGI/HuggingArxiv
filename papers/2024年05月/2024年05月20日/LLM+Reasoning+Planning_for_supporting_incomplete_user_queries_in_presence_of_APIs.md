# 大型语言模型（LLM）通过推理与规划，巧妙应对API环境下用户查询的不完整性。

发布时间：2024年05月20日

`Agent

理由：这篇论文介绍了一种结合逻辑推理、经典AI规划与大型语言模型（LLM）的方法，用于处理用户查询中的信息缺失和API协调问题。这种方法通过将用户查询转化为PDDL格式，并利用AI规划器来编排API调用，以提高查询解答的准确性和效率。这种集成多种技术和策略来执行特定任务的方法，符合Agent的定义，即一个能够感知环境、做出决策并执行动作以达到目标的实体。因此，这篇论文应归类于Agent。` `人工智能规划`

> LLM+Reasoning+Planning for supporting incomplete user queries in presence of APIs

# 摘要

> 随着大型语言模型（LLMs）的兴起，基于LLM的自然语言接口方法如雨后春笋般涌现，旨在为各类用户任务提供便捷的交互方式。这些任务通常依赖于一组API的协同工作。然而，用户查询往往信息不全，这可能导致API无法完全响应。尽管LLMs在NLP领域表现卓越，但在处理信息缺失或API协调时却显得力不从心。我们的方法巧妙结合了逻辑推理、经典AI规划与LLM，旨在精准解答用户查询，同时填补查询中的信息空白。通过LLM与ASP求解器的协作，我们将用户查询转化为PDDL格式，并特设“get_info_api”以补全缺失信息。我们将API视为支持数据交互的PDDL动作，并借助AI规划器精心编排API调用，确保查询得到妥善解答。评估表明，我们的方法在处理复杂查询时，成功率高达95%以上，远超单纯依赖LLM的方案。

> Recent availability of Large Language Models (LLMs) has led to the development of numerous LLM-based approaches aimed at providing natural language interfaces for various end-user tasks. These end-user tasks in turn can typically be accomplished by orchestrating a given set of APIs. In practice, natural language task requests (user queries) are often incomplete, i.e., they may not contain all the information required by the APIs. While LLMs excel at natural language processing (NLP) tasks, they frequently hallucinate on missing information or struggle with orchestrating the APIs. The key idea behind our proposed approach is to leverage logical reasoning and classical AI planning along with an LLM for accurately answering user queries including identification and gathering of any missing information in these queries. Our approach uses an LLM and ASP (Answer Set Programming) solver to translate a user query to a representation in Planning Domain Definition Language (PDDL) via an intermediate representation in ASP. We introduce a special API "get_info_api" for gathering missing information. We model all the APIs as PDDL actions in a way that supports dataflow between the APIs. Our approach then uses a classical AI planner to generate an orchestration of API calls (including calls to get_info_api) to answer the user query. Our evaluation results show that our approach significantly outperforms a pure LLM based approach by achieving over 95\% success rate in most cases on a dataset containing complete and incomplete single goal and multi-goal queries where the multi-goal queries may or may not require dataflow among the APIs.

[Arxiv](https://arxiv.org/abs/2405.12433)