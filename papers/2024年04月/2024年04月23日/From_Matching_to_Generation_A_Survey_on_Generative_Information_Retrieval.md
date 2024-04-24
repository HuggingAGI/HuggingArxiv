# 探索信息检索的创新路径：从匹配到生成的生成式信息检索综述

发布时间：2024年04月23日

`分类：LLM应用` `信息检索`

> From Matching to Generation: A Survey on Generative Information Retrieval

# 摘要

> 信息检索系统对于用户获取信息至关重要，被广泛应用于搜索引擎、问答系统和推荐系统等场景。传统上，基于相似性匹配的IR方法一直是信息检索的可靠手段。然而，随着预训练语言模型的发展，生成式信息检索（GenIR）作为一种新兴范式，正逐渐受到业界的广泛关注。GenIR的研究主要分为两大方向：生成式文档检索（GR）和可靠的响应生成。GR通过利用生成模型的参数记忆文档，无需显式索引即可检索，而可靠的响应生成则直接利用语言模型生成用户所需的信息，超越了传统IR的限制，提供了更高的灵活性和效率。本文将系统梳理GenIR领域的最新研究进展，包括GR在模型训练、文档标识符生成、增量学习、下游任务适配、多模态GR和生成式推荐等方面的进展，以及在知识内化、知识外扩、引用生成和个人信息助理等方面的可靠响应生成技术。此外，本文还将探讨GenIR系统的评估标准、面临的挑战及未来的发展方向，旨在为GenIR研究者提供全面的参考，以推动该领域的进一步发展。

> Information Retrieval (IR) systems are crucial tools for users to access information, widely applied in scenarios like search engines, question answering, and recommendation systems. Traditional IR methods, based on similarity matching to return ranked lists of documents, have been reliable means of information acquisition, dominating the IR field for years. With the advancement of pre-trained language models, generative information retrieval (GenIR) has emerged as a novel paradigm, gaining increasing attention in recent years. Currently, research in GenIR can be categorized into two aspects: generative document retrieval (GR) and reliable response generation. GR leverages the generative model's parameters for memorizing documents, enabling retrieval by directly generating relevant document identifiers without explicit indexing. Reliable response generation, on the other hand, employs language models to directly generate the information users seek, breaking the limitations of traditional IR in terms of document granularity and relevance matching, offering more flexibility, efficiency, and creativity, thus better meeting practical needs. This paper aims to systematically review the latest research progress in GenIR. We will summarize the advancements in GR regarding model training, document identifier, incremental learning, downstream tasks adaptation, multi-modal GR and generative recommendation, as well as progress in reliable response generation in aspects of internal knowledge memorization, external knowledge augmentation, generating response with citations and personal information assistant. We also review the evaluation, challenges and future prospects in GenIR systems. This review aims to offer a comprehensive reference for researchers in the GenIR field, encouraging further development in this area.

[Arxiv](https://arxiv.org/abs/2404.14851)