# extsc{Neon}：用于强化问答的新闻实体交互提取

发布时间：2024年11月20日

`LLM应用` `知识图谱`

> Neon: News Entity-Interaction Extraction for Enhanced Question Answering

# 摘要

> 捕获近乎实时的新鲜信息，并借此增强现有的大型语言模型（LLMs），这对于生成最新、有依据且可靠的输出极为关键。当LLMs用于诸如与近期或正在发生的涉及实体的网络搜索等快速发展领域的信息任务时，此问题尤为棘手，因为生成与时间相关的响应需要获取最新的新闻源。然而，LLMs的参数化内存所构建的信息通常过时，原型检索系统的网络结果可能无法捕捉最新的相关信息，也难以处理不断变化的新闻中的冲突报道。为应对这一挑战，我们推出了NEON框架，旨在提取新闻文章中所描述的新兴实体交互，比如事件或活动。NEON构建了一个以实体为中心且带有时间戳的知识图谱，用于捕获此类交互，进而提升与新闻事件相关的问答能力。我们的框架创新之处在于将开放信息提取（openIE）样式的元组集成到LLMs中，实现上下文检索增强生成。这种集成在处理时间、以实体为中心的搜索查询时，问答性能有了显著提升。通过NEON，LLMs能够给出更准确、可靠和最新的回应。

> Capturing fresh information in near real-time and using it to augment existing large language models (LLMs) is essential to generate up-to-date, grounded, and reliable output. This problem becomes particularly challenging when LLMs are used for informational tasks in rapidly evolving fields, such as Web search related to recent or unfolding events involving entities, where generating temporally relevant responses requires access to up-to-the-hour news sources. However, the information modeled by the parametric memory of LLMs is often outdated, and Web results from prototypical retrieval systems may fail to capture the latest relevant information and struggle to handle conflicting reports in evolving news. To address this challenge, we present the NEON framework, designed to extract emerging entity interactions -- such as events or activities -- as described in news articles. NEON constructs an entity-centric timestamped knowledge graph that captures such interactions, thereby facilitating enhanced QA capabilities related to news events. Our framework innovates by integrating open Information Extraction (openIE) style tuples into LLMs to enable in-context retrieval-augmented generation. This integration demonstrates substantial improvements in QA performance when tackling temporal, entity-centric search queries. Through NEON, LLMs can deliver more accurate, reliable, and up-to-date responses.

[Arxiv](https://arxiv.org/abs/2411.12449)