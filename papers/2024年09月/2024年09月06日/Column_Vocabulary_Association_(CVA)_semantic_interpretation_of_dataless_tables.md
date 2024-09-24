# 列词汇关联 (CVA)：解读无数据表格的语义

发布时间：2024年09月06日

`LLM应用` `数据科学` `知识图谱`

> Column Vocabulary Association (CVA): semantic interpretation of dataless tables

# 摘要

> 传统的语义表格解释（STI）方法依赖于底层数据进行语义注释。今年的 SemTab 挑战赛引入了“元数据到 KG”赛道，仅使用元数据进行 STI。为此，我们提出了“列词汇关联（CVA）”这一新概念，即仅基于元数据对列标题进行语义注释。我们评估了多种方法的性能，包括 LLMs 和 RAG，以及基于 SemanticBERT 的传统方法。我们采用零-shot 设置，避免特定领域的影响。我们测试了 7 种 LLMs，包括三种商业 GPT 模型和四种开源模型，并结合 RAG 系统，研究温度设置对性能的影响。此外，我们还使用 SemanticBERT 进行 CVA 任务，分析元数据对其性能的影响。初步结果显示，LLMs 在低温下表现优异，但在数据与词汇表相关时，传统方法表现更佳。

> Traditional Semantic Table Interpretation (STI) methods rely primarily on the underlying table data to create semantic annotations. This year's SemTab challenge introduced the ``Metadata to KG'' track, which focuses on performing STI by using only metadata information, without access to the underlying data. In response to this new challenge, we introduce a new term: Column Vocabulary Association (CVA). This term refers to the task of semantic annotation of column headers solely based on metadata information. In this study, we evaluate the performance of various methods in executing the CVA task, including a Large Language Models (LLMs) and Retrieval Augmented Generation (RAG) approach, as well as a more traditional similarity approach with SemanticBERT. Our methodology uses a zero-shot setting, with no pretraining or examples passed to the Large Language Models (LLMs), as we aim to avoid a domain-specific setting.
  We investigate a total of 7 different LLMs, of which three commercial GPT models (i.e. gpt-3.5-turbo-0.125, gpt-4o and gpt-4-turbo) and four open source models (i.e. llama3-80b, llama3-7b, gemma-7b and mixtral-8x7b). We integrate this models with RAG systems, and we explore how variations in temperature settings affect performances. Moreover, we continue our investigation by performing the CVA task utilizing SemanticBERT, analyzing how various metadata information influence its performance.
  Initial findings indicate that LLMs generally perform well at temperatures below 1.0, achieving an accuracy of 100\% in certain cases. Nevertheless, our investigation also reveal that the nature of the data significantly influences CVA task outcomes. In fact, in cases where the input data and glossary are related (for example by being created by the same organizations) traditional methods appear to surpass the performance of LLMs.

[Arxiv](https://arxiv.org/abs/2409.13709)