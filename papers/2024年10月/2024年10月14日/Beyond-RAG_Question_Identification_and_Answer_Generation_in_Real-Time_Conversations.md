# 超越RAG：实时对话中的问题识别与答案生成

发布时间：2024年10月14日

`RAG` `客户服务` `人工智能`

> Beyond-RAG: Question Identification and Answer Generation in Real-Time Conversations

# 摘要

> 在客户服务中心，人工客服因需手动解读查询并查找相关知识库文章，常面临较长的处理时间。尽管使用大型语言模型的检索增强生成（RAG）系统已被广泛用于协助此类任务，但在实时对话中，RAG 仍面临查询不准确和频繁检索常见问题（FAQ）的挑战。为此，我们设计了一种决策支持系统，能实时识别客户问题：若问题匹配 FAQ，直接从数据库中获取答案；否则，通过 RAG 生成答案。该系统不仅减少了对人工查询的依赖，还能在 2 秒内为客服提供响应。在 Minerva CQ 的 AI 辅助客服解决方案中应用后，系统显著提升了效率，缩短了处理时间，并降低了运营成本。此外，我们还开发了一种自动化流程，用于在没有预设 FAQ 的情况下，从历史对话中自动识别常见问题。

> In customer contact centers, human agents often struggle with long average handling times (AHT) due to the need to manually interpret queries and retrieve relevant knowledge base (KB) articles. While retrieval augmented generation (RAG) systems using large language models (LLMs) have been widely adopted in industry to assist with such tasks, RAG faces challenges in real-time conversations, such as inaccurate query formulation and redundant retrieval of frequently asked questions (FAQs). To address these limitations, we propose a decision support system that can look beyond RAG by first identifying customer questions in real time. If the query matches an FAQ, the system retrieves the answer directly from the FAQ database; otherwise, it generates answers via RAG. Our approach reduces reliance on manual queries, providing responses to agents within 2 seconds. Deployed in AI-powered human-agent assist solution at Minerva CQ, this system improves efficiency, reduces AHT, and lowers operational costs. We also introduce an automated LLM-agentic workflow to identify FAQs from historical transcripts when no predefined FAQs exist.

[Arxiv](https://arxiv.org/abs/2410.10136)