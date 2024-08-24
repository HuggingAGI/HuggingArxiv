# 圆桌会议：通过动态模式与上下文自动补全，提升表格问答查询的精准度

发布时间：2024年08月22日

`LLM应用` `数据库` `信息技术`

> RoundTable: Leveraging Dynamic Schema and Contextual Autocomplete for Enhanced Query Precision in Tabular Question Answering

# 摘要

> 随着 LLM 的发展，用简单英语查询数据库已成为主要应用之一，它能将用户提问转化为可执行的数据库查询，效果显著提升。但现实数据集的多样性和复杂性给 LLM 带来了挑战，传统方法难以全面展现数据集的复杂性。为此，我们提出了一种结合全文搜索的新框架，不仅能精准定位数据，还能简化搜索过程，提升查询准确性。此外，该框架还支持智能自动补全，根据数据内容推荐查询，极大优化了用户与复杂数据集的互动体验。我们还开发了跨平台的应用程序，供读者在个人数据上亲自体验。

> With advancements in Large Language Models (LLMs), a major use case that has emerged is querying databases in plain English, translating user questions into executable database queries, which has improved significantly. However, real-world datasets often feature a vast array of attributes and complex values, complicating the LLMs task of accurately identifying relevant columns or values from natural language queries. Traditional methods cannot fully relay the datasets size and complexity to the LLM. To address these challenges, we propose a novel framework that leverages Full-Text Search (FTS) on the input table. This approach not only enables precise detection of specific values and columns but also narrows the search space for language models, thereby enhancing query accuracy. Additionally, it supports a custom auto-complete feature that suggests queries based on the data in the table. This integration significantly refines the interaction between the user and complex datasets, offering a sophisticated solution to the limitations faced by current table querying capabilities. This work is accompanied by an application for both Mac and Windows platforms, which readers can try out themselves on their own data.

[Arxiv](https://arxiv.org/abs/2408.12369)