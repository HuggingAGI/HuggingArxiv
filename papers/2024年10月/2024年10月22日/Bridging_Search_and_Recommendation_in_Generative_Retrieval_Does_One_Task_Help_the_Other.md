# 在生成式检索中架起搜索和推荐的桥梁：一项任务会对另一项任务有帮助吗？

发布时间：2024年10月22日

`LLM应用` `信息检索` `在线平台`

> Bridging Search and Recommendation in Generative Retrieval: Does One Task Help the Other?

# 摘要

> 用于搜索和推荐的生成式检索是一种很有前景的检索项目的范例，为依赖外部索引和最近邻搜索的传统方法提供了替代方案。相反，生成式模型直接将输入与项目 ID 相关联。鉴于大型语言模型（LLM）的突破，这些生成式系统可以在将各种信息检索（IR）任务集中在一个执行诸如查询理解、检索、推荐、解释、重新排序和响应生成等任务的单一模型中发挥关键作用。尽管对这种用于 IR 系统的统一生成式方法的兴趣日益浓厚，但在文献中，使用单个多任务模型相对于多个专门模型的优势尚未得到充分确立。本文研究了这种统一方法在搜索和推荐的 IR 任务中是否以及何时能够优于特定任务模型，这些任务广泛共存于多个工业在线平台，如 Spotify、YouTube 和 Netflix。先前的工作表明：（1）生成式推荐器学习到的项目的潜在表示偏向于流行度，（2）基于内容和基于协同过滤的信息可以改善项目的表示。受此启发，我们的研究以两个假设为指导：[H1]联合训练规范了每个项目的流行度估计，[H2]联合训练规范了项目的潜在表示，其中搜索捕获项目的基于内容的方面，推荐捕获协同过滤方面。我们对模拟和真实世界数据进行的大量实验都支持[H1]和[H2]是统一的搜索和推荐生成式模型相对于单任务方法所观察到的有效性改进的关键贡献因素。

> Generative retrieval for search and recommendation is a promising paradigm for retrieving items, offering an alternative to traditional methods that depend on external indexes and nearest-neighbor searches. Instead, generative models directly associate inputs with item IDs. Given the breakthroughs of Large Language Models (LLMs), these generative systems can play a crucial role in centralizing a variety of Information Retrieval (IR) tasks in a single model that performs tasks such as query understanding, retrieval, recommendation, explanation, re-ranking, and response generation. Despite the growing interest in such a unified generative approach for IR systems, the advantages of using a single, multi-task model over multiple specialized models are not well established in the literature. This paper investigates whether and when such a unified approach can outperform task-specific models in the IR tasks of search and recommendation, broadly co-existing in multiple industrial online platforms, such as Spotify, YouTube, and Netflix. Previous work shows that (1) the latent representations of items learned by generative recommenders are biased towards popularity, and (2) content-based and collaborative-filtering-based information can improve an item's representations. Motivated by this, our study is guided by two hypotheses: [H1] the joint training regularizes the estimation of each item's popularity, and [H2] the joint training regularizes the item's latent representations, where search captures content-based aspects of an item and recommendation captures collaborative-filtering aspects. Our extensive experiments with both simulated and real-world data support both [H1] and [H2] as key contributors to the effectiveness improvements observed in the unified search and recommendation generative models over the single-task approaches.

[Arxiv](https://arxiv.org/abs/2410.16823)