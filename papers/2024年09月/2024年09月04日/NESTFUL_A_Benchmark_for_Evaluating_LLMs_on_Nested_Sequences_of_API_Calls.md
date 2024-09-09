# NESTFUL：评估 LLM 处理嵌套 API 调用序列的基准

发布时间：2024年09月04日

`Agent` `软件开发` `人工智能`

> NESTFUL: A Benchmark for Evaluating LLMs on Nested Sequences of API Calls

# 摘要

> 由 LLM 驱动的自主代理应用近期因其解决复杂现实任务的能力而备受瞩目。这些应用的核心在于利用 LLM 规划并执行一系列工具和 API 调用，以满足用户需求。尽管已有多种基准测试 LLM 的 API 使用能力，但大多仅限于单一或多个孤立的 API 调用。本文介绍的 NESTFUL 基准，专注于评估 LLM 在嵌套 API 调用序列上的表现，即前一 API 的输出作为下一调用的输入。NESTFUL 包含 300 个由人类注释的样本，分为可执行和不可执行两类。可执行样本通过 Rapid-APIs 爬取，不可执行样本则由人工从 LLM 生成的数据中挑选。实验结果表明，相较于现有基准中的简单任务，大多数 LLM 在 NESTFUL 的嵌套 API 调用上表现欠佳。

> Autonomous agent applications powered by large language models (LLMs) have recently risen to prominence as effective tools for addressing complex real-world tasks. At their core, agentic workflows rely on LLMs to plan and execute the use of tools and external Application Programming Interfaces (APIs) in sequence to arrive at the answer to a user's request. Various benchmarks and leaderboards have emerged to evaluate an LLM's capabilities for tool and API use; however, most of these evaluations only track single or multiple isolated API calling capabilities. In this paper, we present NESTFUL, a benchmark to evaluate LLMs on nested sequences of API calls, i.e., sequences where the output of one API call is passed as input to a subsequent call. NESTFUL has a total of 300 human annotated samples divided into two types - executable and non-executable. The executable samples are curated manually by crawling Rapid-APIs whereas the non-executable samples are hand picked by human annotators from data synthetically generated using an LLM. We evaluate state-of-the-art LLMs with function calling abilities on NESTFUL. Our results show that most models do not perform well on nested APIs in NESTFUL as compared to their performance on the simpler problem settings available in existing benchmarks.

[Arxiv](https://arxiv.org/abs/2409.03797)