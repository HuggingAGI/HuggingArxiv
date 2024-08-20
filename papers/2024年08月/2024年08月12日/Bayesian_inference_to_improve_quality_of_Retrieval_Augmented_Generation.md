# 利用贝叶斯推理提升检索增强生成的质量

发布时间：2024年08月12日

`RAG` `人工智能` `搜索引擎`

> Bayesian inference to improve quality of Retrieval Augmented Generation

# 摘要

> 检索增强生成（RAG）是现代大型语言模型（LLM）应用中最受欢迎的模式。RAG 通过在向量数据库中搜索相关段落来处理用户查询。然而，这种方法依赖于搜索的有效性，且缺乏强有力的后处理来确保文本块的质量。我们提出一种贝叶斯方法，通过评估文本块的质量和相关性，来提升 RAG 系统的响应质量。利用 LLM 评估上下文段落的相关性，并结合文档页码作为先验概率，我们旨在优化答案的概括性和准确性。

> Retrieval Augmented Generation or RAG is the most popular pattern for modern Large Language Model or LLM applications. RAG involves taking a user query and finding relevant paragraphs of context in a large corpus typically captured in a vector database. Once the first level of search happens over a vector database, the top n chunks of relevant text are included directly in the context and sent as prompt to the LLM. Problem with this approach is that quality of text chunks depends on effectiveness of search. There is no strong post processing after search to determine if the chunk does hold enough information to include in prompt. Also many times there may be chunks that have conflicting information on the same subject and the model has no prior experience which chunk to prioritize to make a decision. Often times, this leads to the model providing a statement that there are conflicting statements, and it cannot produce an answer. In this research we propose a Bayesian approach to verify the quality of text chunks from the search results. Bayes theorem tries to relate conditional probabilities of the hypothesis with evidence and prior probabilities. We propose that, finding likelihood of text chunks to give a quality answer and using prior probability of quality of text chunks can help us improve overall quality of the responses from RAG systems. We can use the LLM itself to get a likelihood of relevance of a context paragraph. For prior probability of the text chunk, we use the page number in the documents parsed. Assumption is that that paragraphs in earlier pages have a better probability of being findings and more relevant to generalizing an answer.

[Arxiv](https://arxiv.org/abs/2408.08901)