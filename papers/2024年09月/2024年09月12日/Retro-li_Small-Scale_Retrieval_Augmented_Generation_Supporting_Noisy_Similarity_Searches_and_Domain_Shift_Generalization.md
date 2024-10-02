# Retro-li：小规模检索增强生成，支持噪声相似性搜索及领域转移泛化。

发布时间：2024年09月12日

`RAG` `人工智能`

> Retro-li: Small-Scale Retrieval Augmented Generation Supporting Noisy Similarity Searches and Domain Shift Generalization

# 摘要

> Retro 等 RAG 系统通过从包含数万亿条目的非参数记忆数据库中检索，显著提升了语言建模能力并减少了毒性和幻觉。我们推出的 Retro-li 则展示了即使使用小规模数据库，检索同样有效，但需更精准的邻居搜索。通过语义相似性搜索，这一挑战得以解决。我们还首次为非参数记忆引入正则化，显著提升了在噪声环境下的困惑度和领域转移时的泛化能力。此外，Retro-li 的非参数记忆有望在模拟内存计算硬件上实现，实现 O(1) 搜索时间，且性能损失微乎其微（<1%）。代码已公开，详见：https://github.com/IBM/Retrieval-Enhanced-Transformer-Little。

> The retrieval augmented generation (RAG) system such as Retro has been shown to improve language modeling capabilities and reduce toxicity and hallucinations by retrieving from a database of non-parametric memory containing trillions of entries. We introduce Retro-li that shows retrieval can also help using a small-scale database, but it demands more accurate and better neighbors when searching in a smaller hence sparser non-parametric memory. This can be met by using a proper semantic similarity search. We further propose adding a regularization to the non-parametric memory for the first time: it significantly reduces perplexity when the neighbor search operations are noisy during inference, and it improves generalization when a domain shift occurs. We also show that Retro-li's non-parametric memory can potentially be implemented on analog in-memory computing hardware, exhibiting O(1) search time while causing noise in retrieving neighbors, with minimal (<1%) performance loss. Our code is available at: https://github.com/IBM/Retrieval-Enhanced-Transformer-Little.

[Arxiv](https://arxiv.org/abs/2410.00004)