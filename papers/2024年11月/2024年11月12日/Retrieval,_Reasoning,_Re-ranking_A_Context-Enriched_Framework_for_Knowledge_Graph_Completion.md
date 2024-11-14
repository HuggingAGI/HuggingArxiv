# 检索、推理、重新排序：一个用于知识图谱补全的上下文丰富框架

发布时间：2024年11月12日

`LLM应用` `知识图谱` `人工智能`

> Retrieval, Reasoning, Re-ranking: A Context-Enriched Framework for Knowledge Graph Completion

# 摘要

> 知识图谱补全（KGC）任务旨在从不完整的三元组中推断缺失的实体。现有的基于嵌入的方法仅依赖于知识图谱中的三元组，这容易受到虚假关系模式和长尾实体的影响。另一方面，基于文本的方法在处理知识图谱三元组和自然语言之间的语义差距方面存在困难。除了三元组，实体上下文（例如标签、描述、别名）在扩充知识图谱方面也发挥着重要作用。为了解决这些限制，我们提出了 KGR3，一个用于知识图谱补全的上下文丰富框架。KGR3 由三个模块组成。首先，检索模块从知识图谱中收集支持三元组，从基础嵌入模型中收集合理的候选答案，并为每个相关实体检索上下文。然后，推理模块使用大型语言模型为每个查询三元组生成潜在答案。最后，重排序模块结合上述两个模块的候选答案，并微调一个大型语言模型以提供最佳答案。在广泛使用的数据集上进行的大量实验表明，KGR3 持续改进了各种知识图谱补全方法。具体而言，KGR3 的最佳变体在 FB15k237 和 WN18RR 数据集上分别实现了绝对 Hits@1 提升 12.3％和 5.6％。

> The Knowledge Graph Completion~(KGC) task aims to infer the missing entity from an incomplete triple. Existing embedding-based methods rely solely on triples in the KG, which is vulnerable to specious relation patterns and long-tail entities. On the other hand, text-based methods struggle with the semantic gap between KG triples and natural language. Apart from triples, entity contexts (e.g., labels, descriptions, aliases) also play a significant role in augmenting KGs. To address these limitations, we propose KGR3, a context-enriched framework for KGC. KGR3 is composed of three modules. Firstly, the Retrieval module gathers supporting triples from the KG, collects plausible candidate answers from a base embedding model, and retrieves context for each related entity. Then, the Reasoning module employs a large language model to generate potential answers for each query triple. Finally, the Re-ranking module combines candidate answers from the two modules mentioned above, and fine-tunes an LLM to provide the best answer. Extensive experiments on widely used datasets demonstrate that KGR3 consistently improves various KGC methods. Specifically, the best variant of KGR3 achieves absolute Hits@1 improvements of 12.3% and 5.6% on the FB15k237 and WN18RR datasets.

[Arxiv](https://arxiv.org/abs/2411.08165)