# 利用大型语言模型打造智能查询推荐

发布时间：2024年05月30日

`RAG

理由：这篇论文介绍了一种基于大型语言模型（LLM）的生成查询推荐（GQR）方法，并进一步开发了检索增强型GQR（RA-GQR）。这种方法通过动态检索相似查询来优化提示，显著提升了查询推荐系统的性能。由于论文主要关注的是利用LLM进行检索增强的查询推荐，这与RAG（Retrieval-Augmented Generation）的概念相符，即通过检索机制增强生成模型的性能。因此，将其分类为RAG。` `搜索引擎` `查询推荐`

> Generating Query Recommendations via LLMs

# 摘要

> 在现代搜索引擎中，查询推荐系统无处不在，它们助力用户精准获取信息。但这些系统依赖大量数据，如海量文档和查询日志，才能提供优质推荐。特别是在冷启动情况下，查询日志和用户数据难以获取。为此，我们提出了一种创新的生成查询推荐（GQR）方法，它基于LLM，无需额外训练即可工作。我们设计的提示让LLM能够理解并执行推荐任务，即便仅有一个示例。进一步地，我们开发了检索增强型GQR（RA-GQR），它从查询日志中动态检索相似查询以优化提示。GQR方法简化了流程，使其更易于推向市场，即使在冷启动场景下也表现出色。我们的GQR在NDCG@10和清晰度评分上达到了行业领先水平，与两大商业搜索引擎及之前的方法相比，在Robust04和ClueWeb09B数据集上平均提升了约4%的NDCG@10性能。RA-GQR更进一步，将NDCG@10性能分别提升了约11%和6%。此外，在用户盲测中，我们的系统赢得了约59%的用户青睐，证明了其生成的查询极具吸引力。

> Query recommendation systems are ubiquitous in modern search engines, assisting users in producing effective queries to meet their information needs. However, these systems require a large amount of data to produce good recommendations, such as a large collection of documents to index and query logs. In particular, query logs and user data are not available in cold start scenarios. Query logs are expensive to collect and maintain and require complex and time-consuming cascading pipelines for creating, combining, and ranking recommendations. To address these issues, we frame the query recommendation problem as a generative task, proposing a novel approach called Generative Query Recommendation (GQR). GQR uses an LLM as its foundation and does not require to be trained or fine-tuned to tackle the query recommendation problem. We design a prompt that enables the LLM to understand the specific recommendation task, even using a single example. We then improved our system by proposing a version that exploits query logs called Retriever-Augmented GQR (RA-GQR). RA-GQr dynamically composes its prompt by retrieving similar queries from query logs. GQR approaches reuses a pre-existing neural architecture resulting in a simpler and more ready-to-market approach, even in a cold start scenario. Our proposed GQR obtains state-of-the-art performance in terms of NDCG@10 and clarity score against two commercial search engines and the previous state-of-the-art approach on the Robust04 and ClueWeb09B collections, improving on average the NDCG@10 performance up to ~4% on Robust04 and ClueWeb09B w.r.t the previous best competitor. RA-GQR further improve the NDCG@10 obtaining an increase of ~11%, ~6\% on Robust04 and ClueWeb09B w.r.t the best competitor. Furthermore, our system obtained ~59% of user preferences in a blind user study, proving that our method produces the most engaging queries.

[Arxiv](https://arxiv.org/abs/2405.19749)