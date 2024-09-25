# 开启市场之门：多语言问答的跨市场基准

发布时间：2024年09月24日

`LLM应用` `问答系统`

> Unlocking Markets: A Multilingual Benchmark to Cross-Market Question Answering

# 摘要

> 在电商平台上，用户常提出大量产品相关问题，影响购买决策。我们提出多语言跨市场产品问答（MCPQA）任务，即利用资源丰富的辅助市场信息，在主市场中回答产品相关问题。我们构建了包含700多万问题的大规模数据集McMarket，涵盖11种语言的17个市场。重点研究基于评论的答案生成和产品问题排名两项子任务，通过LLM标注并经人工评估。实验表明，跨市场信息的引入显著提升了任务表现。

> Users post numerous product-related questions on e-commerce platforms, affecting their purchase decisions. Product-related question answering (PQA) entails utilizing product-related resources to provide precise responses to users. We propose a novel task of Multilingual Cross-market Product-based Question Answering (MCPQA) and define the task as providing answers to product-related questions in a main marketplace by utilizing information from another resource-rich auxiliary marketplace in a multilingual context. We introduce a large-scale dataset comprising over 7 million questions from 17 marketplaces across 11 languages. We then perform automatic translation on the Electronics category of our dataset, naming it as McMarket. We focus on two subtasks: review-based answer generation and product-related question ranking. For each subtask, we label a subset of McMarket using an LLM and further evaluate the quality of the annotations via human assessment. We then conduct experiments to benchmark our dataset, using models ranging from traditional lexical models to LLMs in both single-market and cross-market scenarios across McMarket and the corresponding LLM subset. Results show that incorporating cross-market information significantly enhances performance in both tasks.

[Arxiv](https://arxiv.org/abs/2409.16025)