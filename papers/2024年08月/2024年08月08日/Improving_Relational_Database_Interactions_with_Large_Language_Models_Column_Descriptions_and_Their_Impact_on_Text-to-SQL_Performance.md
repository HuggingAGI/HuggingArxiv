# 利用大型语言模型优化关系数据库交互：探讨列描述如何提升文本到SQL的转换效率

发布时间：2024年08月08日

`LLM应用` `数据库` `人工智能`

> Improving Relational Database Interactions with Large Language Models: Column Descriptions and Their Impact on Text-to-SQL Performance

# 摘要

> 关系数据库常因表内容描述模糊不清而困扰，如含糊的列和难以理解的值，这不仅影响用户，也影响 Text-to-SQL 模型。本文利用大型语言模型 (LLM) 生成详尽的列描述，为关系数据库构建语义层。通过 BIRD-Bench 开发集，我们打造了 \textsc{ColSQL} 数据集，其中包含 LLM 与人工共同精炼的金标准列描述。评估显示，GPT-4o 和 Command R+ 在生成高质量描述方面表现卓越。我们还尝试用 LLM 作为评判来评估模型，尽管其结果与人类评估有差异，但此举旨在探索其潜力并寻求改进。为提升自动评估的可靠性，仍需更多研究。此外，详尽的列描述能显著提升 Text-to-SQL 的执行准确性，尤其是在列信息不明确时。本研究证实 LLM 是生成详细元数据、提升关系数据库可用性的有力工具。

> Relational databases often suffer from uninformative descriptors of table contents, such as ambiguous columns and hard-to-interpret values, impacting both human users and Text-to-SQL models. This paper explores the use of large language models (LLMs) to generate informative column descriptions as a semantic layer for relational databases. Using the BIRD-Bench development set, we created \textsc{ColSQL}, a dataset with gold-standard column descriptions generated and refined by LLMs and human annotators. We evaluated several instruction-tuned models, finding that GPT-4o and Command R+ excelled in generating high-quality descriptions. Additionally, we applied an LLM-as-a-judge to evaluate model performance. Although this method does not align well with human evaluations, we included it to explore its potential and to identify areas for improvement. More work is needed to improve the reliability of automatic evaluations for this task. We also find that detailed column descriptions significantly improve Text-to-SQL execution accuracy, especially when columns are uninformative. This study establishes LLMs as effective tools for generating detailed metadata, enhancing the usability of relational databases.

[Arxiv](https://arxiv.org/abs/2408.04691)