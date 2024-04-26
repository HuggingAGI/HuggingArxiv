# 由点及面：图卷积网络 RAG 策略在查询导向摘要中的应用

发布时间：2024年04月24日

`RAG` `信息检索`

> From Local to Global: A Graph RAG Approach to Query-Focused Summarization

# 摘要

> 通过检索增强生成（RAG），大型语言模型（LLMs）能够从外部知识库中检索信息，解答关于私密或未曾见过的文档集合的查询。但面对针对整个文本集合的全局性问题，如“数据集中的主要主题有哪些？”，RAG 显得无能为力，因为这本质上是一个查询聚焦的摘要任务，而非直接的检索任务。传统的查询聚焦摘要方法也无法适应 RAG 系统所处理的海量文本。为了融合这些方法的优势，我们提出了一种基于图的 RAG 方法，用于在私人文本集合上进行问答，它能够适应用户问题的广泛性以及需要索引的源文本量。该方法利用 LLM 分两步构建基于图的文本索引：首先从源文档中提取实体知识图谱，然后为所有紧密相关的实体群体预生成社区摘要。面对问题，每个社区摘要被用来生成部分答案，所有部分答案再汇总成最终回答。在处理大约百万个令牌的数据集的全局性理解问题时，我们证明了图 RAG 在答案的全面性和多样性上，相较于传统 RAG 有显著提升。一个开源的、基于 Python 的全局和局部图 RAG 方法的实现将在 https://aka.ms/graphrag 上发布。

> The use of retrieval-augmented generation (RAG) to retrieve relevant information from an external knowledge source enables large language models (LLMs) to answer questions over private and/or previously unseen document collections. However, RAG fails on global questions directed at an entire text corpus, such as "What are the main themes in the dataset?", since this is inherently a query-focused summarization (QFS) task, rather than an explicit retrieval task. Prior QFS methods, meanwhile, fail to scale to the quantities of text indexed by typical RAG systems. To combine the strengths of these contrasting methods, we propose a Graph RAG approach to question answering over private text corpora that scales with both the generality of user questions and the quantity of source text to be indexed. Our approach uses an LLM to build a graph-based text index in two stages: first to derive an entity knowledge graph from the source documents, then to pregenerate community summaries for all groups of closely-related entities. Given a question, each community summary is used to generate a partial response, before all partial responses are again summarized in a final response to the user. For a class of global sensemaking questions over datasets in the 1 million token range, we show that Graph RAG leads to substantial improvements over a naïve RAG baseline for both the comprehensiveness and diversity of generated answers. An open-source, Python-based implementation of both global and local Graph RAG approaches is forthcoming at https://aka.ms/graphrag.

[Arxiv](https://arxiv.org/abs/2404.16130)