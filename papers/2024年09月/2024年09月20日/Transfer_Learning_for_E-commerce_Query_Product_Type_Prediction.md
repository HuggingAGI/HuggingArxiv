# 电商查询产品类型预测中的迁移学习

发布时间：2024年09月20日

`LLM应用` `搜索技术`

> Transfer Learning for E-commerce Query Product Type Prediction

# 摘要

> 在电商搜索中，精准把握客户意图是关键。特别是，将搜索词与正确的商品类型匹配，能有效引导客户找到心仪商品。然而，查询商品类型分类（Q2PT）任务充满挑战，搜索词简短且模糊，商品类别繁多，涵盖数千种。国际市场还需应对语言、文化和方言差异带来的额外挑战。我们专注于全球多地区电商市场的Q2PT预测，发现单独为各地区训练模型在低资源市场表现不佳，且难以快速扩展至新市场。为此，我们提出从高资源地区向低资源地区进行迁移学习，以实现全球Q2PT性能的均衡。通过对比各地区模型与统一模型（共享全球数据和结构），以及地区感知与地区无关模型，我们发现，统一的地区感知Q2PT模型在全球20个地区的电商数据集上表现卓越，显著优于其他方案。

> Getting a good understanding of the customer intent is essential in e-commerce search engines. In particular, associating the correct product type to a search query plays a vital role in surfacing correct products to the customers. Query product type classification (Q2PT) is a particularly challenging task because search queries are short and ambiguous, the number of existing product categories is extremely large, spanning thousands of values. Moreover, international marketplaces face additional challenges, such as language and dialect diversity and cultural differences, influencing the interpretation of the query. In this work we focus on Q2PT prediction in the global multilocale e-commerce markets. The common approach of training Q2PT models for each locale separately shows significant performance drops in low-resource stores. Moreover, this method does not allow for a smooth expansion to a new country, requiring to collect the data and train a new locale-specific Q2PT model from scratch. To tackle this, we propose to use transfer learning from the highresource to the low-resource locales, to achieve global parity of Q2PT performance. We benchmark the per-locale Q2PT model against the unified one, which shares the training data and model structure across all worldwide stores. Additionally, we compare locale-aware and locale-agnostic Q2PT models, showing the task dependency on the country-specific traits. We conduct extensive quantiative and qualitative analysis of Q2PT models on the large-scale e-commerce dataset across 20 worldwide locales, which shows that unified locale-aware Q2PT model has superior performance over the alternatives.

[Arxiv](https://arxiv.org/abs/2410.07121)