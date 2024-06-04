# SPAGHETTI：融合检索与语义解析，从多元数据源中解锁开放域问答的奥秘

发布时间：2024年06月01日

`RAG

理由：论文摘要中提到的 SPAGHETTI 系统结合了语义解析与增强生成技术，用于从文本表格和信息框中提取多源信息，并在异构开放域问答数据集上取得了显著的性能提升。这种技术涉及到对异构知识的整合和生成，与 RAG（Retrieval-Augmented Generation）模型的概念相符，后者通常用于结合检索和生成技术来提高语言模型的性能。因此，该论文更适合归类于RAG。` `问答系统` `数据分析`

> SPAGHETTI: Open-Domain Question Answering from Heterogeneous Data Sources with Retrieval and Semantic Parsing

# 摘要

> 我们推出了 SPAGHETTI 系统：一种结合语义解析与增强生成的混合问答技术，能从文本表格和信息框中提取多源信息。该系统整合了知识库、文本、表格及信息框等异构知识，使其在 Compmix 这一最全面的异构开放域 QA 数据集上，以 56.5% 的精确匹配率刷新了记录。更关键的是，对部分数据集的手动分析显示，SPAGHETTI 的准确率高达 90% 以上，这表明传统的 EM 评估标准已不足以衡量现代 QA 系统的真正实力。

> We introduce SPAGHETTI: Semantic Parsing Augmented Generation for Hybrid English information from Text Tables and Infoboxes, a hybrid question-answering (QA) pipeline that utilizes information from heterogeneous knowledge sources, including knowledge base, text, tables, and infoboxes. Our LLM-augmented approach achieves state-of-the-art performance on the Compmix dataset, the most comprehensive heterogeneous open-domain QA dataset, with 56.5% exact match (EM) rate. More importantly, manual analysis on a sample of the dataset suggests that SPAGHETTI is more than 90% accurate, indicating that EM is no longer suitable for assessing the capabilities of QA systems today.

![SPAGHETTI：融合检索与语义解析，从多元数据源中解锁开放域问答的奥秘](../../../paper_images/2406.00562/x4.png)

![SPAGHETTI：融合检索与语义解析，从多元数据源中解锁开放域问答的奥秘](../../../paper_images/2406.00562/x5.png)

![SPAGHETTI：融合检索与语义解析，从多元数据源中解锁开放域问答的奥秘](../../../paper_images/2406.00562/x6.png)

[Arxiv](https://arxiv.org/abs/2406.00562)