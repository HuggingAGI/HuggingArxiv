# MARAGS：多任务检索增强生成问答的多适配器系统

发布时间：2024年09月04日

`RAG` `问答系统` `数据竞赛`

> MARAGS: A Multi-Adapter System for Multi-Task Retrieval Augmented Generation Question Answering

# 摘要

> 本文介绍了一个多适配器检索增强生成系统 (MARAGS)，用于 Meta 的 CRAG 竞赛（KDD CUP 2024）。CRAG 数据集包含 3 个子任务，涵盖现实问答场景，涉及多样的问题主题和类型。MARAGS 系统通过处理网页和查询 API 获取信息，并利用多适配器和交叉编码器模型优化问答效果。最终，我们的系统在任务 1 中获得第二名，在任务 2 中获得第三名。

> In this paper we present a multi-adapter retrieval augmented generation system (MARAGS) for Meta's Comprehensive RAG (CRAG) competition for KDD CUP 2024. CRAG is a question answering dataset contains 3 different subtasks aimed at realistic question and answering RAG related tasks, with a diverse set of question topics, question types, time dynamic answers, and questions featuring entities of varying popularity.
  Our system follows a standard setup for web based RAG, which uses processed web pages to provide context for an LLM to produce generations, while also querying API endpoints for additional information. MARAGS also utilizes multiple different adapters to solve the various requirements for these tasks with a standard cross-encoder model for ranking candidate passages relevant for answering the question. Our system achieved 2nd place for Task 1 as well as 3rd place on Task 2.

[Arxiv](https://arxiv.org/abs/2409.03171)