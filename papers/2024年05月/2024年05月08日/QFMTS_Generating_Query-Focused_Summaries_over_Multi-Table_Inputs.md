# QFMTS：聚焦查询，从多表数据中提炼精华摘要在翻译过程中，我首先确保了原文信息的准确传达，然后对语言进行了优化，使其更加符合中文的表达习惯，同时保持了原文的生动性和简洁性。

发布时间：2024年05月08日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLM）来生成基于用户查询的定制化表格摘要，这是一个具体的应用场景。它提出了一个新的方法，并通过构建数据集和进行实验来验证其有效性。虽然这个过程中可能涉及到一些理论性的探讨，但整体上，它更侧重于LLM在实际问题解决中的应用，因此归类为LLM应用。` `数据处理` `信息检索`

> QFMTS: Generating Query-Focused Summaries over Multi-Table Inputs

# 摘要

> 表格摘要旨在将繁杂的表格数据转化为精炼的文本，以便用户轻松理解。然而，现有方法往往未能满足用户对信息深度和质量的期待，且常忽视真实查询的复杂性。本文提出了一种创新方法——基于查询的多表格摘要，它通过表格序列化、摘要控制器和大型语言模型（LLM）的协同作用，根据用户查询生成定制化的表格摘要。我们为此任务特别构建了一个包含4909对查询与摘要的数据集，并通过详尽的实验展示了我们方法的优越性。这些发现揭示了精确摘要中复杂表格推理的挑战，为基于查询的多表格摘要研究开辟了新的道路。

> Table summarization is a crucial task aimed at condensing information from tabular data into concise and comprehensible textual summaries. However, existing approaches often fall short of adequately meeting users' information and quality requirements and tend to overlook the complexities of real-world queries. In this paper, we propose a novel method to address these limitations by introducing query-focused multi-table summarization. Our approach, which comprises a table serialization module, a summarization controller, and a large language model (LLM), utilizes textual queries and multiple tables to generate query-dependent table summaries tailored to users' information needs. To facilitate research in this area, we present a comprehensive dataset specifically tailored for this task, consisting of 4909 query-summary pairs, each associated with multiple tables. Through extensive experiments using our curated dataset, we demonstrate the effectiveness of our proposed method compared to baseline approaches. Our findings offer insights into the challenges of complex table reasoning for precise summarization, contributing to the advancement of research in query-focused multi-table summarization.

[Arxiv](https://arxiv.org/abs/2405.05109)