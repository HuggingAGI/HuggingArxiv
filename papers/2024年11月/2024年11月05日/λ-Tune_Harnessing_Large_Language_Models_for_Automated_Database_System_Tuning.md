# λ-Tune：利用大型语言模型进行自动化数据库系统调优

发布时间：2024年11月05日

`LLM应用` `数据库` `系统调优`

> λ-Tune: Harnessing Large Language Models for Automated Database System Tuning

# 摘要

> 我们引入了λ-Tune，这是一个利用大型语言模型（LLM）进行自动化数据库系统调优的框架。λ-Tune 的设计受到最新一代 LLM 能力的推动。与之前的工作不同，利用 LLM 为单个参数提取调优提示，λ-Tune 根据描述调优上下文的大型输入文档生成整个配置脚本。λ-Tune 使用一种原则性的方法生成替代配置，从一小部分候选配置中识别出最佳配置。这样做，它最大限度地减少了重新配置的开销，并确保评估成本作为最优运行时间的函数是有界的。通过将提示生成视为基于成本的优化问题，λ-Tune 向 LLM 传达最相关的上下文，同时限制输入标记的数量，从而限制 LLM 调用的费用。我们将λ-Tune 与各种基线进行比较，使用多个基准以及 PostgreSQL 和 MySQL 作为调优的目标系统，表明λ-Tune 比以前的方法明显更强大。

> We introduce λ-Tune, a framework that leverages Large Language Models (LLMs) for automated database system tuning. The design of λ-Tune is motivated by the capabilities of the latest generation of LLMs. Different from prior work, leveraging LLMs to extract tuning hints for single parameters, λ-Tune generates entire configuration scripts, based on a large input document, describing the tuning context. λ-Tune generates alternative configurations, using a principled approach to identify the best configuration, out of a small set of candidates. In doing so, it minimizes reconfiguration overheads and ensures that evaluation costs are bounded as a function of the optimal run time. By treating prompt generation as a cost-based optimization problem, λ-Tune conveys the most relevant context to the LLM while bounding the number of input tokens and, therefore, monetary fees for LLM invocations. We compare λ-Tune to various baselines, using multiple benchmarks and PostgreSQL and MySQL as target systems for tuning, showing that λ-Tune is significantly more robust than prior approaches.

[Arxiv](https://arxiv.org/abs/2411.03500)