# IRSC：一个通过语义理解进行信息检索的零-shot 评估基准，专为检索增强生成场景设计。

发布时间：2024年09月24日

`RAG` `信息检索`

> IRSC: A Zero-shot Evaluation Benchmark for Information Retrieval through Semantic Comprehension in Retrieval-Augmented Generation Scenarios

# 摘要

> 在 LLM 支持的 RAG 任务中，检索信息的质量直接影响最终输出。本文推出了 IRSC 基准，用于评估多语言 RAG 任务中的嵌入模型性能。该基准涵盖了查询、标题、段落部分、关键词和摘要五大检索任务。我们填补了当前 RAG 场景中嵌入模型测试与比较方法的空白，引入了语义理解相似度指数 (SSCI) 和检索能力竞赛指数 (RCCI)，并评估了 Snowflake-Arctic、BGE、GTE 和 M3E 等模型。我们的贡献包括 IRSC 基准、SSCI 和 RCCI 指标，以及对嵌入模型跨语言限制的深入分析。IRSC 基准旨在推动 RAG 任务中检索系统的精准发展。所有资源已开放，访问链接：https://github.com/Jasaxion/IRSC\_Benchmark

> In Retrieval-Augmented Generation (RAG) tasks using Large Language Models (LLMs), the quality of retrieved information is critical to the final output. This paper introduces the IRSC benchmark for evaluating the performance of embedding models in multilingual RAG tasks. The benchmark encompasses five retrieval tasks: query retrieval, title retrieval, part-of-paragraph retrieval, keyword retrieval, and summary retrieval. Our research addresses the current lack of comprehensive testing and effective comparison methods for embedding models in RAG scenarios. We introduced new metrics: the Similarity of Semantic Comprehension Index (SSCI) and the Retrieval Capability Contest Index (RCCI), and evaluated models such as Snowflake-Arctic, BGE, GTE, and M3E. Our contributions include: 1) the IRSC benchmark, 2) the SSCI and RCCI metrics, and 3) insights into the cross-lingual limitations of embedding models. The IRSC benchmark aims to enhance the understanding and development of accurate retrieval systems in RAG tasks. All code and datasets are available at: https://github.com/Jasaxion/IRSC\_Benchmark

[Arxiv](https://arxiv.org/abs/2409.15763)