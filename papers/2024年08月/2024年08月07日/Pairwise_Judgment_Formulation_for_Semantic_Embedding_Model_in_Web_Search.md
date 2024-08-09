# Web 搜索中语义嵌入模型的配对判断方法

发布时间：2024年08月07日

`LLM应用` `搜索引擎`

> Pairwise Judgment Formulation for Semantic Embedding Model in Web Search

# 摘要

> SEM，一种基于神经网络的孪生架构，正逐渐在信息检索和自然语言处理领域崭露头角。为实现SEM在网络搜索中的监督训练，通常借助搜索引擎的查询日志自动生成成对判断作为训练数据。尽管语义嵌入技术在搜索引擎行业中应用广泛，但关于如何为SEM训练制定有效成对判断的研究却寥寥无几。本文首次深入探讨了多种生成SEM成对判断的策略，并揭示了一个有趣的现象：在成对学习排序领域广泛采用的传统成对判断策略，对SEM训练未必有效。通过基于大型商业搜索引擎的查询日志和用户点击行为进行的大规模实证研究，我们验证了SEM的有效训练策略，并指出混合启发式（如点击优先于未点击）相较于传统LTR中的原子启发式（如点击优先于跳过）更具优势。最后，我们总结了训练SEM的最佳实践，并展望了未来研究的方向。

> Semantic Embedding Model (SEM), a neural network-based Siamese architecture, is gaining momentum in information retrieval and natural language processing. In order to train SEM in a supervised fashion for Web search, the search engine query log is typically utilized to automatically formulate pairwise judgments as training data. Despite the growing application of semantic embeddings in the search engine industry, little work has been done on formulating effective pairwise judgments for training SEM. In this paper, we make the first in-depth investigation of a wide range of strategies for generating pairwise judgments for SEM. An interesting (perhaps surprising) discovery reveals that the conventional pairwise judgment formulation strategy wildly used in the field of pairwise Learning-to-Rank (LTR) is not necessarily effective for training SEM. Through a large-scale empirical study based on query logs and click-through activities from a major commercial search engine, we demonstrate the effective strategies for SEM and highlight the advantages of a hybrid heuristic (i.e., Clicked > Non-Clicked) in comparison to the atomic heuristics (e.g., Clicked > Skipped) in LTR. We conclude with best practices for training SEM and offer promising insights for future research.

[Arxiv](https://arxiv.org/abs/2408.04197)