# UniAdapt：知识校准的万能适配器

发布时间：2024年10月01日

`LLM应用` `人工智能` `知识管理`

> UniAdapt: A Universal Adapter for Knowledge Calibration

# 摘要

> 为了跟上知识的快速更新，大型语言模型 (LLM) 需要频繁更新。然而，直接插入新知识容易引发冲突，甚至破坏原有知识。为此，我们推出了 UniAdapt，一种专为知识校准设计的通用适配器。UniAdapt 借鉴了专家混合与检索增强生成的理念，通过向量辅助路由器，智能地将输入导向合适的专家。其向量存储系统，包含多个分片，能基于语义相似性进行高效搜索。UniAdapt 设计灵活，可无缝集成于各类模型。实验证明，UniAdapt 在终身模型编辑方面表现卓越，大幅超越现有方法，并在多项指标上取得优异成绩。

> Large Language Models (LLMs) require frequent updates to correct errors and keep pace with continuously evolving knowledge in a timely and effective manner. Recent research in it model editing has highlighted the challenges in balancing generalization and locality, especially in the context of lifelong model editing. We discover that inserting knowledge directly into the model often causes conflicts and potentially disrupts other unrelated pre-trained knowledge. To address this problem, we introduce UniAdapt, a universal adapter for knowledge calibration. Inspired by the Mixture of Experts architecture and Retrieval-Augmented Generation, UniAdapt is designed with a vector-assisted router that is responsible for routing inputs to appropriate experts. The router maintains a vector store, including multiple shards, to construct routing vectors based on semantic similarity search results. UniAdapt is fully model-agnostic and designed for seamless plug-and-play integration. Experimental results show that UniAdapt outperforms existing lifelong model editors and achieves exceptional results in most metrics.

[Arxiv](https://arxiv.org/abs/2410.00454)