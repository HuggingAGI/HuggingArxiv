# 探索信息检索的演进：从匹配到生成的生成性信息检索综述

发布时间：2024年04月23日

`LLM应用` `信息检索`

> From Matching to Generation: A Survey on Generative Information Retrieval

# 摘要

> 信息检索系统对于用户获取信息至关重要，它们在搜索引擎、问答系统和推荐系统等场景中发挥着重要作用。传统上，这些系统依赖于相似性匹配技术，以提供有序的文档列表，这一方法多年来一直是信息检索的主流。然而，随着预训练语言模型的发展，生成式信息检索（GenIR）作为一种创新的检索范式，正逐渐受到业界的广泛关注。GenIR的研究主要分为两大方向：生成式文档检索（GR）和可靠的响应生成。GR通过利用生成模型的参数记忆文档内容，实现了无需显式索引即可直接生成相关文档标识符的检索方式。而可靠的响应生成则利用语言模型直接产出用户所需的信息，超越了传统IR在文档细节和相关性匹配上的局限，提供了更高的灵活性和效率。本文的目的是对GenIR领域的最新研究进展进行系统性的梳理。我们将概述GR在模型训练、文档标识、增量学习、任务适应、多模态检索和推荐系统等方面的进展，以及在知识记忆、知识增强、引用生成和个人助理等方面的可靠响应生成技术。此外，我们还将探讨GenIR系统的评估标准、面临的挑战及未来的发展方向。本篇综述的目标是为GenIR领域的研究者提供一个全面的参考框架，以促进该领域的持续进步。

> Information Retrieval (IR) systems are crucial tools for users to access information, widely applied in scenarios like search engines, question answering, and recommendation systems. Traditional IR methods, based on similarity matching to return ranked lists of documents, have been reliable means of information acquisition, dominating the IR field for years. With the advancement of pre-trained language models, generative information retrieval (GenIR) has emerged as a novel paradigm, gaining increasing attention in recent years. Currently, research in GenIR can be categorized into two aspects: generative document retrieval (GR) and reliable response generation. GR leverages the generative model's parameters for memorizing documents, enabling retrieval by directly generating relevant document identifiers without explicit indexing. Reliable response generation, on the other hand, employs language models to directly generate the information users seek, breaking the limitations of traditional IR in terms of document granularity and relevance matching, offering more flexibility, efficiency, and creativity, thus better meeting practical needs. This paper aims to systematically review the latest research progress in GenIR. We will summarize the advancements in GR regarding model training, document identifier, incremental learning, downstream tasks adaptation, multi-modal GR and generative recommendation, as well as progress in reliable response generation in aspects of internal knowledge memorization, external knowledge augmentation, generating response with citations and personal information assistant. We also review the evaluation, challenges and future prospects in GenIR systems. This review aims to offer a comprehensive reference for researchers in the GenIR field, encouraging further development in this area.

[Arxiv](https://arxiv.org/abs/2404.14851)