# 为什么是这些文档？具有分层类别路径的可解释生成式检索

发布时间：2024年11月08日

`LLM应用` `信息检索` `文档处理`

> Why These Documents? Explainable Generative Retrieval with Hierarchical Category Paths

# 摘要

> 生成式检索最近已成为传统信息检索方法的一种新的替代方案。然而，现有的生成式检索方法在给出查询时直接解码文档 ID，这使得无法为用户提供解释作为“为什么检索此文档？”的答案。为了解决这个限制，我们提出了分层类别路径增强生成式检索（HyPE），它通过在解码文档 ID 之前逐步生成分层类别路径来增强可解释性。HyPE 利用分层类别路径作为解释，从宽泛到特定的语义类别逐步推进。这种方法通过使用查询和文档之间的共享类别路径，根据查询为同一文档提供不同的解释，并通过从粗到细的方式反映文档的语义结构提供合理的解释。HyPE 利用外部高质量语义层次结构构建类别路径，利用大型语言模型为每个文档选择合适的候选路径，并使用路径增强数据集优化生成式检索模型。在推理过程中，HyPE 利用路径感知重排序策略聚合各种主题信息，使最相关的文档在最终的文档 ID 排名列表中优先排序。我们的大量实验表明，HyPE 不仅提供了高度的可解释性，而且在文档检索任务中提高了检索性能。

> Generative retrieval has recently emerged as a new alternative of traditional information retrieval approaches. However, existing generative retrieval methods directly decode docid when a query is given, making it impossible to provide users with explanations as an answer for "Why this document is retrieved?". To address this limitation, we propose Hierarchical Category Path-Enhanced Generative Retrieval(HyPE), which enhances explainability by generating hierarchical category paths step-by-step before decoding docid. HyPE leverages hierarchical category paths as explanation, progressing from broad to specific semantic categories. This approach enables diverse explanations for the same document depending on the query by using shared category paths between the query and the document, and provides reasonable explanation by reflecting the document's semantic structure through a coarse-to-fine manner. HyPE constructs category paths with external high-quality semantic hierarchy, leverages LLM to select appropriate candidate paths for each document, and optimizes the generative retrieval model with path-augmented dataset. During inference, HyPE utilizes path-aware reranking strategy to aggregate diverse topic information, allowing the most relevant documents to be prioritized in the final ranked list of docids. Our extensive experiments demonstrate that HyPE not only offers a high level of explainability but also improves the retrieval performance in the document retrieval task.

[Arxiv](https://arxiv.org/abs/2411.05572)