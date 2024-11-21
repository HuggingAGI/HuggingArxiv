# LLM-KT：一个实现从大型语言模型向协同过滤进行知识转移的通用框架

发布时间：2024年11月01日

`LLM应用` `推荐系统` `知识转移`

> LLM-KT: A Versatile Framework for Knowledge Transfer from Large Language Models to Collaborative Filtering

# 摘要

> 我们推出了 LLM-KT 这一灵活的框架，旨在将 LLM（大型语言模型）生成的特征无缝融入，从而增强协同过滤（CF）模型。现有的方法多是把 LLM 生成的特征直接作为输入，而我们的框架则把这些特征注入到任意 CF 模型的中间层，让模型能在内部重建和利用嵌入。这种不依赖特定模型的方法能适配各类 CF 模型，无需改变架构，适用于各种推荐场景。我们的框架易于集成和修改，为研究人员和开发人员提供了强大的工具，能通过高效的知识转移来拓展 CF 模型的能力。我们在 MovieLens 和 Amazon 数据集上进行的实验证明了其有效性，它不断提升了基线 CF 模型。实验研究显示，LLM-KT 在上下文感知的设定中能与最先进的方法媲美，而且能应用于比当前方法更广泛的 CF 模型。

> We present LLM-KT, a flexible framework designed to enhance collaborative filtering (CF) models by seamlessly integrating LLM (Large Language Model)-generated features. Unlike existing methods that rely on passing LLM-generated features as direct inputs, our framework injects these features into an intermediate layer of any CF model, allowing the model to reconstruct and leverage the embeddings internally. This model-agnostic approach works with a wide range of CF models without requiring architectural changes, making it adaptable to various recommendation scenarios. Our framework is built for easy integration and modification, providing researchers and developers with a powerful tool for extending CF model capabilities through efficient knowledge transfer. We demonstrate its effectiveness through experiments on the MovieLens and Amazon datasets, where it consistently improves baseline CF models. Experimental studies showed that LLM-KT is competitive with the state-of-the-art methods in context-aware settings but can be applied to a broader range of CF models than current approaches.

[Arxiv](https://arxiv.org/abs/2411.00556)