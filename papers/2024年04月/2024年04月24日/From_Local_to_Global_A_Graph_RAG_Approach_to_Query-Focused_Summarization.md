# 由点及面：探索基于图的 RAG 技术在查询导向摘要中的应用

发布时间：2024年04月24日

`RAG` `信息检索`

> From Local to Global: A Graph RAG Approach to Query-Focused Summarization

# 摘要

> 通过检索增强生成（RAG）技术，大型语言模型（LLMs）能够从外部知识库中检索信息，从而解答涉及私密或之前未见文档集合的查询。然而，面对针对整个文本集合的全局性问题，如“数据集的主要主题有哪些？”，RAG 显得无能为力，因为这本质上是一项查询聚焦的摘要任务，而非直接的检索任务。与此同时，传统的查询聚焦摘要方法在处理 RAG 系统索引的海量文本时也显得力不从心。为了融合这些方法的优势，我们提出了一种基于图的 RAG 方法，用于解答私人文本语料库的问题，这种方法能够适应用户问题的广泛性以及需要索引的源文本量。我们的解决方案首先利用 LLM 构建基于图的文本索引，包括从源文档中提取实体知识图谱，然后为所有紧密相关的实体群体预生成社区摘要。当提出问题时，每个社区摘要用于生成部分答案，随后所有部分答案汇总生成最终回答。在处理大约百万级令牌的数据集时，我们证明了图 RAG 在生成答案的全面性和多样性方面，相较于传统 RAG 基线有显著提升。一个开源的、基于 Python 的全局和本地图 RAG 方法的实现即将发布，详情请访问 https://aka.ms/graphrag。

> The use of retrieval-augmented generation (RAG) to retrieve relevant information from an external knowledge source enables large language models (LLMs) to answer questions over private and/or previously unseen document collections. However, RAG fails on global questions directed at an entire text corpus, such as "What are the main themes in the dataset?", since this is inherently a query-focused summarization (QFS) task, rather than an explicit retrieval task. Prior QFS methods, meanwhile, fail to scale to the quantities of text indexed by typical RAG systems. To combine the strengths of these contrasting methods, we propose a Graph RAG approach to question answering over private text corpora that scales with both the generality of user questions and the quantity of source text to be indexed. Our approach uses an LLM to build a graph-based text index in two stages: first to derive an entity knowledge graph from the source documents, then to pregenerate community summaries for all groups of closely-related entities. Given a question, each community summary is used to generate a partial response, before all partial responses are again summarized in a final response to the user. For a class of global sensemaking questions over datasets in the 1 million token range, we show that Graph RAG leads to substantial improvements over a naïve RAG baseline for both the comprehensiveness and diversity of generated answers. An open-source, Python-based implementation of both global and local Graph RAG approaches is forthcoming at https://aka.ms/graphrag.

[Arxiv](https://arxiv.org/abs/2404.16130)