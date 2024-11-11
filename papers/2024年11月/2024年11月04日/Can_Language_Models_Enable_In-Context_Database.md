# 语言模型能够实现上下文数据库吗？

发布时间：2024年11月04日

`RAG` `数据库` `语言模型`

> Can Language Models Enable In-Context Database?

# 摘要

> 大型语言模型（LLMs）正在成为能够处理各种任务的少样本学习者，包括理解、规划、推理、问答、算术计算等等。这些能力的核心是 LLMs 在表示和理解结构或半结构数据（如表格和图表）方面的熟练程度。众多研究表明，对表格数据或图表进行推理不仅对 LLMs 是可行的，而且为将这些数据视为上下文数据提供了一个有前途的研究方向。上下文数据库的轻量和人类可读的特点有可能使其在典型的 RAG（检索增强生成）设置中成为传统数据库的替代品。然而，几乎所有当前的工作都集中在静态的上下文数据上，这不允许动态更新。在本文中，为了实现动态数据库更新，提出了数据库的增量编码。我们探讨了如何将传统 RDBMS 中存储的数据编码为上下文文本，并评估 LLMs 对上下文数据库的 CRUD（创建、读取、更新和删除）操作的熟练程度。提出了一个名为 InConDB 的基准，并进行了广泛的实验，通过改变数据库编码方法、提示方法、操作类型和输入数据分布，展示了不同语言模型在实现上下文数据库方面的性能，揭示了其熟练程度和局限性。

> Large language models (LLMs) are emerging as few-shot learners capable of handling a variety of tasks, including comprehension, planning, reasoning, question answering, arithmetic calculations, and more. At the core of these capabilities is LLMs' proficiency in representing and understanding structural or semi-structural data, such as tables and graphs. Numerous studies have demonstrated that reasoning on tabular data or graphs is not only feasible for LLMs but also gives a promising research direction which treats these data as in-context data. The lightweight and human readable characteristics of in-context database can potentially make it an alternative for the traditional database in typical RAG (Retrieval Augmented Generation) settings. However, almost all current work focuses on static in-context data, which does not allow dynamic update. In this paper, to enable dynamic database update, delta encoding of database is proposed. We explore how data stored in traditional RDBMS can be encoded as in-context text and evaluate LLMs' proficiency for CRUD (Create, Read, Update and Delete) operations on in-context databases. A benchmark named InConDB is presented and extensive experiments are conducted to show the performance of different language models in enabling in-context database by varying the database encoding method, prompting method, operation type and input data distribution, revealing both the proficiency and limitations.

[Arxiv](https://arxiv.org/abs/2411.01807)