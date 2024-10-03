# 旅行目的地推荐中的广泛与间接查询，通过详细子主题查询重构来优化。

发布时间：2024年10月02日

`LLM应用` `推荐系统`

> Elaborative Subtopic Query Reformulation for Broad and Indirect Queries in Travel Destination Recommendation

# 摘要

> 在旅行推荐系统中，理解用户复杂的查询意图至关重要，如“适合年轻人的活动”或“高中毕业旅行”。这些查询因潜在意图的广泛和微妙而具挑战性，现有的查询重构方法往往只关注查询的广度或深度，而非两者兼顾。本文提出详细子主题查询重构 (EQR)，通过生成信息丰富的子主题来结合广度和深度，显著提升召回率和精确度。同时，我们发布了新数据集 TravelDest，为旅行推荐系统提供更强大的支持。

> In Query-driven Travel Recommender Systems (RSs), it is crucial to understand the user intent behind challenging natural language(NL) destination queries such as the broadly worded "youth-friendly activities" or the indirect description "a high school graduation trip". Such queries are challenging due to the wide scope and subtlety of potential user intents that confound the ability of retrieval methods to infer relevant destinations from available textual descriptions such as WikiVoyage. While query reformulation (QR) has proven effective in enhancing retrieval by addressing user intent, existing QR methods tend to focus only on expanding the range of potentially matching query subtopics (breadth) or elaborating on the potential meaning of a query (depth), but not both. In this paper, we introduce Elaborative Subtopic Query Reformulation (EQR), a large language model-based QR method that combines both breadth and depth by generating potential query subtopics with information-rich elaborations. We also release TravelDest, a novel dataset for query-driven travel destination RSs. Experiments on TravelDest show that EQR achieves significant improvements in recall and precision over existing state-of-the-art QR methods.

[Arxiv](https://arxiv.org/abs/2410.01598)