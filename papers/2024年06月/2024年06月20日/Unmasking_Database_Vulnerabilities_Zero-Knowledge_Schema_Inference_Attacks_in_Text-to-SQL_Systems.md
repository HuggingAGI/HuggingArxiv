# 揭秘数据库安全漏洞：探究文本到SQL系统中零知识模式推断攻击的威胁

发布时间：2024年06月20日

`Agent

理由：这篇论文主要探讨了如何通过文本到SQL技术来理解和探索数据库结构，以及这种理解如何可能增加安全风险，如SQL注入攻击。论文中提出的零知识框架是一种策略，用于在不直接接触数据库的情况下探索数据库结构。这种策略可以被视为一种智能体（Agent）的行为，因为它涉及到对环境的探索和理解，以及基于这种理解采取的行动。因此，这篇论文更符合Agent分类，而不是RAG、LLM应用或LLM理论。` `数据库管理` `信息安全`

> Unmasking Database Vulnerabilities: Zero-Knowledge Schema Inference Attacks in Text-to-SQL Systems

# 摘要

> 关系数据库是现代信息系统的基石，它们支持着数据的存储、查询和管理。随着大型语言模型技术的进步，文本到SQL技术应运而生，极大地提升了从数据库中提取信息的能力，同时也带来了隐私和安全的新挑战。我们的研究揭示了文本到SQL模型背后的数据库结构元素。了解这些结构可能使SQL注入等攻击更为容易。为此，我们设计了一套零知识框架，通过提出特定问题来探索数据库结构，而不直接接触数据库。这套框架应用于经过文本-SQL对微调的模型和生成SQL的语言模型，成功重建了表名，微调模型的F1分数达到0.75，生成模型的F1分数高达0.96。

> Relational databases are integral to modern information systems, serving as the foundation for storing, querying, and managing data efficiently and effectively. Advancements in large language modeling have led to the emergence of text-to-SQL technologies, significantly enhancing the querying and extracting of information from these databases and raising concerns about privacy and security. Our research extracts the database schema elements underlying a text-to-SQL model. Knowledge of the schema can make attacks such as SQL injection easier. By asking specially crafted questions, we have developed a zero-knowledge framework designed to probe various database schema elements without knowledge of the database itself. The text-to-SQL models then process these questions to produce an output that we use to uncover the structure of the database schema. We apply it to specialized text-to-SQL models fine-tuned on text-SQL pairs and generative language models used for SQL generation. Overall, we can reconstruct the table names with an F1 of nearly .75 for fine-tuned models and .96 for generative.

![揭秘数据库安全漏洞：探究文本到SQL系统中零知识模式推断攻击的威胁](../../../paper_images/2406.14545/x1.png)

![揭秘数据库安全漏洞：探究文本到SQL系统中零知识模式推断攻击的威胁](../../../paper_images/2406.14545/x2.png)

![揭秘数据库安全漏洞：探究文本到SQL系统中零知识模式推断攻击的威胁](../../../paper_images/2406.14545/x3.png)

[Arxiv](https://arxiv.org/abs/2406.14545)