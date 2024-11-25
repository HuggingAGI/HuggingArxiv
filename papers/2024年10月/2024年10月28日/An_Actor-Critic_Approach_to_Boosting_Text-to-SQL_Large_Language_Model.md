# 一种提升文本到 SQL 大型语言模型的演员 - 评论家式方法

发布时间：2024年10月28日

`LLM应用` `数据库`

> An Actor-Critic Approach to Boosting Text-to-SQL Large Language Model

# 摘要

> Text-To-SQL（T2S）基于大型语言模型（LLMs）的转换已得到广泛应用，凭借LLMs解释自然语言表达的查询意图的能力。现有研究聚焦于数据模式和/或问题的恰当表示、特定任务的指令与代表性示例以及复杂的推理流程。所有这些方法都是经验性和任务特定的，不存在性能的理论界限。在本文中，我们提出了一种简单、通用且性能有保障的T2S增强方法，名为Actor-Critic（AC）。具体而言，我们使用相同的LLM设计了两个角色：一个Actor生成SQL查询，一个Critic评估生成的SQL。若Critic认为生成的SQL有误，它会通知Actor重新生成SQL并再次评估。通过这一简单的迭代过程，理论上能够得出预期性能。我们在Spider及相关数据集上用11个LLMs进行了大量实验，证明了Actor-Critic方法持续提升了T2S的性能，从而成为T2S转换的通用增强途径。

> Text-To-SQL (T2S) conversion based on large language models (LLMs) has found a wide range of applications, by leveraging the capabilities of LLMs in interpreting the query intent expressed in natural language. Existing research focuses on suitable representations for data schema and/or questions, task-specific instructions and representative examples, and complicated inference pipelines. All these methods are empirical and task specific, without a theoretical bound on performance. In this paper, we propose a simple, general, and performance guaranteed T2S enhancement approach called Actor-Critic (AC). Specifically, we design two roles using the same LLM: an Actor to produce SQL queries and a Critic to evaluate the produced SQL. If the Critic believes the produced SQL is wrong, it notifies the Actor to reproduce the SQL and perform evaluation again. By this simple iterative process, expected performance can be derived in theory. We conducted extensive experiments on the Spider and related datasets with eleven LLMs, and demonstrated that the Actor-Critic method consistently improves the performance of T2S, thus serving as a general enhancement approach for T2S conversion.

[Arxiv](https://arxiv.org/abs/2410.22082)