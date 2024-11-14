# XiYan-SQL：用于文本到 SQL 的多生成器集成框架

发布时间：2024年11月13日

`LLM应用` `数据库`

> XiYan-SQL: A Multi-Generator Ensemble Framework for Text-to-SQL

# 摘要

> 为了解决大型语言模型在自然语言到 SQL 任务中的性能挑战，我们引入了 XiYan-SQL，这是一个采用多生成器集成策略来改进候选生成的创新框架。我们引入了 M-Schema，这是一种旨在增强对数据库结构理解的半结构化模式表示方法。为了提高生成的候选 SQL 查询的质量和多样性，XiYan-SQL 将上下文学习（ICL）的巨大潜力与监督微调的精确控制相结合。一方面，我们提出了一系列训练策略来微调模型，以生成具有不同偏好的高质量候选。另一方面，我们通过基于命名实体识别的示例选择方法来实现 ICL 方法，以防止对实体的过度强调。优化器通过纠正逻辑或语法错误来优化每个候选。为了解决识别最佳候选的挑战，我们微调了一个选择模型来区分候选 SQL 查询的细微差别。在多个方言数据集上的实验结果表明，XiYan-SQL 在应对不同场景的挑战方面具有鲁棒性。总的来说，我们提出的 XiYan-SQL 在 Spider 测试集上达到了 89.65％的最先进执行准确率，在 SQL-Eval 上达到 69.86％，在 NL2GQL 上达到 41.20％，在 Bird 开发基准上获得了具有竞争力的 72.23％的分数。所提出的框架不仅提高了 SQL 查询的质量和多样性，而且优于以前的方法。

> To tackle the challenges of large language model performance in natural language to SQL tasks, we introduce XiYan-SQL, an innovative framework that employs a multi-generator ensemble strategy to improve candidate generation. We introduce M-Schema, a semi-structured schema representation method designed to enhance the understanding of database structures. To enhance the quality and diversity of generated candidate SQL queries, XiYan-SQL integrates the significant potential of in-context learning (ICL) with the precise control of supervised fine-tuning. On one hand, we propose a series of training strategies to fine-tune models to generate high-quality candidates with diverse preferences. On the other hand, we implement the ICL approach with an example selection method based on named entity recognition to prevent overemphasis on entities. The refiner optimizes each candidate by correcting logical or syntactical errors. To address the challenge of identifying the best candidate, we fine-tune a selection model to distinguish nuances of candidate SQL queries. The experimental results on multiple dialect datasets demonstrate the robustness of XiYan-SQL in addressing challenges across different scenarios. Overall, our proposed XiYan-SQL achieves the state-of-the-art execution accuracy of 89.65% on the Spider test set, 69.86% on SQL-Eval, 41.20% on NL2GQL, and a competitive score of 72.23% on the Bird development benchmark. The proposed framework not only enhances the quality and diversity of SQL queries but also outperforms previous methods.

[Arxiv](https://arxiv.org/abs/2411.08599)