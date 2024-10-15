# LongMemEval：评估聊天助手在长期交互记忆中的表现

发布时间：2024年10月14日

`LLM应用` `人工智能` `对话系统`

> LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory

# 摘要

> 最新的大型语言模型（LLM）驱动的聊天助手系统已加入记忆功能，能追踪用户与助手的对话历史，从而提供更精准、个性化的回应。然而，这些系统在长时间对话中的长期记忆能力仍待深入研究。本文推出LongMemEval，一个全面评估聊天助手五大核心长期记忆能力的基准：信息提取、跨会话推理、时间推理、知识更新及拒绝。该基准包含500个精心设计的问题，嵌入在可自由扩展的对话历史中，对现有长期记忆系统构成重大挑战，商业聊天助手和长上下文LLM在持续对话中记忆准确率下降30%。我们进一步提出一个统一框架，将长期记忆设计细分为索引、检索和阅读阶段的四个关键选择。基于实验洞察，我们设计了多种优化方案，如会话分解优化信息粒度，事实增强的关键扩展提升索引效率，以及时间感知的查询扩展精炼搜索范围。实验显示，这些优化显著提升了LongMemEval上的记忆召回率和问答表现。总体而言，本研究为提升基于LLM的聊天助手长期记忆能力提供了宝贵资源和指导，推动对话AI向更个性化、可靠的方向发展。

> Recent large language model (LLM)-driven chat assistant systems have integrated memory components to track user-assistant chat histories, enabling more accurate and personalized responses. However, their long-term memory capabilities in sustained interactions remain underexplored. This paper introduces LongMemEval, a comprehensive benchmark designed to evaluate five core long-term memory abilities of chat assistants: information extraction, multi-session reasoning, temporal reasoning, knowledge updates, and abstention. With 500 meticulously curated questions embedded within freely scalable user-assistant chat histories, LongMemEval presents a significant challenge to existing long-term memory systems, with commercial chat assistants and long-context LLMs showing 30% accuracy drop on memorizing information across sustained interactions. We then present a unified framework that breaks down the long-term memory design into four design choices across the indexing, retrieval, and reading stages. Built upon key experimental insights, we propose several memory designs including session decomposition for optimizing value granularity, fact-augmented key expansion for enhancing the index structure, and time-aware query expansion for refining the search scope. Experiment results show that these optimizations greatly improve both memory recall and downstream question answering on LongMemEval. Overall, our study provides valuable resources and guidance for advancing the long-term memory capabilities of LLM-based chat assistants, paving the way toward more personalized and reliable conversational AI.

[Arxiv](https://arxiv.org/abs/2410.10813)