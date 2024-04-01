# 挖掘大型语言模型在数据科学预测表格任务中的潜在力量。

发布时间：2024年03月29日

`LLM应用` `数据科学` `表格数据分析`

> Unleashing the Potential of Large Language Models for Predictive Tabular Tasks in Data Science

# 摘要

> 在数据科学的世界里，我们经常遇到表格数据的分类、回归和填补缺失值等预测任务。本研究尝试利用大型语言模型（LLMs）来应对这些挑战。尽管LLMs在理解自然语言上有着出色的表现，面对结构化的表格数据时却显得力不从心，这主要是因为它们在初始训练阶段缺乏对表格数据细节的了解。为了弥补这一不足，我们构建了一个详尽的带注释表格语料库，并对Llama-2进行了大规模的训练。我们还探索了将训练后的模型应用于零-shot、少-shot和上下文学习等实际场景。经过大量实验验证，我们的方法是对现有基准的显著提升，这不仅展示了针对数据科学中的表格问题定制LLM训练的有效性，也为利用LLMs提升表格数据分析智能树立了新的标杆。

> In the domain of data science, the predictive tasks of classification, regression, and imputation of missing values are commonly encountered challenges associated with tabular data. This research endeavors to apply Large Language Models (LLMs) towards addressing these predictive tasks. Despite their proficiency in comprehending natural language, LLMs fall short in dealing with structured tabular data. This limitation stems from their lacking exposure to the intricacies of tabular data during their foundational training. Our research aims to mitigate this gap by compiling a comprehensive corpus of tables annotated with instructions and executing large-scale training of Llama-2 on this enriched dataset. Furthermore, we investigate the practical application of applying the trained model to zero-shot prediction, few-shot prediction, and in-context learning scenarios. Through extensive experiments, our methodology has shown significant improvements over existing benchmarks. These advancements highlight the efficacy of tailoring LLM training to solve table-related problems in data science, thereby establishing a new benchmark in the utilization of LLMs for enhancing tabular intelligence.

[Arxiv](https://arxiv.org/abs/2403.20208)