# 掌握对话问答中的检索时机、重写内容与回应技巧

发布时间：2024年09月23日

`RAG` `问答系统` `人工智能`

> Learning When to Retrieve, What to Rewrite, and How to Respond in Conversational QA

# 摘要

> 为 LLM 增加信息检索能力（RAG）已被证明对知识密集型任务有益。然而，在会话问答中理解用户的上下文搜索意图仍是一个未被充分研究的领域。与单轮 QA 相比，多轮会话带来了更多挑战，系统需在多轮对话中理解和管理检索内容。为此，我们提出了一种方法，使 LLM 能在会话上下文中决定何时进行检索。必要时，LLM 会重写对话以检索相关段落，并在生成回答前评估其相关性。基于单轮 SELF-RAG 框架，我们提出了适用于多轮会话的 SELF-multi-RAG。实验结果显示，SELF-multi-RAG 在检索相关段落和评估回答质量方面表现更优，人工注释的改进率约为 13%。

> Augmenting Large Language Models (LLMs) with information retrieval capabilities (i.e., Retrieval-Augmented Generation (RAG)) has proven beneficial for knowledge-intensive tasks. However, understanding users' contextual search intent when generating responses is an understudied topic for conversational question answering (QA). This conversational extension leads to additional concerns when compared to single-turn QA as it is more challenging for systems to comprehend conversational context and manage retrieved passages over multiple turns. In this work, we propose a method for enabling LLMs to decide when to retrieve in RAG settings given a conversational context. When retrieval is deemed necessary, the LLM then rewrites the conversation for passage retrieval and judges the relevance of returned passages before response generation. Operationally, we build on the single-turn SELF-RAG framework (Asai et al., 2023) and propose SELF-multi-RAG for conversational settings. SELF-multi-RAG demonstrates improved capabilities over single-turn variants with respect to retrieving relevant passages (by using summarized conversational context) and assessing the quality of generated responses. Experiments on three conversational QA datasets validate the enhanced response generation capabilities of SELF-multi-RAG, with improvements of ~13% measured by human annotation.

[Arxiv](https://arxiv.org/abs/2409.15515)