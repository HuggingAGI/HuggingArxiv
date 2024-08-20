# AutoML 引导下的实体与 LLM 表示融合

发布时间：2024年08月19日

`LLM应用` `人工智能` `机器学习`

> AutoML-guided Fusion of Entity and LLM-based representations

# 摘要

> 大型语义知识库依赖于事实知识，但当前的密集文本表示方法并未充分利用这些资源。为了有效应对下游分类和检索任务，我们需要密集且健壮的文档表示。本研究揭示，引入知识库的嵌入信息能显著提升LLM在文本分类中的表现。通过融合表示空间并应用自动化机器学习，我们进一步证明，即便在低维投影中，也能提升分类准确性。这一发现意味着，我们可以在几乎不牺牲预测性能的前提下，实现更快速的分类器，这在六个不同真实数据集上的五个LLM基线测试中得到了验证。

> Large semantic knowledge bases are grounded in factual knowledge. However, recent approaches to dense text representations (embeddings) do not efficiently exploit these resources. Dense and robust representations of documents are essential for effectively solving downstream classification and retrieval tasks. This work demonstrates that injecting embedded information from knowledge bases can augment the performance of contemporary Large Language Model (LLM)-based representations for the task of text classification. Further, by considering automated machine learning (AutoML) with the fused representation space, we demonstrate it is possible to improve classification accuracy even if we use low-dimensional projections of the original representation space obtained via efficient matrix factorization. This result shows that significantly faster classifiers can be achieved with minimal or no loss in predictive performance, as demonstrated using five strong LLM baselines on six diverse real-life datasets.

[Arxiv](https://arxiv.org/abs/2408.09794)