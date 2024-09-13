# OmniQuery：通过情境增强多模态记忆，实现个性化问答

发布时间：2024年09月12日

`RAG` `社交媒体` `个人助手`

> OmniQuery: Contextually Augmenting Captured Multimodal Memory to Enable Personal Question Answering

# 摘要

> 人们常用照片、截图和视频记录生活点滴。现有AI工具虽能用自然语言查询这些数据，但大多仅限于检索单个信息，如照片中的物体，难以应对涉及复杂记忆关联的查询，如事件序列。为此，我们进行了为期一个月的日记研究，收集真实用户查询，并构建了整合记忆所需的上下文信息分类。随后，我们推出了OmniQuery系统，该系统能解答需提取和推断上下文的复杂记忆问题。OmniQuery通过整合多重关联记忆的上下文信息，增强单个记忆片段，检索相关记忆，并借助大型语言模型（LLM）提供全面解答。在人类评估中，OmniQuery准确率达71.5%，超越传统RAG系统，74.5%的情况下表现更佳或持平。

> People often capture memories through photos, screenshots, and videos. While existing AI-based tools enable querying this data using natural language, they mostly only support retrieving individual pieces of information like certain objects in photos and struggle with answering more complex queries that involve interpreting interconnected memories like event sequences. We conducted a one-month diary study to collect realistic user queries and generated a taxonomy of necessary contextual information for integrating with captured memories. We then introduce OmniQuery, a novel system that is able to answer complex personal memory-related questions that require extracting and inferring contextual information. OmniQuery augments single captured memories through integrating scattered contextual information from multiple interconnected memories, retrieves relevant memories, and uses a large language model (LLM) to comprehensive answers. In human evaluations, we show the effectiveness of OmniQuery with an accuracy of 71.5%, and it outperformed a conventional RAG system, winning or tying in 74.5% of the time.

[Arxiv](https://arxiv.org/abs/2409.08250)