# [我们提出了一种增强查询方法，旨在改进语言生成任务中的检索过程，从而提高整体性能和效果。](https://arxiv.org/abs/2402.16874)

发布时间：2024年02月06日

`RAG`

> Enhancing Retrieval Processes for Language Generation with Augmented Queries

> 随着尖端语言模型的发展，智能技术领域中的文档搜索日益复杂，其中存在的“幻想”现象（即模型提供不准确信息的问题）成为一大挑战。本研究聚焦于运用检索增强生成（RAG）技术，引导模型依据真实数据输出准确答案。为解决规模化应用的难题，研究者采用创新的查询优化方法，将用户查询与BERT、Orca2等强大语言模型对接。实验分三步进行：第一步排除RAG影响，第二步无额外辅助，第三步添加外部支持，并巧妙选用精悍高效的Orca2 7B模型，实现对计算资源的智慧利用。实验证明，经过RAG优化后，原始语言模型性能大幅提升，尤其是在搭配提示增强工具时效果尤为显著。跨不同编码方式下的文档检索一致性体现了语言模型生成查询的有效性，而引入UMAP用于BERT则在简化文档检索流程的同时确保了卓越的检索性能。

> In the rapidly changing world of smart technology, searching for documents has become more challenging due to the rise of advanced language models. These models sometimes face difficulties, like providing inaccurate information, commonly known as "hallucination." This research focuses on addressing this issue through Retrieval-Augmented Generation (RAG), a technique that guides models to give accurate responses based on real facts. To overcome scalability issues, the study explores connecting user queries with sophisticated language models such as BERT and Orca2, using an innovative query optimization process. The study unfolds in three scenarios: first, without RAG, second, without additional assistance, and finally, with extra help. Choosing the compact yet efficient Orca2 7B model demonstrates a smart use of computing resources. The empirical results indicate a significant improvement in the initial language model's performance under RAG, particularly when assisted with prompts augmenters. Consistency in document retrieval across different encodings highlights the effectiveness of using language model-generated queries. The introduction of UMAP for BERT further simplifies document retrieval while maintaining strong results.

[Arxiv](https://arxiv.org/abs/2402.16874)