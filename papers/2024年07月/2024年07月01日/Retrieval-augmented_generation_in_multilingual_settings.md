# 多语言环境下的检索增强生成

发布时间：2024年07月01日

`RAG` `人工智能` `多语言处理`

> Retrieval-augmented generation in multilingual settings

# 摘要

> RAG作为一种创新的解决方案，旨在将最新或特定领域的知识融入大型语言模型（LLM），并提升其事实性，但目前主要在英语环境中研究。我们探索了多语言环境下的RAG（mRAG），涉及13种语言的用户查询和数据存储，并探讨了构建高效mRAG流水线的关键组件和必要调整。研究发现，尽管现有高质量多语言工具丰富，但任务特定的提示工程对于实现用户语言生成至关重要。同时，评估指标需适应多语言特性，考虑命名实体的拼写差异。未来挑战包括非拉丁字母语言中的代码切换频繁、流畅性问题、文档解读错误及无关检索等。我们已在https://github.com/naver/bergen分享了mRAG基线流水线的代码，供未来研究参考。

> Retrieval-augmented generation (RAG) has recently emerged as a promising solution for incorporating up-to-date or domain-specific knowledge into large language models (LLMs) and improving LLM factuality, but is predominantly studied in English-only settings. In this work, we consider RAG in the multilingual setting (mRAG), i.e. with user queries and the datastore in 13 languages, and investigate which components and with which adjustments are needed to build a well-performing mRAG pipeline, that can be used as a strong baseline in future works. Our findings highlight that despite the availability of high-quality off-the-shelf multilingual retrievers and generators, task-specific prompt engineering is needed to enable generation in user languages. Moreover, current evaluation metrics need adjustments for multilingual setting, to account for variations in spelling named entities. The main limitations to be addressed in future works include frequent code-switching in non-Latin alphabet languages, occasional fluency errors, wrong reading of the provided documents, or irrelevant retrieval. We release the code for the resulting mRAG baseline pipeline at https://github.com/naver/bergen.

[Arxiv](https://arxiv.org/abs/2407.01463)