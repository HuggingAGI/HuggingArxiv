# 借助领域数据库知识，提升大型语言模型在文本转SQL方面的表现

发布时间：2024年09月24日

`LLM应用` `数据库`

> Enhancing Text-to-SQL Capabilities of Large Language Models via Domain Database Knowledge Injection

# 摘要

> Text-to-SQL 作为语义解析的一部分，随着 LLM 的进步取得了显著进展。然而，LLM 在处理幻觉问题和缺乏特定数据库知识时遇到困难，导致在生成 SQL 语句时容易出错。本文提出了一种知识注入方法，通过引入先验知识来提升 LLM 对数据库模式的理解，从而改善 Text-to-SQL 任务的表现。实验显示，预训练和微调显著提升了 EX 和 EM 指标，减少了生成错误。此外，这种方法具有广泛的应用潜力，适用于多种 Text-to-SQL 任务。

> Text-to-SQL is a subtask in semantic parsing that has seen rapid progress with the evolution of Large Language Models (LLMs). However, LLMs face challenges due to hallucination issues and a lack of domain-specific database knowledge(such as table schema and cell values). As a result, they can make errors in generating table names, columns, and matching values to the correct columns in SQL statements. This paper introduces a method of knowledge injection to enhance LLMs' ability to understand schema contents by incorporating prior knowledge. This approach improves their performance in Text-to-SQL tasks. Experimental results show that pre-training LLMs on domain-specific database knowledge and fine-tuning them on downstream Text-to-SQL tasks significantly improves the Execution Match (EX) and Exact Match (EM) metrics across various models. This effectively reduces errors in generating column names and matching values to the columns. Furthermore, the knowledge-injected models can be applied to many downstream Text-to-SQL tasks, demonstrating the generalizability of the approach presented in this paper.

[Arxiv](https://arxiv.org/abs/2409.15907)