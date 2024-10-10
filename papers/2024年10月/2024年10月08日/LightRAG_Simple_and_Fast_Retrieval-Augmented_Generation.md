# LightRAG：一种既简单又高效的检索增强生成方法

发布时间：2024年10月08日

`RAG` `人工智能` `信息检索`

> LightRAG: Simple and Fast Retrieval-Augmented Generation

# 摘要

> RAG 系统通过整合外部知识源，使 LLM 能够提供更精准、更符合用户需求的响应。然而，现有 RAG 系统存在依赖扁平数据和上下文意识不足的问题，导致答案碎片化。为此，我们推出了 LightRAG，它将图结构融入检索过程，采用双层检索系统，提升信息检索的全面性。结合图结构与向量表示，LightRAG 能高效检索相关实体及其关系，显著提升响应速度并保持上下文相关性。通过增量更新算法，LightRAG 能及时整合新数据，适应快速变化的环境。实验证明，LightRAG 在检索精度和效率上优于现有方法。现已开源，链接：https://github.com/HKUDS/LightRAG。

> Retrieval-Augmented Generation (RAG) systems enhance large language models (LLMs) by integrating external knowledge sources, enabling more accurate and contextually relevant responses tailored to user needs. However, existing RAG systems have significant limitations, including reliance on flat data representations and inadequate contextual awareness, which can lead to fragmented answers that fail to capture complex inter-dependencies. To address these challenges, we propose LightRAG, which incorporates graph structures into text indexing and retrieval processes. This innovative framework employs a dual-level retrieval system that enhances comprehensive information retrieval from both low-level and high-level knowledge discovery. Additionally, the integration of graph structures with vector representations facilitates efficient retrieval of related entities and their relationships, significantly improving response times while maintaining contextual relevance. This capability is further enhanced by an incremental update algorithm that ensures the timely integration of new data, allowing the system to remain effective and responsive in rapidly changing data environments. Extensive experimental validation demonstrates considerable improvements in retrieval accuracy and efficiency compared to existing approaches. We have made our LightRAG open-source and available at the link: https://github.com/HKUDS/LightRAG.

[Arxiv](https://arxiv.org/abs/2410.05779)