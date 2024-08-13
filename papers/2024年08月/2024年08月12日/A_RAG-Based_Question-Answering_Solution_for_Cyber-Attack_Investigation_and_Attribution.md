# 针对网络攻击调查与归因，我们提出了一种基于 RAG 的问答解决方案。

发布时间：2024年08月12日

`RAG` `网络安全` `人工智能`

> A RAG-Based Question-Answering Solution for Cyber-Attack Investigation and Attribution

# 摘要

> 在网络安全领域，分析师需紧跟最新攻击动态和相关信息，以助力网络攻击的调查与归因。我们首创的问答（QA）模型，结合检索增强生成（RAG）技术与大型语言模型（LLM），为专家提供精准的网络攻击调查与归因信息。该模型依据我们的知识库（KB）或用户外部资源，高效解答各类问题。与OpenAI的GPT模型相比，我们的QA模型不仅提供答案来源，更克服了GPT模型的幻觉限制，对网络攻击调查与归因至关重要。研究显示，RAG QA模型在提供少量示例而非零-shot指令时，答案质量更佳。

> In the constantly evolving field of cybersecurity, it is imperative for analysts to stay abreast of the latest attack trends and pertinent information that aids in the investigation and attribution of cyber-attacks. In this work, we introduce the first question-answering (QA) model and its application that provides information to the cybersecurity experts about cyber-attacks investigations and attribution. Our QA model is based on Retrieval Augmented Generation (RAG) techniques together with a Large Language Model (LLM) and provides answers to the users' queries based on either our knowledge base (KB) that contains curated information about cyber-attacks investigations and attribution or on outside resources provided by the users. We have tested and evaluated our QA model with various types of questions, including KB-based, metadata-based, specific documents from the KB, and external sources-based questions. We compared the answers for KB-based questions with those from OpenAI's GPT-3.5 and the latest GPT-4o LLMs. Our proposed QA model outperforms OpenAI's GPT models by providing the source of the answers and overcoming the hallucination limitations of the GPT models, which is critical for cyber-attack investigation and attribution. Additionally, our analysis showed that when the RAG QA model is given few-shot examples rather than zero-shot instructions, it generates better answers compared to cases where no examples are supplied in addition to the query.

[Arxiv](https://arxiv.org/abs/2408.06272)