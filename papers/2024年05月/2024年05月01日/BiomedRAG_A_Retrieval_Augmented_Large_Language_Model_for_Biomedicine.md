# BiomedRAG：一种为生物医学领域设计的、结合了检索功能的先进大型语言模型。

发布时间：2024年05月01日

`RAG` `生物医学`

> BiomedRAG: A Retrieval Augmented Large Language Model for Biomedicine

# 摘要

> 大型语言模型（LLMs）在生物医学和医疗领域的多样化应用中迅速崭露头角，尽管它们有时会生成错误信息或产生幻觉。为了解决这些问题，检索增强生成技术应运而生，帮助模型刷新知识库并提升性能。与以往的检索增强语言模型相比，这些模型通常使用专门的交叉注意力机制来编码检索到的文本，BiomedRAG则采取了更为简洁的方法，直接将检索到的块状文档输入LLM。这种设计简化了现有检索和语言模型的应用，有效过滤了检索文档中的噪声，尤其是在噪声较多的任务中。此外，我们的研究还展示了利用LLM指导生物医学领域检索模型的潜力，以检索出能够辅助LLM提升预测准确度的文档。实验结果显示，在经过调整的评分器辅助下，BiomedRAG在5项生物医学自然语言处理任务上均展现出色的表现，这些任务包括信息抽取（三元组抽取、关系抽取）、文本分类、链接预测和问答，涵盖了9个以上的数据集。以三元组抽取任务为例，BiomedRAG在GIT和ChemProt语料库上的微F1分数分别达到了81.42和88.83，超越了其他同类系统。

> Large Language Models (LLMs) have swiftly emerged as vital resources for different applications in the biomedical and healthcare domains; however, these models encounter issues such as generating inaccurate information or hallucinations. Retrieval-augmented generation provided a solution for these models to update knowledge and enhance their performance. In contrast to previous retrieval-augmented LMs, which utilize specialized cross-attention mechanisms to help LLM encode retrieved text, BiomedRAG adopts a simpler approach by directly inputting the retrieved chunk-based documents into the LLM. This straightforward design is easily applicable to existing retrieval and language models, effectively bypassing noise information in retrieved documents, particularly in noise-intensive tasks. Moreover, we demonstrate the potential for utilizing the LLM to supervise the retrieval model in the biomedical domain, enabling it to retrieve the document that assists the LM in improving its predictions. Our experiments reveal that with the tuned scorer,\textsc{ BiomedRAG} attains superior performance across 5 biomedical NLP tasks, encompassing information extraction (triple extraction, relation extraction), text classification, link prediction, and question-answering, leveraging over 9 datasets. For instance, in the triple extraction task, \textsc{BiomedRAG} outperforms other triple extraction systems with micro-F1 scores of 81.42 and 88.83 on GIT and ChemProt corpora, respectively.

[Arxiv](https://arxiv.org/abs/2405.00465)