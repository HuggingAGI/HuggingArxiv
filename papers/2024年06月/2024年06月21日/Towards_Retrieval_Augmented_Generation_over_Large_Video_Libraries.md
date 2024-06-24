# 迈向大规模视频库上的增强检索生成

发布时间：2024年06月21日

`RAG

理由：这篇论文主要介绍了将检索增强生成（RAG）技术应用于视频库问答（VLQA）任务的方法。它利用大型语言模型（LLMs）生成搜索查询，并结合视频的语音与视觉元数据来生成答案。这种方法特别强调了RAG技术在视频内容处理中的应用，因此归类为RAG。` `视频创作` `多媒体内容检索`

> Towards Retrieval Augmented Generation over Large Video Libraries

# 摘要

> 视频内容创作者急需高效工具，以应对内容再利用的复杂挑战，尤其是从庞大的视频库中提炼新作。本文创新性地提出了视频库问答（VLQA）任务，通过一种兼容性架构，将检索增强生成（RAG）技术应用于视频库。我们的系统利用大型语言模型（LLMs）生成精准搜索查询，捕捉视频中语音与视觉元数据标记的关键时刻。随后，答案生成模块巧妙结合用户查询与元数据，输出附带精确时间戳的答案。此方法在多媒体内容检索及AI辅助视频创作领域展现出广阔前景。

> Video content creators need efficient tools to repurpose content, a task that often requires complex manual or automated searches. Crafting a new video from large video libraries remains a challenge. In this paper we introduce the task of Video Library Question Answering (VLQA) through an interoperable architecture that applies Retrieval Augmented Generation (RAG) to video libraries. We propose a system that uses large language models (LLMs) to generate search queries, retrieving relevant video moments indexed by speech and visual metadata. An answer generation module then integrates user queries with this metadata to produce responses with specific video timestamps. This approach shows promise in multimedia content retrieval, and AI-assisted video content creation.

[Arxiv](https://arxiv.org/abs/2406.14938)