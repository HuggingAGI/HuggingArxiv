# 大型语言模型重塑结构化数据库信息检索新篇章

发布时间：2024年05月08日

`RAG

解释：这篇论文主要讨论了如何利用大型语言模型（LLMs）的语义理解能力来改进信息检索过程，特别是在金融领域的应用。它提出了一个名为ChatLR的框架，并通过实验展示了其在信息检索方面的准确性。这与RAG（Retrieval-Augmented Generation）的概念相符，RAG是一种结合了检索和生成的方法，用于提高语言模型的性能，尤其是在需要外部知识的情况下。因此，这篇论文更适合归类为RAG。` `问答系统`

> Redefining Information Retrieval of Structured Database via Large Language Models

# 摘要

> 在语言模型（LMs）利用外部知识库进行推理之前，检索增强对于提取与查询相关的非参数知识至关重要。通过将检索信息融入LMs作为查询的上下文，我们提高了回答事实问题的可靠性。然而，传统检索器在从知识库中精确提取相关信息方面面临挑战。为此，我们提出了ChatLR框架，它利用LLMs的强大语义理解能力进行精确信息检索。我们还开发了一个专为金融领域定制的LLM搜索和问答系统，并通过Text2API和API-ID识别任务对LLM进行微调。实验表明，ChatLR在处理用户查询方面表现出色，信息检索准确率高达98.8%以上。

> Retrieval augmentation is critical when Language Models (LMs) exploit non-parametric knowledge related to the query through external knowledge bases before reasoning. The retrieved information is incorporated into LMs as context alongside the query, enhancing the reliability of responses towards factual questions. Prior researches in retrieval augmentation typically follow a retriever-generator paradigm. In this context, traditional retrievers encounter challenges in precisely and seamlessly extracting query-relevant information from knowledge bases. To address this issue, this paper introduces a novel retrieval augmentation framework called ChatLR that primarily employs the powerful semantic understanding ability of Large Language Models (LLMs) as retrievers to achieve precise and concise information retrieval. Additionally, we construct an LLM-based search and question answering system tailored for the financial domain by fine-tuning LLM on two tasks including Text2API and API-ID recognition. Experimental results demonstrate the effectiveness of ChatLR in addressing user queries, achieving an overall information retrieval accuracy exceeding 98.8\%.

[Arxiv](https://arxiv.org/abs/2405.05508)