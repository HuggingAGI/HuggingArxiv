# IRLab@iKAT24：利用多方面 LLM 查询生成的学习型稀疏检索服务于对话式搜索

发布时间：2024年11月22日

`LLM应用` `对话助手` `个性化搜索`

> IRLab@iKAT24: Learned Sparse Retrieval with Multi-aspect LLM Query Generation for Conversational Search

# 摘要

> 2024 年的交互式知识助手赛道（iKAT）致力于推动对话助手的发展，使其能够依据个性化的用户知识来调整交互和回应。该赛道融合了个人文本知识库（PTKB）以及诸如段落排序和响应生成之类的对话式人工智能任务。鉴于查询重写是解决对话情境的有效手段，我们将大型语言模型（LLMs）用作查询重写器进行探索。具体来说，我们提交的运行借助 MQ4CS 框架探索多方面的查询生成，还通过 SPLADE 架构进一步强化了学习到的稀疏检索，并搭配了强大的交叉编码器模型。此外，我们提出了一种不同于以往交错策略的方法，在重新排名阶段聚合多个方面。我们的发现表明，多方面的查询生成与先进的检索和重新排名模型相结合时，能够有效地提升性能。我们的成果也为对话式搜索中的更优个性化指明了方向，依靠 LLMs 在查询重写中融入个性化，其表现优于人类重写的性能。

> The Interactive Knowledge Assistant Track (iKAT) 2024 focuses on advancing conversational assistants, able to adapt their interaction and responses from personalized user knowledge. The track incorporates a Personal Textual Knowledge Base (PTKB) alongside Conversational AI tasks, such as passage ranking and response generation. Query Rewrite being an effective approach for resolving conversational context, we explore Large Language Models (LLMs), as query rewriters. Specifically, our submitted runs explore multi-aspect query generation using the MQ4CS framework, which we further enhance with Learned Sparse Retrieval via the SPLADE architecture, coupled with robust cross-encoder models. We also propose an alternative to the previous interleaving strategy, aggregating multiple aspects during the reranking phase. Our findings indicate that multi-aspect query generation is effective in enhancing performance when integrated with advanced retrieval and reranking models. Our results also lead the way for better personalization in Conversational Search, relying on LLMs to integrate personalization within query rewrite, and outperforming human rewrite performance.

[Arxiv](https://arxiv.org/abs/2411.14739)