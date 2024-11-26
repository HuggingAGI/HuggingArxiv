# 用于检索增强生成的上下文感知门

发布时间：2024年11月25日

`RAG` `问答系统` `开放域`

> Context Awareness Gate For Retrieval Augmented Generation

# 摘要

> 检索增强生成（RAG）已成为广泛应用的手段，用于缓解大型语言模型（LLMs）在回答特定领域问题时的局限性。此前的研究重点多在于提升检索到的数据块的精准度和质量，以增强生成流程的整体性能。然而，尽管不断有新进展，检索不相关信息这一关键问题——它会削弱模型有效运用内部知识的能力——却鲜少受到关注。在本项工作中，我们探究了在开放域问答中检索不相关信息所产生的影响，突出了其对LLM输出质量的显著不利作用。为应对此挑战，我们提出了上下文感知门（CAG）架构，这是一种能依据用户查询是否需要外部上下文检索来动态调整LLM输入提示的新颖机制。另外，我们引入了向量候选方法，这是CAG的核心数学组成部分，具有统计性、不依赖LLM且高度可扩展性。我们还进一步研究了上下文与问题之间关系的分布情况，并对这些分布进行了统计分析。此分析可用于强化检索增强生成（RAG）系统中的上下文检索过程。

> Retrieval Augmented Generation (RAG) has emerged as a widely adopted approach to mitigate the limitations of large language models (LLMs) in answering domain-specific questions. Previous research has predominantly focused on improving the accuracy and quality of retrieved data chunks to enhance the overall performance of the generation pipeline. However, despite ongoing advancements, the critical issue of retrieving irrelevant information -- which can impair the ability of the model to utilize its internal knowledge effectively -- has received minimal attention. In this work, we investigate the impact of retrieving irrelevant information in open-domain question answering, highlighting its significant detrimental effect on the quality of LLM outputs. To address this challenge, we propose the Context Awareness Gate (CAG) architecture, a novel mechanism that dynamically adjusts the LLMs' input prompt based on whether the user query necessitates external context retrieval. Additionally, we introduce the Vector Candidates method, a core mathematical component of CAG that is statistical, LLM-independent, and highly scalable. We further examine the distributions of relationships between contexts and questions, presenting a statistical analysis of these distributions. This analysis can be leveraged to enhance the context retrieval process in Retrieval Augmented Generation (RAG) systems.

[Arxiv](https://arxiv.org/abs/2411.16133)