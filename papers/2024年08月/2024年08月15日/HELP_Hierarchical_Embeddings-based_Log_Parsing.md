# HELP：一种基于层次嵌入技术的日志解析方法

发布时间：2024年08月15日

`LLM应用` `软件维护` `故障诊断`

> HELP: Hierarchical Embeddings-based Log Parsing

# 摘要

> 日志作为软件维护和故障诊断的直接信息源，其解析过程至关重要。然而，现有解析器在实际应用中面临三大难题：传统启发式解析器依赖手工特征和领域知识，难以大规模泛化；大型语言模型解析器需周期性离线处理，实时性受限；在线解析算法易受日志漂移影响，误报频发。为此，我们推出HELP，首个利用LLM的在线语义日志解析器，通过创新层次嵌入模块大幅降低成本，并引入迭代再平衡机制应对日志漂移。在14个大规模数据集上的测试表明，HELP在分组和解析准确性上远超同类产品，并已成功应用于Iudex的生产环境，展现了其高效且实用的特性。

> Logs are a first-hand source of information for software maintenance and failure diagnosis. Log parsing, which converts semi-structured log messages into structured templates, is a prerequisite for automated log analysis tasks such as anomaly detection, troubleshooting, and root cause analysis. However, existing log parsers fail in real-world systems for three main reasons. First, traditional heuristics-based parsers require handcrafted features and domain knowledge, which are difficult to generalize at scale. Second, existing large language model-based parsers rely on periodic offline processing, limiting their effectiveness in real-time use cases. Third, existing online parsing algorithms are susceptible to log drift, where slight log changes create false positives that drown out real anomalies. To address these challenges, we propose HELP, a Hierarchical Embeddings-based Log Parser. HELP is the first online semantic-based parser to leverage LLMs for performant and cost-effective log parsing. We achieve this through a novel hierarchical embeddings module, which fine-tunes a text embedding model to cluster logs before parsing, reducing querying costs by multiple orders of magnitude. To combat log drift, we also develop an iterative rebalancing module, which periodically updates existing log groupings. We evaluate HELP extensively on 14 public large-scale datasets, showing that HELP achieves significantly higher F1-weighted grouping and parsing accuracy than current state-of-the-art online log parsers. We also implement HELP into Iudex's production observability platform, confirming HELP's practicality in a production environment. Our results show that HELP is effective and efficient for high-throughput real-world log parsing.

[Arxiv](https://arxiv.org/abs/2408.08300)