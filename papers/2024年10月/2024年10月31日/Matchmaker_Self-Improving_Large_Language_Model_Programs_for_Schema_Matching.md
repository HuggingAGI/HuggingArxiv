# Matchmaker：用于模式匹配的可自我改进的大型语言模型程序

发布时间：2024年10月31日

`LLM应用`

> Matchmaker: Self-Improving Large Language Model Programs for Schema Matching

# 摘要

> 模式匹配——即在具有不同表格和层级结构的各异数据源之间寻找属性匹配的任务——对于创建可互操作的机器学习（ML）就绪数据极为关键。解决这一基本的以数据为中心的问题影响广泛，尤其在医疗保健、金融和电子商务等领域。同时，通过增加 ML 模型训练可用数据，还有望更普遍地惠及 ML 模型。然而，由于不同模式间存在结构/层级和语义的异质性，模式匹配是一项颇具挑战的 ML 任务。此前用于自动化模式匹配的 ML 方法，要么需要大量有标记数据用于模型训练，这往往不现实，要么零样本性能欠佳。为此，我们提出了 Matchmaker——一个用于模式匹配的组合语言模型程序，包含候选生成、细化和置信度评分。Matchmaker 还通过一种新颖的优化方式以零样本方式自我改进，无需有标记示例，该方式构建合成的上下文示例来引导语言模型的推理过程。从经验来看，在真实世界的医疗模式匹配基准测试中，Matchmaker 优于以往基于 ML 的方法，凸显了其加速数据集成和 ML 就绪数据互操作性的潜力。

> Schema matching -- the task of finding matches between attributes across disparate data sources with different tables and hierarchies -- is critical for creating interoperable machine learning (ML)-ready data. Addressing this fundamental data-centric problem has wide implications, especially in domains like healthcare, finance and e-commerce -- but also has the potential to benefit ML models more generally, by increasing the data available for ML model training. However, schema matching is a challenging ML task due to structural/hierarchical and semantic heterogeneity between different schemas. Previous ML approaches to automate schema matching have either required significant labeled data for model training, which is often unrealistic or suffer from poor zero-shot performance. To this end, we propose Matchmaker - a compositional language model program for schema matching, comprised of candidate generation, refinement and confidence scoring. Matchmaker also self-improves in a zero-shot manner without the need for labeled demonstrations via a novel optimization approach, which constructs synthetic in-context demonstrations to guide the language model's reasoning process. Empirically, we demonstrate on real-world medical schema matching benchmarks that Matchmaker outperforms previous ML-based approaches, highlighting its potential to accelerate data integration and interoperability of ML-ready data.

[Arxiv](https://arxiv.org/abs/2410.24105)