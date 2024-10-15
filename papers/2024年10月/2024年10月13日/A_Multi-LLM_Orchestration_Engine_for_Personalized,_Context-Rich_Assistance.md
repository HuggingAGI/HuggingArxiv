# 个性化、上下文感知的辅助系统，采用多 LLM 编排引擎

发布时间：2024年10月13日

`LLM应用` `人工智能` `个性化助手`

> A Multi-LLM Orchestration Engine for Personalized, Context-Rich Assistance

# 摘要

> 近年来，大型语言模型在自然语言处理方面表现出色，但在处理私人或本地数据时，常面临幻觉和长期上下文相关性的挑战。本文提出了一种创新架构，通过集成多个LLM、时间图数据库和向量数据库的编排引擎，有效应对这些问题。该系统通过捕捉用户交互，构建对话图谱，并存储关键概念、实体和行为的时间关联，从而深入理解用户偏好，提供个性化且上下文相关的答案。此外，向量数据库编码私人数据，确保LLM在需要时能访问并综合复杂信息。为增强可靠性，编排引擎协调多个LLM生成全面答案，并不断反思其准确性。最终，该系统成为一个适应性强、注重隐私的AI助手，能在降低幻觉风险的同时，提供更深入、更相关的交互体验。本文详细介绍了该系统的架构、方法及其在个性化AI助手领域的潜在应用，开辟了新的研究方向。

> In recent years, large language models have demonstrated remarkable capabilities in natural language understanding and generation. However, these models often struggle with hallucinations and maintaining long term contextual relevance, particularly when dealing with private or local data. This paper presents a novel architecture that addresses these challenges by integrating an orchestration engine that utilizes multiple LLMs in conjunction with a temporal graph database and a vector database. The proposed system captures user interactions, builds a graph representation of conversations, and stores nodes and edges that map associations between key concepts, entities, and behaviors over time. This graph based structure allows the system to develop an evolving understanding of the user preferences, providing personalized and contextually relevant answers. In addition to this, a vector database encodes private data to supply detailed information when needed, allowing the LLM to access and synthesize complex responses. To further enhance reliability, the orchestration engine coordinates multiple LLMs to generate comprehensive answers and iteratively reflect on their accuracy. The result is an adaptive, privacy centric AI assistant capable of offering deeper, more relevant interactions while minimizing the risk of hallucinations. This paper outlines the architecture, methodology, and potential applications of this system, contributing a new direction in personalized, context aware AI assistance.

[Arxiv](https://arxiv.org/abs/2410.10039)