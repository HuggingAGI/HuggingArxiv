# 对 LLM 网络代理的文化和社会意识进行评估

发布时间：2024年10月30日

`Agent` `在线购物` `社交讨论`

> Evaluating Cultural and Social Awareness of LLM Web Agents

# 摘要

> 随着大型语言模型（LLMs）拓展到传统自然语言处理（NLP）任务之外，在现实世界应用中充当代理执行任务，评估其稳健性愈发重要。然而，现有的基准测试往往忽视了文化和社会意识等关键维度。为此，我们推出了 CASA 基准，旨在评估 LLM 代理在两个基于网络的任务——在线购物和社交讨论论坛中对文化和社会规范的敏感度。我们的方法评估 LLM 代理检测并恰当回应违反规范的用户查询与观察的能力。另外，我们提出了一个综合评估框架，用于衡量意识覆盖范围、处理用户查询的有效性以及面对误导性网络内容时的违规率。实验显示，当前的 LLMs 在非代理环境中的表现远优于基于网络的代理环境，代理的意识覆盖不足 10％，违规率超 40％。为提升性能，我们探索了两种方法：提示和微调，发现两者结合能带来互补优势——在特定文化的数据集上微调显著增强了代理在不同地区的泛化能力，而提示则提升了代理处理复杂任务的能力。这些发现凸显了在开发周期中持续对 LLM 代理的文化和社会意识进行基准测试的重要性。

> As large language models (LLMs) expand into performing as agents for real-world applications beyond traditional NLP tasks, evaluating their robustness becomes increasingly important. However, existing benchmarks often overlook critical dimensions like cultural and social awareness. To address these, we introduce CASA, a benchmark designed to assess LLM agents' sensitivity to cultural and social norms across two web-based tasks: online shopping and social discussion forums. Our approach evaluates LLM agents' ability to detect and appropriately respond to norm-violating user queries and observations. Furthermore, we propose a comprehensive evaluation framework that measures awareness coverage, helpfulness in managing user queries, and the violation rate when facing misleading web content. Experiments show that current LLMs perform significantly better in non-agent than in web-based agent environments, with agents achieving less than 10% awareness coverage and over 40% violation rates. To improve performance, we explore two methods: prompting and fine-tuning, and find that combining both methods can offer complementary advantages -- fine-tuning on culture-specific datasets significantly enhances the agents' ability to generalize across different regions, while prompting boosts the agents' ability to navigate complex tasks. These findings highlight the importance of constantly benchmarking LLM agents' cultural and social awareness during the development cycle.

[Arxiv](https://arxiv.org/abs/2410.23252)