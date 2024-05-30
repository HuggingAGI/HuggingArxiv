# GPT能否革新医学认知？探究其在生物医学机器阅读理解领域的评估表现

发布时间：2024年05月28日

`RAG

理由：这篇论文主要关注的是在闭卷生物医学机器阅读理解（MRC）领域中，对大型语言模型（LLMs）如GPT的评估，并提出了隐式检索增强生成（RAG）策略。这种策略旨在减少对传统向量数据库的依赖，并提高生成自然语言输出的质量。因此，这篇论文的核心贡献在于RAG策略的提出和应用，属于RAG分类。` `生物医学` `机器阅读理解`

> Can GPT Redefine Medical Understanding? Evaluating GPT on Biomedical Machine Reading Comprehension

# 摘要

> 大型语言模型（LLMs）在多领域任务中表现出色，但在闭卷生物医学机器阅读理解（MRC）领域的深度评估尚缺。本研究中，我们对GPT在四个闭卷生物医学MRC基准上进行了评估，并尝试了多种传统提示技术，同时创新性地引入了新的提示方法。针对LLMs固有的检索难题，我们提出了隐式检索增强生成（RAG）策略，有效减少了传统RAG设置中对向量数据库的依赖。此外，我们对生成的自然语言输出进行了质量评估。结果表明，我们的新提示技术在四个数据集中两个达到最佳，其余两个排名第二。实验证明，即使在零-shot条件下，如GPT这样的现代LLMs也能超越监督模型，在两个基准上刷新了最先进（SoTA）记录。

> Large language models (LLMs) have shown remarkable performance on many tasks in different domains. However, their performance in closed-book biomedical machine reading comprehension (MRC) has not been evaluated in depth. In this work, we evaluate GPT on four closed-book biomedical MRC benchmarks. We experiment with different conventional prompting techniques as well as introduce our own novel prompting method. To solve some of the retrieval problems inherent to LLMs, we propose a prompting strategy named Implicit Retrieval Augmented Generation (RAG) that alleviates the need for using vector databases to retrieve important chunks in traditional RAG setups. Moreover, we report qualitative assessments on the natural language generation outputs from our approach. The results show that our new prompting technique is able to get the best performance in two out of four datasets and ranks second in rest of them. Experiments show that modern-day LLMs like GPT even in a zero-shot setting can outperform supervised models, leading to new state-of-the-art (SoTA) results on two of the benchmarks.

![GPT能否革新医学认知？探究其在生物医学机器阅读理解领域的评估表现](../../../paper_images/2405.18682/IRAG.png)

[Arxiv](https://arxiv.org/abs/2405.18682)