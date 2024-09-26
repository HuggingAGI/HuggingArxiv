# E-SQL：通过问题丰富实现文本到SQL的直接模式链接

发布时间：2024年09月25日

`LLM应用` `数据库`

> E-SQL: Direct Schema Linking via Question Enrichment in Text-to-SQL

# 摘要

> 将自然语言查询转化为SQL查询（Text-to-SQL）是自然语言处理和数据库领域的关键任务，旨在为数据库提供自然语言接口，降低非专家的使用门槛。尽管大型语言模型（LLMs）带来了进步，但仍面临处理复杂数据库模式、解决查询歧义和生成准确SQL等挑战。为此，我们推出了E-SQL，一种通过直接模式链接和候选谓词增强来应对这些挑战的新方法。E-SQL通过将数据库元素直接融入查询，增强了自然语言查询，并利用候选谓词增强来修正SQL中的错误。我们还探讨了模式过滤技术的影响，发现其效果在先进LLM的辅助下逐渐减弱。在BIRD基准测试中，E-SQL在复杂查询中表现优异，执行准确率达66.29%。所有相关代码已在GitHub上公开。

> Translating Natural Language Queries into Structured Query Language (Text-to-SQL or NLQ-to-SQL) is a critical task extensively studied by both the natural language processing and database communities, aimed at providing a natural language interface to databases (NLIDB) and lowering the barrier for non-experts. Despite recent advancements made through the use of Large Language Models (LLMs), significant challenges remain. These include handling complex database schemas, resolving ambiguity in user queries, and generating SQL queries with intricate structures that accurately reflect the user's intent. In this work, we introduce E-SQL, a novel pipeline specifically designed to address these challenges through direct schema linking and candidate predicate augmentation. E-SQL enhances the natural language query by incorporating relevant database items (i.e., tables, columns, and values) and conditions directly into the question, bridging the gap between the query and the database structure. The pipeline leverages candidate predicate augmentation to mitigate erroneous or incomplete predicates in generated SQLs. We further investigate the impact of schema filtering, a technique widely explored in previous work, and demonstrate its diminishing returns when applied alongside advanced large language models. Comprehensive evaluations on the BIRD benchmark illustrate that E-SQL achieves competitive performance, particularly excelling in complex queries with a 66.29% execution accuracy on the test set. All code required to reproduce the reported results is publicly available on our GitHub repository.

[Arxiv](https://arxiv.org/abs/2409.16751)