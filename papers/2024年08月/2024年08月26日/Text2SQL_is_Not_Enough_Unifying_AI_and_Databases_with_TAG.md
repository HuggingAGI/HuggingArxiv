# 仅靠 Text2SQL 远远不够，我们需要通过 TAG 来实现 AI 与数据库的真正融合。

发布时间：2024年08月26日

`RAG` `数据库` `人工智能`

> Text2SQL is Not Enough: Unifying AI and Databases with TAG

# 摘要

> AI系统通过自然语言查询数据库，潜力巨大。它们结合了语言模型的推理能力与数据管理系统的计算优势，使用户能自由查询自定义数据。但现有技术与评估标准未能充分挖掘这一潜力。Text2SQL和RAG方法各自局限，前者仅处理关系代数可表达的问题，后者则限于点查找能解答的简单查询。为此，我们推出了表增强生成（TAG），一个全新的通用框架，旨在探索语言模型与数据库间更广泛的交互，并开辟了新的研究领域。我们创建了TAG基准测试，结果显示传统方法仅能正确回答不到20%的查询，凸显了深入研究的迫切需求。基准代码已公开于https://github.com/TAG-Research/TAG-Bench。

> AI systems that serve natural language questions over databases promise to unlock tremendous value. Such systems would allow users to leverage the powerful reasoning and knowledge capabilities of language models (LMs) alongside the scalable computational power of data management systems. These combined capabilities would empower users to ask arbitrary natural language questions over custom data sources. However, existing methods and benchmarks insufficiently explore this setting. Text2SQL methods focus solely on natural language questions that can be expressed in relational algebra, representing a small subset of the questions real users wish to ask. Likewise, Retrieval-Augmented Generation (RAG) considers the limited subset of queries that can be answered with point lookups to one or a few data records within the database. We propose Table-Augmented Generation (TAG), a unified and general-purpose paradigm for answering natural language questions over databases. The TAG model represents a wide range of interactions between the LM and database that have been previously unexplored and creates exciting research opportunities for leveraging the world knowledge and reasoning capabilities of LMs over data. We systematically develop benchmarks to study the TAG problem and find that standard methods answer no more than 20% of queries correctly, confirming the need for further research in this area. We release code for the benchmark at https://github.com/TAG-Research/TAG-Bench.

[Arxiv](https://arxiv.org/abs/2408.14717)