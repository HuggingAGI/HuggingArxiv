# Re-Invoke：零-shot 工具检索中的工具调用重写技术

发布时间：2024年08月03日

`Agent` `软件开发` `人工智能`

> Re-Invoke: Tool Invocation Rewriting for Zero-Shot Tool Retrieval

# 摘要

> 随着大型语言模型 (LLM) 的发展，自主代理能够运用多种工具进行复杂推理和任务执行。但工具集的扩大使得精准选择工具成为难题，影响了工具使用的可靠性。为此，我们推出了 Re-Invoke，一种无需训练的无监督工具检索技术，能有效应对大型工具集。该方法首先在工具索引阶段生成涵盖各方面的多样化合成查询，然后在推理阶段利用 LLM 解析用户查询中的关键信息和意图，最终通过基于意图的多视角相似性排序策略，精准匹配最合适的工具。评估结果表明，Re-Invoke 在单工具和多工具应用中均大幅超越现有技术，且无需监督。在 ToolE 数据集上，单工具检索的 nDCG@5 提升了 20%，多工具检索提升了 39%。

> Recent advances in large language models (LLMs) have enabled autonomous agents with complex reasoning and task-fulfillment capabilities using a wide range of tools. However, effectively identifying the most relevant tools for a given task becomes a key bottleneck as the toolset size grows, hindering reliable tool utilization. To address this, we introduce Re-Invoke, an unsupervised tool retrieval method designed to scale effectively to large toolsets without training. Specifically, we first generate a diverse set of synthetic queries that comprehensively cover different aspects of the query space associated with each tool document during the tool indexing phase. Second, we leverage LLM's query understanding capabilities to extract key tool-related context and underlying intents from user queries during the inference phase. Finally, we employ a novel multi-view similarity ranking strategy based on intents to pinpoint the most relevant tools for each query. Our evaluation demonstrates that Re-Invoke significantly outperforms state-of-the-art alternatives in both single-tool and multi-tool scenarios, all within a fully unsupervised setting. Notably, on the ToolE datasets, we achieve a 20% relative improvement in nDCG@5 for single-tool retrieval and a 39% improvement for multi-tool retrieval.

[Arxiv](https://arxiv.org/abs/2408.01875)