# 面对较少为人所知的知识领域，我们探究微调和检索增强生成两种方法的优劣。

发布时间：2024年03月03日

`RAG`

> Fine Tuning vs. Retrieval Augmented Generation for Less Popular Knowledge

# 摘要

> LLMs凭借强大的记忆力囊括了大量的事实知识，并在各类任务和领域中表现出色，但当遇到不常出现或低频的概念与实体，特别是在专业应用场景下，其性能往往有所下滑。为此，有两种主流策略来提升LLMs对低频话题的表现力，即检索增强生成（RAG）和基于合成数据的微调（FT）。本论文深入探究了RAG与FT在定制LLMs以应对问答任务中低频实体问题时的效果，并发现FT能显著提高各流行度实体的任务完成度，尤其对于热门和冷门群体效果更为明显；与此同时，RAG相较于其他方法表现更优。另外，RAG与FT两种方法的成功背后离不开检索技术与数据增强技术的发展与进步。为了促进进一步的研究，我们已将数据和代码开源，可在https://github.com/HeydarSoudani/RAGvsFT查看下载。

> Large language models (LLMs) memorize a vast amount of factual knowledge, exhibiting strong performance across diverse tasks and domains. However, it has been observed that the performance diminishes when dealing with less-popular or low-frequency concepts and entities, for example in domain specific applications. The two prominent approaches to enhance the performance of LLMs on low-frequent topics are: Retrieval Augmented Generation (RAG) and fine-tuning (FT) over synthetic data. This paper explores and evaluates the impact of RAG and FT on customizing LLMs in handling low-frequency entities on question answering task. Our findings indicate that FT significantly boosts the performance across entities of varying popularity, especially in the most and least popular groups, while RAG surpasses other methods. Additionally, the success of both RAG and FT approaches is amplified by advancements in retrieval and data augmentation techniques. We release our data and code at https://github.com/HeydarSoudani/RAGvsFT.

[Arxiv](https://arxiv.org/abs/2403.01432)