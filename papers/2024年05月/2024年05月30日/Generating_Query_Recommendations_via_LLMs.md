# 利用大型语言模型生成查询推荐

发布时间：2024年05月30日

`LLM应用

这篇论文摘要描述了一种基于大型语言模型（LLM）的生成查询推荐（GQR）方法，该方法旨在解决现代搜索引擎中查询推荐系统的挑战，特别是在冷启动情况下。GQR方法利用LLM的能力，通过精心设计的提示来生成推荐，无需额外训练。此外，论文还介绍了RA-GQR版本，它通过动态检索相似查询来进一步优化提示。这种方法在性能上超越了现有的商业搜索引擎和其他方法，在多个数据集上提升了NDCG@10性能，并在用户盲测中获得了高满意度。因此，这篇论文属于LLM应用类别，因为它展示了LLM在实际应用中的有效性和创新性使用。` `搜索引擎` `查询推荐`

> Generating Query Recommendations via LLMs

# 摘要

> 在现代搜索引擎中，查询推荐系统如影随形，助力用户精准获取信息。但这些系统依赖海量数据，如庞大的文档库和查询日志，以提供优质推荐。尤其在冷启动情况下，查询日志和用户数据难以获取。为此，我们创新性地将查询推荐视为生成任务，推出了生成查询推荐（GQR）这一新颖方法。GQR以LLM为基石，无需额外训练即可应对挑战。我们精心设计的提示让LLM能够理解并执行推荐任务，即便仅凭单一示例。随后，我们推出了利用查询日志的RA-GQR版本，它通过动态检索相似查询来优化提示。GQR方法简化了流程，重用现有神经架构，使其在冷启动场景中也能迅速市场化。我们的GQR在NDCG@10和清晰度评分上刷新了记录，与两大商业搜索引擎及之前最佳方法相比，在Robust04和ClueWeb09B数据集上平均提升了约4%的NDCG@10性能。RA-GQR更上一层楼，分别提升了约11%和6%。在盲测中，我们的系统赢得了59%用户的青睐，证明了其生成的查询最具吸引力。

> Query recommendation systems are ubiquitous in modern search engines, assisting users in producing effective queries to meet their information needs. However, these systems require a large amount of data to produce good recommendations, such as a large collection of documents to index and query logs. In particular, query logs and user data are not available in cold start scenarios. Query logs are expensive to collect and maintain and require complex and time-consuming cascading pipelines for creating, combining, and ranking recommendations. To address these issues, we frame the query recommendation problem as a generative task, proposing a novel approach called Generative Query Recommendation (GQR). GQR uses an LLM as its foundation and does not require to be trained or fine-tuned to tackle the query recommendation problem. We design a prompt that enables the LLM to understand the specific recommendation task, even using a single example. We then improved our system by proposing a version that exploits query logs called Retriever-Augmented GQR (RA-GQR). RA-GQr dynamically composes its prompt by retrieving similar queries from query logs. GQR approaches reuses a pre-existing neural architecture resulting in a simpler and more ready-to-market approach, even in a cold start scenario. Our proposed GQR obtains state-of-the-art performance in terms of NDCG@10 and clarity score against two commercial search engines and the previous state-of-the-art approach on the Robust04 and ClueWeb09B collections, improving on average the NDCG@10 performance up to ~4% on Robust04 and ClueWeb09B w.r.t the previous best competitor. RA-GQR further improve the NDCG@10 obtaining an increase of ~11%, ~6\% on Robust04 and ClueWeb09B w.r.t the best competitor. Furthermore, our system obtained ~59% of user preferences in a blind user study, proving that our method produces the most engaging queries.

[Arxiv](https://arxiv.org/abs/2405.19749)