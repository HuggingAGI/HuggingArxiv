# CHASE-SQL：优化文本到SQL转换中的多路径推理与候选选择

发布时间：2024年10月02日

`LLM应用` `数据库` `人工智能`

> CHASE-SQL: Multi-Path Reasoning and Preference Optimized Candidate Selection in Text-to-SQL

# 摘要

> 在解决 Text-to-SQL 任务中 LLM 的性能难题时，我们推出了 CHASE-SQL 框架。该框架通过多代理建模中的测试时间计算，创新性地提升了候选 SQL 查询的生成与选择。CHASE-SQL 利用 LLM 的内在知识，采用三种策略生成高质量 SQL 候选：分解复杂查询、基于执行计划的链式推理，以及定制化的少样本示例生成。通过微调的二进制候选选择 LLM 进行成对比较，选择代理能更稳健地选出最佳候选。CHASE-SQL 不仅提升了 SQL 查询的质量与多样性，还在 BIRD Text-to-SQL 数据集上以 73.0% 和 73.01% 的执行准确率刷新了记录，成为当时的排行榜冠军。

> In tackling the challenges of large language model (LLM) performance for Text-to-SQL tasks, we introduce CHASE-SQL, a new framework that employs innovative strategies, using test-time compute in multi-agent modeling to improve candidate generation and selection. CHASE-SQL leverages LLMs' intrinsic knowledge to generate diverse and high-quality SQL candidates using different LLM generators with: (1) a divide-and-conquer method that decomposes complex queries into manageable sub-queries in a single LLM call; (2) chain-of-thought reasoning based on query execution plans, reflecting the steps a database engine takes during execution; and (3) a unique instance-aware synthetic example generation technique, which offers specific few-shot demonstrations tailored to test questions.To identify the best candidate, a selection agent is employed to rank the candidates through pairwise comparisons with a fine-tuned binary-candidates selection LLM. This selection approach has been demonstrated to be more robust over alternatives. The proposed generators-selector framework not only enhances the quality and diversity of SQL queries but also outperforms previous methods. Overall, our proposed CHASE-SQL achieves the state-of-the-art execution accuracy of 73.0% and 73.01% on the test set and development set of the notable BIRD Text-to-SQL dataset benchmark, rendering CHASE-SQL the top submission of the leaderboard (at the time of paper submission).

[Arxiv](https://arxiv.org/abs/2410.01943)