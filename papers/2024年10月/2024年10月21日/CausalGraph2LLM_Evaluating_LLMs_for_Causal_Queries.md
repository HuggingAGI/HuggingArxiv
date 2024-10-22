# CausalGraph2LLM：探究 LLM 在因果查询中的表现

发布时间：2024年10月21日

`LLM应用` `科学研究` `人工智能`

> CausalGraph2LLM: Evaluating LLMs for Causal Queries

# 摘要

> 因果关系在科学研究中至关重要，帮助研究人员揭示变量间的真实联系。这些联系通常通过有向无环图（因果图）来表示。随着大型语言模型（LLM）的进步，人们对其在因果推理中的潜力愈发关注。然而，这些任务要求 LLM 有效编码因果图，以支持后续的下游任务。为此，我们提出了一个综合基准 \emph{CausalGraph2LLM}，涵盖多种因果图场景，以评估 LLM 的因果图理解能力。我们将因果查询分为图级和节点级两类，并对开源和闭源模型进行了测试。结果显示，尽管 LLM 在此领域表现出色，但它们对编码方式极为敏感，即使是 GPT-4 和 Gemini-1.5 这样的先进模型，编码偏差也高达 $60\%$。此外，我们还发现 LLM 在处理因果图上下文信息时，可能因参数化记忆而产生偏见。

> Causality is essential in scientific research, enabling researchers to interpret true relationships between variables. These causal relationships are often represented by causal graphs, which are directed acyclic graphs. With the recent advancements in Large Language Models (LLMs), there is an increasing interest in exploring their capabilities in causal reasoning and their potential use to hypothesize causal graphs. These tasks necessitate the LLMs to encode the causal graph effectively for subsequent downstream tasks. In this paper, we propose a comprehensive benchmark, \emph{CausalGraph2LLM}, encompassing a variety of causal graph settings to assess the causal graph understanding capability of LLMs. We categorize the causal queries into two types: graph-level and node-level queries. We benchmark both open-sourced and closed models for our study. Our findings reveal that while LLMs show promise in this domain, they are highly sensitive to the encoding used. Even capable models like GPT-4 and Gemini-1.5 exhibit sensitivity to encoding, with deviations of about $60\%$. We further demonstrate this sensitivity for downstream causal intervention tasks. Moreover, we observe that LLMs can often display biases when presented with contextual information about a causal graph, potentially stemming from their parametric memory.

[Arxiv](https://arxiv.org/abs/2410.15939)