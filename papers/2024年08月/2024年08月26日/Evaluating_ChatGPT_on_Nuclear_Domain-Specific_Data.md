# 探究 ChatGPT 在核领域数据上的性能表现

发布时间：2024年08月26日

`RAG` `核数据` `人工智能`

> Evaluating ChatGPT on Nuclear Domain-Specific Data

# 摘要

> 本文深入研究了ChatGPT在核数据这一高度专业化领域中的问答任务应用。我们重点评估了ChatGPT在特定测试集上的表现，并对比了独立LLM与RAG方法的输出效果。尽管LLM技术不断进步，但其生成的错误或“幻觉”信息在需要高精度的场景中仍是一大挑战。本研究探索了RAG在LLM中的应用，该方法通过整合外部知识库和先进检索技术，显著提升了输出内容的准确性与相关性。我们采用两种策略评估ChatGPT的领域问答能力：一是直接从LLM获取答案，二是在RAG框架下获取答案。通过人机双重评估机制，我们根据正确性等多项指标对答案质量进行了评定。研究结果显示，引入RAG流程的LLM在处理核领域特定问题时，能生成更为精准且贴合上下文的回答。同时，本文还探讨了其他可能的方法，以进一步提升此类专业领域答案的精细度和质量。

> This paper examines the application of ChatGPT, a large language model (LLM), for question-and-answer (Q&A) tasks in the highly specialized field of nuclear data. The primary focus is on evaluating ChatGPT's performance on a curated test dataset, comparing the outcomes of a standalone LLM with those generated through a Retrieval Augmented Generation (RAG) approach. LLMs, despite their recent advancements, are prone to generating incorrect or 'hallucinated' information, which is a significant limitation in applications requiring high accuracy and reliability. This study explores the potential of utilizing RAG in LLMs, a method that integrates external knowledge bases and sophisticated retrieval techniques to enhance the accuracy and relevance of generated outputs. In this context, the paper evaluates ChatGPT's ability to answer domain-specific questions, employing two methodologies: A) direct response from the LLM, and B) response from the LLM within a RAG framework. The effectiveness of these methods is assessed through a dual mechanism of human and LLM evaluation, scoring the responses for correctness and other metrics. The findings underscore the improvement in performance when incorporating a RAG pipeline in an LLM, particularly in generating more accurate and contextually appropriate responses for nuclear domain-specific queries. Additionally, the paper highlights alternative approaches to further refine and improve the quality of answers in such specialized domains.

[Arxiv](https://arxiv.org/abs/2409.00090)