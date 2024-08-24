# 图检索强化可信推理

发布时间：2024年08月22日

`Agent` `人工智能`

> Graph Retrieval Augmented Trustworthiness Reasoning

# 摘要

> 在信息不完整的多人游戏中，信任推理至关重要，它帮助代理识别盟友和对手，优化决策过程。传统方法依赖预训练模型，需大量特定数据和奖励反馈，但缺乏实时适应性，限制了其在动态环境中的效能。本文引入图检索增强推理（GRATR）框架，利用RAG技术强化代理的信任推理。GRATR构建动态信任图，实时更新证据信息，并检索信任数据以提升LLMs的推理能力。实验证明，GRATR在“狼人”游戏中胜率超基准方法30%，推理性能卓越。此外，GRATR有效减少LLM的幻觉问题，如身份和目标遗忘，并通过信任图使推理过程更透明、可追溯。

> Trustworthiness reasoning is crucial in multiplayer games with incomplete information, enabling agents to identify potential allies and adversaries, thereby enhancing reasoning and decision-making processes. Traditional approaches relying on pre-trained models necessitate extensive domain-specific data and considerable reward feedback, with their lack of real-time adaptability hindering their effectiveness in dynamic environments. In this paper, we introduce the Graph Retrieval Augmented Reasoning (GRATR) framework, leveraging the Retrieval-Augmented Generation (RAG) technique to bolster trustworthiness reasoning in agents. GRATR constructs a dynamic trustworthiness graph, updating it in real-time with evidential information, and retrieves relevant trust data to augment the reasoning capabilities of Large Language Models (LLMs). We validate our approach through experiments on the multiplayer game "Werewolf," comparing GRATR against baseline LLM and LLM enhanced with Native RAG and Rerank RAG. Our results demonstrate that GRATR surpasses the baseline methods by over 30\% in winning rate, with superior reasoning performance. Moreover, GRATR effectively mitigates LLM hallucinations, such as identity and objective amnesia, and crucially, it renders the reasoning process more transparent and traceable through the use of the trustworthiness graph.

[Arxiv](https://arxiv.org/abs/2408.12333)