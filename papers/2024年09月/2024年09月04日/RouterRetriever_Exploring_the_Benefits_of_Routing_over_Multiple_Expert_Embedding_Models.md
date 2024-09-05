# RouterRetriever：探究多专家嵌入模型中路由的优势

发布时间：2024年09月04日

`LLM应用` `信息检索` `人工智能`

> RouterRetriever: Exploring the Benefits of Routing over Multiple Expert Embedding Models

# 摘要

> 信息检索常依赖于单一的通用嵌入模型，如MSMARCO。然而，特定领域的模型往往表现更佳。尽管多任务训练有所尝试，但结合多领域专家检索器的研究仍属空白。我们提出的RouterRetriever模型，通过集成多领域专家和智能路由机制，为每个查询精准匹配合适的专家，无需额外训练即可灵活调整专家库。在BEIR基准测试中，RouterRetriever显著超越了传统和多任务训练模型，其路由机制也优于现有技术。这一创新不仅在特定测试集上表现出色，其优势还能广泛适用于其他数据集，即便在缺乏特定领域专家的情况下。RouterRetriever首次证明了在检索任务中，多领域专家嵌入模型结合高效路由机制的显著优势，超越了传统的单一通用模型。

> Information retrieval methods often rely on a single embedding model trained on large, general-domain datasets like MSMARCO. While this approach can produce a retriever with reasonable overall performance, models trained on domain-specific data often yield better results within their respective domains. While prior work in information retrieval has tackled this through multi-task training, the topic of combining multiple domain-specific expert retrievers remains unexplored, despite its popularity in language model generation. In this work, we introduce RouterRetriever, a retrieval model that leverages multiple domain-specific experts along with a routing mechanism to select the most appropriate expert for each query. It is lightweight and allows easy addition or removal of experts without additional training. Evaluation on the BEIR benchmark demonstrates that RouterRetriever outperforms both MSMARCO-trained (+2.1 absolute nDCG@10) and multi-task trained (+3.2) models. This is achieved by employing our routing mechanism, which surpasses other routing techniques (+1.8 on average) commonly used in language modeling. Furthermore, the benefit generalizes well to other datasets, even in the absence of a specific expert on the dataset. To our knowledge, RouterRetriever is the first work to demonstrate the advantages of using multiple domain-specific expert embedding models with effective routing over a single, general-purpose embedding model in retrieval tasks.

[Arxiv](https://arxiv.org/abs/2409.02685)