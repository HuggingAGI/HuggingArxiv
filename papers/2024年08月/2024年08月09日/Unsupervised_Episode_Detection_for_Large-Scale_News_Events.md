# 大规模新闻事件的无监督片段检测

发布时间：2024年08月09日

`LLM应用` `事件检测`

> Unsupervised Episode Detection for Large-Scale News Events

# 摘要

> 情节结构因其可解释性和适应性，在大规模关键事件中展现出独特优势。然而，当前的自动事件检测技术却未能充分利用这一特性。为此，我们提出了一项新任务——情节检测，旨在从新闻语料库中精准识别关键事件的情节。每个情节由核心实体在特定时空背景下的行动构成，是关键事件的重要组成部分。自动检测情节面临挑战，因无法简单依赖时间和地点的明确提及，或通过语义相似性来整合不一致的情节共指。为此，我们设计了EpiMine框架，通过自动识别关键术语、基于自然情节分区的候选情节确定，以及利用大型语言模型进行推理细化，最终形成情节集群。我们在三个真实事件数据集上进行了测试，EpiMine以平均59.2%的提升，显著超越了所有基线方法。

> Episodic structures are inherently interpretable and adaptable to evolving large-scale key events. However, state-of-the-art automatic event detection methods overlook event episodes and, therefore, struggle with these crucial characteristics. This paper introduces a novel task, episode detection, aimed at identifying episodes from a news corpus containing key event articles. An episode describes a cohesive cluster of core entities (e.g., "protesters", "police") performing actions at a specific time and location. Furthermore, an episode is a significant part of a larger group of episodes under a particular key event. Automatically detecting episodes is challenging because, unlike key events and atomic actions, we cannot rely on explicit mentions of times and locations to distinguish between episodes or use semantic similarity to merge inconsistent episode co-references. To address these challenges, we introduce EpiMine, an unsupervised episode detection framework that (1) automatically identifies the most salient, key-event-relevant terms and segments, (2) determines candidate episodes in an article based on natural episodic partitions estimated through shifts in discriminative term combinations, and (3) refines and forms final episode clusters using large language model-based reasoning on the candidate episodes. We construct three diverse, real-world event datasets annotated at the episode level. EpiMine outperforms all baselines on these datasets by an average 59.2% increase across all metrics.

[Arxiv](https://arxiv.org/abs/2408.04873)