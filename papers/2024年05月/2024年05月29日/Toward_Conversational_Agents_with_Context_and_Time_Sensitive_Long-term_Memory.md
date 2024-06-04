# 构建具备上下文感知和时间敏感长期记忆的对话系统

发布时间：2024年05月29日

`Agent

这篇论文主要关注的是具有长期记忆的对话代理，并针对长篇对话数据的检索问题提出了新的挑战和解决方案。论文中提到的检索增强生成（RAG）技术是用于改进对话代理性能的方法，而不是作为研究主题本身。因此，这篇论文更侧重于Agent的应用和发展，而不是RAG技术的理论研究，也不是LLM的理论探讨或应用案例。论文通过创建新的数据集和开发新型检索模型，旨在推动记忆增强对话代理在多领域AI应用中的发展，这符合Agent分类的特征。` `对话系统` `人工智能`

> Toward Conversational Agents with Context and Time Sensitive Long-term Memory

# 摘要

> 近期，具有长期记忆的对话代理引起了广泛关注，推动了采用检索增强生成（RAG）技术的语言模型的迅猛发展。然而，多数研究侧重于从维基百科等大型文本数据库中检索信息，而非长篇对话。本文指出，长篇对话数据的检索面临两大挑战：一是基于时间或事件顺序的查询，要求模型追溯过往对话；二是需要对话上下文来澄清的模糊查询。为此，我们创建了一套新的模糊与时间相关查询数据集，并发现传统RAG方法对此类问题处理不佳。我们进而研发了一种结合链式表搜索、向量数据库检索及提示消歧的新型检索模型，显著提升了处理这些任务的能力。我们期望这一新数据集及先进的RAG代理能成为推动记忆增强对话代理在多领域AI应用中发展的关键里程碑。

> There has recently been growing interest in conversational agents with long-term memory which has led to the rapid development of language models that use retrieval-augmented generation (RAG). Until recently, most work on RAG has focused on information retrieval from large databases of texts, like Wikipedia, rather than information from long-form conversations. In this paper, we argue that effective retrieval from long-form conversational data faces two unique problems compared to static database retrieval: 1) time/event-based queries, which requires the model to retrieve information about previous conversations based on time or the order of a conversational event (e.g., the third conversation on Tuesday), and 2) ambiguous queries that require surrounding conversational context to understand. To better develop RAG-based agents that can deal with these challenges, we generate a new dataset of ambiguous and time-based questions that build upon a recent dataset of long-form, simulated conversations, and demonstrate that standard RAG based approaches handle such questions poorly. We then develop a novel retrieval model which combines chained-of-table search methods, standard vector-database retrieval, and a prompting method to disambiguate queries, and demonstrate that this approach substantially improves over current methods at solving these tasks. We believe that this new dataset and more advanced RAG agent can act as a key benchmark and stepping stone towards effective memory augmented conversational agents that can be used in a wide variety of AI applications.

![构建具备上下文感知和时间敏感长期记忆的对话系统](../../../paper_images/2406.00057/cotable.png)

![构建具备上下文感知和时间敏感长期记忆的对话系统](../../../paper_images/2406.00057/query.png)

![构建具备上下文感知和时间敏感长期记忆的对话系统](../../../paper_images/2406.00057/f2_bar.png)

![构建具备上下文感知和时间敏感长期记忆的对话系统](../../../paper_images/2406.00057/classification_per_dataset_bar.png)

[Arxiv](https://arxiv.org/abs/2406.00057)