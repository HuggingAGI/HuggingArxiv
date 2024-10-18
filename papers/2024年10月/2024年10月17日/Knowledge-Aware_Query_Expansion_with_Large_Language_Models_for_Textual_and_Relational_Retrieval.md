# 利用大型语言模型进行知识感知的查询扩展，应用于文本与关系检索

发布时间：2024年10月17日

`LLM应用` `信息检索` `知识图谱`

> Knowledge-Aware Query Expansion with Large Language Models for Textual and Relational Retrieval

# 摘要

> 大型语言模型 (LLM) 已被用于生成查询扩展，以改进信息搜索。最近的研究还探索了向 LLM 提供初始检索结果，以生成更基于文档语料库的查询扩展。然而，这些方法大多侧重于增强文本相似性，而忽略了文档关系。对于类似“为我找到一款适合野生动物摄影的高评分相机，兼容我的尼康 F 卡口镜头”的查询，现有方法可能会生成语义相似但结构上与用户意图无关的扩展。为了处理这种既包含文本又包含关系要求的半结构化查询，本文提出了一种知识感知的查询扩展框架，通过知识图谱 (KG) 中的结构化文档关系来增强 LLM。为了进一步解决现有基于 KG 的方法中基于实体的评分限制，我们利用文档文本作为丰富的 KG 节点表示，并使用基于文档的关系过滤来进行我们的知识感知检索 (KAR)。在三个不同领域的数据集上的广泛实验表明，与最先进的基线相比，我们的方法在文本和关系半结构化检索方面具有优势。

> Large language models (LLMs) have been used to generate query expansions augmenting original queries for improving information search. Recent studies also explore providing LLMs with initial retrieval results to generate query expansions more grounded to document corpus. However, these methods mostly focus on enhancing textual similarities between search queries and target documents, overlooking document relations. For queries like "Find me a highly rated camera for wildlife photography compatible with my Nikon F-Mount lenses", existing methods may generate expansions that are semantically similar but structurally unrelated to user intents. To handle such semi-structured queries with both textual and relational requirements, in this paper we propose a knowledge-aware query expansion framework, augmenting LLMs with structured document relations from knowledge graph (KG). To further address the limitation of entity-based scoring in existing KG-based methods, we leverage document texts as rich KG node representations and use document-based relation filtering for our Knowledge-Aware Retrieval (KAR). Extensive experiments on three datasets of diverse domains show the advantages of our method compared against state-of-the-art baselines on textual and relational semi-structured retrieval.

[Arxiv](https://arxiv.org/abs/2410.13765)