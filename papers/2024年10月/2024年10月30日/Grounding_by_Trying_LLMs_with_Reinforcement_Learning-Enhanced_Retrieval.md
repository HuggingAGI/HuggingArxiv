# 通过尝试来接地：具有强化学习增强检索功能的大型语言模型

发布时间：2024年10月30日

`LLM应用` `语言模型`

> Grounding by Trying: LLMs with Reinforcement Learning-Enhanced Retrieval

# 摘要

> 摘要：通过允许大型语言模型（LLMs）搜索信息并将其答案基于真实来源，LLMs 的幻觉正日益得到缓解。不幸的是，LLMs 常常难以提出正确的搜索查询，尤其是在处理复杂或其他间接主题时。观察到 LLMs 可以通过尝试不同的查询并学习对成功产生相关结果的查询进行加权来学习搜索相关事实，我们引入了通过尝试进行检索学习（LeReT），这是一个强化学习框架，用于探索搜索查询并使用基于偏好的优化来提高其质量。LeReT 可以将绝对检索准确率提高多达 29％，将下游生成器评估提高 17％。LeReT 的简单性和灵活性使其能够应用于任意现成的检索器，并使其成为改进一般 LLM 管道的有前途的技术。项目网站：此 http 网址。

> 
Abstract:The hallucinations of large language models (LLMs) are increasingly mitigated by allowing LLMs to search for information and to ground their answers in real sources. Unfortunately, LLMs often struggle with posing the right search queries, especially when dealing with complex or otherwise indirect topics. Observing that LLMs can learn to search for relevant facts by $\textit{trying}$ different queries and learning to up-weight queries that successfully produce relevant results, we introduce $\underline{Le}$arning to $\underline{Re}$trieve by $\underline{T}$rying (LeReT), a reinforcement learning framework that explores search queries and uses preference-based optimization to improve their quality. LeReT can improve the absolute retrieval accuracy by up to 29% and the downstream generator evaluations by 17%. The simplicity and flexibility of LeReT allows it to be applied to arbitrary off-the-shelf retrievers and makes it a promising technique for improving general LLM pipelines. Project website: this http URL.
    

[Arxiv](https://arxiv.org/pdf/2410.23214)