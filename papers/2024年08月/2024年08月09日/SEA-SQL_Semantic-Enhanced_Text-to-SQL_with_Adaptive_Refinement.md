# SEA-SQL：融合语义增强与自适应细化的文本转SQL技术

发布时间：2024年08月09日

`LLM应用` `数据库` `软件开发`

> SEA-SQL: Semantic-Enhanced Text-to-SQL with Adaptive Refinement

# 摘要

> 大型语言模型 (LLM) 的最新进展极大地推动了 Text-to-SQL 任务的发展。在这些研究中，多数需要对生成的 SQL 查询进行后校正，主要通过分析错误案例来设计规则，以消除模型偏差，但缺乏对 SQL 查询的执行验证。此外，当前主流技术多依赖于 GPT-4 和少样本提示，成本高昂。为此，我们提出了语义增强的自适应细化 Text-to-SQL (SEA-SQL)，通过自适应偏差消除和动态执行调整，旨在提升性能的同时降低资源消耗，采用零样本提示。SEA-SQL 利用语义增强模式来丰富数据库信息并优化 SQL 查询，通过微调的自适应偏差消除器来减少 LLM 固有偏差，并进行动态执行调整以确保查询的可执行性。实验结果显示，SEA-SQL 在 GPT3.5 环境下以 9%-58% 的成本达到了行业领先水平，且与 GPT-4 性能相当，成本仅为其 0.9%-5.3%。

> Recent advancements in large language models (LLMs) have significantly contributed to the progress of the Text-to-SQL task. A common requirement in many of these works is the post-correction of SQL queries. However, the majority of this process entails analyzing error cases to develop prompts with rules that eliminate model bias. And there is an absence of execution verification for SQL queries. In addition, the prevalent techniques primarily depend on GPT-4 and few-shot prompts, resulting in expensive costs. To investigate the effective methods for SQL refinement in a cost-efficient manner, we introduce Semantic-Enhanced Text-to-SQL with Adaptive Refinement (SEA-SQL), which includes Adaptive Bias Elimination and Dynamic Execution Adjustment, aims to improve performance while minimizing resource expenditure with zero-shot prompts. Specifically, SEA-SQL employs a semantic-enhanced schema to augment database information and optimize SQL queries. During the SQL query generation, a fine-tuned adaptive bias eliminator is applied to mitigate inherent biases caused by the LLM. The dynamic execution adjustment is utilized to guarantee the executability of the bias eliminated SQL query. We conduct experiments on the Spider and BIRD datasets to demonstrate the effectiveness of this framework. The results demonstrate that SEA-SQL achieves state-of-the-art performance in the GPT3.5 scenario with 9%-58% of the generation cost. Furthermore, SEA-SQL is comparable to GPT-4 with only 0.9%-5.3% of the generation cost.

[Arxiv](https://arxiv.org/abs/2408.04919)