# 基于大型语言模型的属性信息检索评估框架

发布时间：2024年09月12日

`RAG` `搜索引擎` `信息检索`

> An Evaluation Framework for Attributed Information Retrieval using Large Language Models

# 摘要

> 随着 LLM 在信息搜索中的成功，搜索引擎开始采用生成方法，提供带有引用的答案。本文聚焦于更具挑战性的信息搜索场景，这些场景因查询的开放性和答案多样性而复杂。我们设计了一个可复现的评估框架，使用不同架构（生成、检索后生成、生成后检索）来测试归属信息搜索。实验结果显示，不同场景对答案的正确性和归属性有显著影响。

> With the growing success of Large Language models (LLMs) in information-seeking scenarios, search engines are now adopting generative approaches to provide answers along with in-line citations as attribution. While existing work focuses mainly on attributed question answering, in this paper, we target information-seeking scenarios which are often more challenging due to the open-ended nature of the queries and the size of the label space in terms of the diversity of candidate-attributed answers per query. We propose a reproducible framework to evaluate and benchmark attributed information seeking, using any backbone LLM, and different architectural designs: (1) Generate (2) Retrieve then Generate, and (3) Generate then Retrieve. Experiments using HAGRID, an attributed information-seeking dataset, show the impact of different scenarios on both the correctness and attributability of answers.

[Arxiv](https://arxiv.org/abs/2409.08014)