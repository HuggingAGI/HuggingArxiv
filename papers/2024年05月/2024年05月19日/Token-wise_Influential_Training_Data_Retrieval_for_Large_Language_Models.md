# 大型语言模型中基于令牌的关键训练数据检索

发布时间：2024年05月19日

`RAG

理由：这篇论文介绍了一个名为RapidIn的框架，该框架专注于通过缓存和检索梯度向量来追溯大型语言模型（LLM）的训练数据影响。这种方法与检索增强生成（RAG）的概念相似，因为RAG也是一种通过检索相关信息来增强模型生成能力的技术。虽然RapidIn不是直接用于生成增强，但其通过检索和分析训练数据的影响来追溯LLM的生成过程，这与RAG的核心思想——利用检索机制来提升模型性能——有一定的联系。因此，将这篇论文归类为RAG是合适的。` `数据追溯` `机器学习`

> Token-wise Influential Training Data Retrieval for Large Language Models

# 摘要

> 面对大型语言模型（LLM）的生成，我们如何追溯其背后的训练数据？本文介绍了RapidIn框架，它通过两步——缓存与检索，精准定位训练数据的影响。首先，RapidIn将梯度向量压缩至原体积的1/200,000，轻松存于磁盘或内存。接着，针对任意生成，RapidIn能在数分钟内，通过遍历这些精简的梯度，迅速评估其影响，速度提升高达6,326倍。不仅如此，RapidIn还支持多GPU协同，大幅提升缓存与检索的效率。实证表明，RapidIn既高效又精准。

> Given a Large Language Model (LLM) generation, how can we identify which training data led to this generation? In this paper, we proposed RapidIn, a scalable framework adapting to LLMs for estimating the influence of each training data. The proposed framework consists of two stages: caching and retrieval. First, we compress the gradient vectors by over 200,000x, allowing them to be cached on disk or in GPU/CPU memory. Then, given a generation, RapidIn efficiently traverses the cached gradients to estimate the influence within minutes, achieving over a 6,326x speedup. Moreover, RapidIn supports multi-GPU parallelization to substantially accelerate caching and retrieval. Our empirical result confirms the efficiency and effectiveness of RapidIn.

[Arxiv](https://arxiv.org/abs/2405.11724)