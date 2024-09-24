# PTD-SQL: 利用 LLMs 在 Text-to-SQL 中实现分区和精准钻取

发布时间：2024年09月21日

`LLM应用` `数据库` `人工智能`

> PTD-SQL: Partitioning and Targeted Drilling with LLMs in Text-to-SQL

# 摘要

> LLM 在 Text-to-SQL 任务中表现出色，但 SQL 解决方案的固定模式引发了一个问题：LLM 能否通过分类思维提升性能？我们提出，通过查询组分区，LLM 可以更专注于特定问题类型的思维过程，从而在不同难度和类别中提升推理能力。实验显示，PTD-SQL 使多个高级 LLM 在 Spider 和 BIRD 数据集上达到或超越了 SOTA 方法。更有趣的是，不同基础的模型在针对性训练后，其能力边界处均有显著提升，这与人类学习过程相似。代码已开源，详见 https://github.com/lrlbbzl/PTD-SQL。

> Large Language Models (LLMs) have emerged as powerful tools for Text-to-SQL tasks, exhibiting remarkable reasoning capabilities. Different from tasks such as math word problems and commonsense reasoning, SQL solutions have a relatively fixed pattern. This facilitates the investigation of whether LLMs can benefit from categorical thinking, mirroring how humans acquire knowledge through inductive reasoning based on comparable examples. In this study, we propose that employing query group partitioning allows LLMs to focus on learning the thought processes specific to a single problem type, consequently enhancing their reasoning abilities across diverse difficulty levels and problem categories. Our experiments reveal that multiple advanced LLMs, when equipped with PTD-SQL, can either surpass or match previous state-of-the-art (SOTA) methods on the Spider and BIRD datasets. Intriguingly, models with varying initial performances have exhibited significant improvements, mainly at the boundary of their capabilities after targeted drilling, suggesting a parallel with human progress. Code is available at https://github.com/lrlbbzl/PTD-SQL.

[Arxiv](https://arxiv.org/abs/2409.14082)