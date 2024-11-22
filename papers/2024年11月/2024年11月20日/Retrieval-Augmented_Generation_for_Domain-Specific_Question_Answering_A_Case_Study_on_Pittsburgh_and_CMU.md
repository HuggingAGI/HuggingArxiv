# 关于特定领域问答的检索增强生成：以匹兹堡和卡内基梅隆大学为例的研究

发布时间：2024年11月20日

`RAG` `信息检索`

> Retrieval-Augmented Generation for Domain-Specific Question Answering: A Case Study on Pittsburgh and CMU

# 摘要

> 我们设计了一个检索增强生成（RAG）系统，旨在为大型语言模型提供解答有关匹兹堡和卡内基梅隆大学（CMU）特定领域问题的相关文档。我们运用贪婪抓取策略提取了逾 1800 个子页面，并采用了混合标注流程，将手动和 Mistral 生成的问答对相结合，达成了 0.7625 的标注者间一致性（IAA）得分。我们的 RAG 框架融合了 BM25 和 FAISS 检索器，并借助重排序器提升了文档检索的精准度。实验结果显示，RAG 系统在时间敏感和复杂查询方面表现显著优于非 RAG 基线，F1 分数从 5.45％提升至 42.21％，召回率达 56.18％。此项研究彰显了 RAG 系统在增强答案精准度和相关性方面的潜能，同时也明确了文档检索和模型训练中有待进一步优化的区域。

> We designed a Retrieval-Augmented Generation (RAG) system to provide large language models with relevant documents for answering domain-specific questions about Pittsburgh and Carnegie Mellon University (CMU). We extracted over 1,800 subpages using a greedy scraping strategy and employed a hybrid annotation process, combining manual and Mistral-generated question-answer pairs, achieving an inter-annotator agreement (IAA) score of 0.7625. Our RAG framework integrates BM25 and FAISS retrievers, enhanced with a reranker for improved document retrieval accuracy. Experimental results show that the RAG system significantly outperforms a non-RAG baseline, particularly in time-sensitive and complex queries, with an F1 score improvement from 5.45% to 42.21% and recall of 56.18%. This study demonstrates the potential of RAG systems in enhancing answer precision and relevance, while identifying areas for further optimization in document retrieval and model training.

[Arxiv](https://arxiv.org/abs/2411.13691)