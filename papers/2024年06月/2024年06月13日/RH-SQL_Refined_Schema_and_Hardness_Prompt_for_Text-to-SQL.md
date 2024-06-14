# RH-SQL：优化文本至SQL的精细架构与难度引导

发布时间：2024年06月13日

`Agent

理由：这篇论文主要介绍了一种新的 Text-to-SQL 方法，该方法通过结合精炼模式和硬度提示来提高性能并降低成本。这种方法可以被视为一种智能代理（Agent），因为它能够处理自然语言查询并将其转换为 SQL 语言，执行特定的任务（即生成 SQL 查询）。虽然这种方法使用了语言模型（LM），但其重点在于开发一种有效的技术来处理特定的任务，而不是深入探讨语言模型本身的理论或应用。因此，将其归类为Agent更为合适。` `数据库`

> RH-SQL: Refined Schema and Hardness Prompt for Text-to-SQL

# 摘要

> Text-to-SQL 技术能将自然语言查询转化为 SQL 语言。近期，一种基于 SQL 查询复杂性的研究方法备受瞩目，显著提升了性能。但这些方法的存储和训练成本高昂，限制了其实际应用。为此，本文提出了一种结合精炼模式和硬度提示的 Text-to-SQL 方法。该方法通过精炼模式筛选无关信息，利用语言模型识别查询难度，从而在保持性能的同时降低成本。此方法适用于所有 seq2seq LM。在 Spider 数据集上，特别是大规模 LM 的实验中，我们达到了 82.6% 的执行准确率，充分展示了该方法在实际应用中的高效性和广泛适用性。

> Text-to-SQL is a technology that converts natural language queries into the structured query language SQL. A novel research approach that has recently gained attention focuses on methods based on the complexity of SQL queries, achieving notable performance improvements. However, existing methods entail significant storage and training costs, which hampers their practical application. To address this issue, this paper introduces a method for Text-to-SQL based on Refined Schema and Hardness Prompt. By filtering out low-relevance schema information with a refined schema and identifying query hardness through a Language Model (LM) to form prompts, this method reduces storage and training costs while maintaining performance. It's worth mentioning that this method is applicable to any sequence-to-sequence (seq2seq) LM. Our experiments on the Spider dataset, specifically with large-scale LMs, achieved an exceptional Execution accuracy (EX) of 82.6%, demonstrating the effectiveness and greater suitability of our method for real-world applications.

[Arxiv](https://arxiv.org/abs/2406.09133)