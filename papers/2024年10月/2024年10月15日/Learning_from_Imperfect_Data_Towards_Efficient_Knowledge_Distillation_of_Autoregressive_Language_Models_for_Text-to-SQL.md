# 从不完美数据中学习：提升自动回归语言模型在文本到SQL任务中的知识蒸馏效率

发布时间：2024年10月15日

`LLM应用` `数据库`

> Learning from Imperfect Data: Towards Efficient Knowledge Distillation of Autoregressive Language Models for Text-to-SQL

# 摘要

> 大型语言模型（LLM）在将自然语言问题转换为 SQL 查询方面表现出色，但这些模型计算成本高，难以在实际应用中部署，因此压缩它们显得尤为重要。知识蒸馏（KD）是一种常见方法，旨在将大模型精简为小模型。尽管针对自回归 LLM 的 KD 方法层出不穷，但在复杂文本到 SQL 场景中的效果仍待验证。我们通过分析发现，现有 KD 方法在性能与效率的平衡上存在不足。为此，我们提出了 KID 方法，通过利用不完美数据，在不增加过多训练成本的情况下显著提升性能。KID 的核心在于模拟训练数据中的推理级联效应，从而有效解决训练与推理之间的不匹配问题。实验结果显示，KID 不仅在各类模型上实现了高达 +5.83% 的平均性能提升，还大幅提高了训练效率。

> Large Language Models (LLMs) have shown promising performance in text-to-SQL, which involves translating natural language questions into SQL queries. However, current text-to-SQL LLMs are computationally expensive and challenging to deploy in real-world applications, highlighting the importance of compressing them. To achieve this goal, knowledge distillation (KD) is a common approach, which aims to distill the larger teacher model into a smaller student model. While numerous KD methods for autoregressive LLMs have emerged recently, it is still under-explored whether they work well in complex text-to-SQL scenarios. To this end, we conduct a series of analyses and reveal that these KD methods generally fall short in balancing performance and efficiency. In response to this problem, we propose to improve the KD with Imperfect Data, namely KID, which effectively boosts the performance without introducing much training budget. The core of KID is to efficiently mitigate the training-inference mismatch by simulating the cascading effect of inference in the imperfect training data. Extensive experiments on 5 text-to-SQL benchmarks show that, KID can not only achieve consistent and significant performance gains (up to +5.83% average score) across all model types and sizes, but also effectively improve the training efficiency.

[Arxiv](https://arxiv.org/abs/2410.11371)