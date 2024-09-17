# SelECT-SQL：一种自校正的集成链式思维方法，专为文本到SQL转换设计。

发布时间：2024年09月16日

`LLM应用` `数据库`

> SelECT-SQL: Self-correcting ensemble Chain-of-Thought for Text-to-SQL

# 摘要

> 近年来，Text-to-SQL 问题备受关注，它涉及将自然语言问题自动转换为 SQL 查询。尽管大型语言模型 (LLM) 在现成应用中表现出色，但仍难以达到专家级水平。特别是在需要深入理解数据库结构、问题和 SQL 语法时，错误频发。为此，我们推出了 SelECT-SQL，一种结合链式思维提示、自我修正和集成方法的 in-context learning 解决方案，刷新了 Text-to-SQL 基准测试的记录。使用 GPT-3.5-Turbo 作为基础模型，SelECT-SQL 在 Spider 排行榜开发集上的执行准确率高达 84.2%，超越了其他 GPT-3.5-Turbo 基线方案的最佳成绩 (81.1%) 和 GPT-4 的峰值表现 (83.5%)。

> In recent years,Text-to-SQL, the problem of automatically converting questions posed in natural language to formal SQL queries, has emerged as an important problem at the intersection of natural language processing and data management research. Large language models (LLMs) have delivered impressive performance when used in an off-the-shelf performance, but still fall significantly short of expected expert-level performance. Errors are especially probable when a nuanced understanding is needed of database schemas, questions, and SQL clauses to do proper Text-to-SQL conversion. We introduce SelECT-SQL, a novel in-context learning solution that uses an algorithmic combination of chain-of-thought (CoT) prompting, self-correction, and ensemble methods to yield a new state-of-the-art result on challenging Text-to-SQL benchmarks. Specifically, when configured using GPT-3.5-Turbo as the base LLM, SelECT-SQL achieves 84.2% execution accuracy on the Spider leaderboard's development set, exceeding both the best results of other baseline GPT-3.5-Turbo-based solutions (81.1%), and the peak performance (83.5%) of the GPT-4 result reported on the leaderboard.

[Arxiv](https://arxiv.org/abs/2409.10007)