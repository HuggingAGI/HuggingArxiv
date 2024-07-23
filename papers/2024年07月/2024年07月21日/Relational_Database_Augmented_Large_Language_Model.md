# 关系数据库强化的大型语言模型

发布时间：2024年07月21日

`LLM应用` `数据库`

> Relational Database Augmented Large Language Model

# 摘要

> 大型语言模型（LLM）在众多自然语言处理任务中表现卓越，但因其仅能通过训练或微调获取新知，故不适用于需精准、实时且私密信息的场景，此类信息常存于关系数据库中。为此，我们提出将关系数据库作为外部记忆融入LLM，以确保数据时效与准确，并助其超越固有能力执行复杂运算。然而，连接LLM与数据库颇具挑战，需精准选库与SQL查询。此外，外部记忆需独立于LLM，以适应实际需求。我们创新设计了包含数据库选择、数据值记忆及关系数据库的架构，并构建了精巧的信息检索流程。同时，我们精心设计提示，最大化框架效能。为验证方法，我们创建了涵盖各类问题的新数据集。实验表明，该框架使LLM有效应对数据库相关问题，超越了其原有能力。

> Large language models (LLMs) excel in many natural language processing (NLP) tasks. However, since LLMs can only incorporate new knowledge through training or supervised fine-tuning processes, they are unsuitable for applications that demand precise, up-to-date, and private information not available in the training corpora. This precise, up-to-date, and private information is typically stored in relational databases. Thus, a promising solution is to augment LLMs with the inclusion of relational databases as external memory. This can ensure the timeliness, correctness, and consistency of data, and assist LLMs in performing complex arithmetic operations beyond their inherent capabilities. However, bridging the gap between LLMs and relational databases is challenging. It requires the awareness of databases and data values stored in databases to select correct databases and issue correct SQL queries. Besides, it is necessary for the external memory to be independent of the LLM to meet the needs of real-world applications. We introduce a novel LLM-agnostic memory architecture comprising a database selection memory, a data value memory, and relational databases. And we design an elegant pipeline to retrieve information from it. Besides, we carefully design the prompts to instruct the LLM to maximize the framework's potential. To evaluate our method, we compose a new dataset with various types of questions. Experimental results show that our framework enables LLMs to effectively answer database-related questions, which is beyond their direct ability.

![关系数据库强化的大型语言模型](../../../paper_images/2407.15071/x1.png)

![关系数据库强化的大型语言模型](../../../paper_images/2407.15071/x2.png)

![关系数据库强化的大型语言模型](../../../paper_images/2407.15071/x3.png)

![关系数据库强化的大型语言模型](../../../paper_images/2407.15071/x4.png)

![关系数据库强化的大型语言模型](../../../paper_images/2407.15071/x5.png)

![关系数据库强化的大型语言模型](../../../paper_images/2407.15071/x6.png)

[Arxiv](https://arxiv.org/abs/2407.15071)