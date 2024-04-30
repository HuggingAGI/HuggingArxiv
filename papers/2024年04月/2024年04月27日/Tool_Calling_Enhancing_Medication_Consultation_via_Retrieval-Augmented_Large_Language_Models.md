# 工具调用：利用检索增强的大型语言模型提升药物咨询效果。

发布时间：2024年04月27日

`分类：RAG` `人工智能`

> Tool Calling: Enhancing Medication Consultation via Retrieval-Augmented Large Language Models

# 摘要

> 大规模语言模型（LLMs）在众多语言任务上取得了卓越成就，但它们也饱受幻觉和时间错位的困扰。为了解决这些问题，我们引入了检索增强生成（RAG）技术，以补充外部知识，优化答案生成过程。尽管如此，将这些模型应用于医学领域时，由于缺乏领域专业知识和现实世界情境的复杂性，我们面临多重挑战。本研究中，我们探讨了在医学领域知识密集型任务中应用RAG框架的LLMs。为了测试LLMs的性能，我们开发了MedicineQA，这是一个模拟真实世界药物咨询场景的多轮对话基准，要求LLMs依据药物数据库中的检索证据进行回答。MedicineQA包含300组多轮问答对，每组都置于详尽的对话背景之中，凸显了这一知识密集型任务对当前LLMs的挑战。此外，我们提出了一个创新的\textit{蒸馏-检索-阅读}框架，替代了传统的\textit{检索然后阅读}模式。在这个新框架中，蒸馏和检索过程通过工具调用机制生成搜索查询，模拟搜索引擎的关键词查询方式。实验结果显示，我们的框架在证据检索的准确性上显著提升了性能，并超越了以往的方法。这一进展为RAG技术在医学领域的应用开辟了新的可能性。

> Large-scale language models (LLMs) have achieved remarkable success across various language tasks but suffer from hallucinations and temporal misalignment. To mitigate these shortcomings, Retrieval-augmented generation (RAG) has been utilized to provide external knowledge to facilitate the answer generation. However, applying such models to the medical domain faces several challenges due to the lack of domain-specific knowledge and the intricacy of real-world scenarios. In this study, we explore LLMs with RAG framework for knowledge-intensive tasks in the medical field. To evaluate the capabilities of LLMs, we introduce MedicineQA, a multi-round dialogue benchmark that simulates the real-world medication consultation scenario and requires LLMs to answer with retrieved evidence from the medicine database. MedicineQA contains 300 multi-round question-answering pairs, each embedded within a detailed dialogue history, highlighting the challenge posed by this knowledge-intensive task to current LLMs. We further propose a new \textit{Distill-Retrieve-Read} framework instead of the previous \textit{Retrieve-then-Read}. Specifically, the distillation and retrieval process utilizes a tool calling mechanism to formulate search queries that emulate the keyword-based inquiries used by search engines. With experimental results, we show that our framework brings notable performance improvements and surpasses the previous counterparts in the evidence retrieval process in terms of evidence retrieval accuracy. This advancement sheds light on applying RAG to the medical domain.

[Arxiv](https://arxiv.org/abs/2404.17897)