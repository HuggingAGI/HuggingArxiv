# 代理型大型语言模型中ReAct提示的基础尚显脆弱

发布时间：2024年05月22日

`Agent

这篇论文主要探讨了大型语言模型（LLMs）在推理能力方面的表现，特别是在代理型LLMs中使用基于ReAct的提示方法的效果。论文通过实验分析了这种提示方法对序列决策能力的影响，并揭示了性能提升的真正原因，这与传统的认知有所不同。研究结果表明，LLMs的推理能力更多依赖于输入示例与查询之间的相似性，而不是其内在的推理机制。因此，这篇论文更符合Agent分类，因为它关注的是如何通过特定的提示方法来增强代理型LLMs的决策能力。` `人工智能` `认知科学`

> On the Brittle Foundations of ReAct Prompting for Agentic Large Language Models

# 摘要

> 大型语言模型（LLMs）的推理能力一直是热议的焦点。基于ReAct的提示方法因其声称能提升代理型LLMs的序列决策能力而备受关注。然而，这种提升的根源尚不明朗。本文通过系统性地调整输入提示，对基于ReAct的提示在增强LLMs序列决策能力方面的效果进行了深入分析，结果发现，性能提升并非源自“推理与行动的交错”或推理轨迹的内容，这与普遍认知相悖。实际上，LLMs的表现更多依赖于输入示例与查询之间的相似性，这无形中增加了提示设计者提供特定实例示例的负担，加大了人类的认知压力。我们的研究揭示，LLMs展现出的推理能力，更多是基于示例与查询的匹配和近似检索，而非其内在的推理机制。

> The reasoning abilities of Large Language Models (LLMs) remain a topic of debate. Some methods such as ReAct-based prompting, have gained popularity for claiming to enhance sequential decision-making abilities of agentic LLMs. However, it is unclear what is the source of improvement in LLM reasoning with ReAct based prompting. In this paper we examine these claims of ReAct based prompting in improving agentic LLMs for sequential decision-making. By introducing systematic variations to the input prompt we perform a sensitivity analysis along the claims of ReAct and find that the performance is minimally influenced by the "interleaving reasoning trace with action execution" or the content of the generated reasoning traces in ReAct, contrary to original claims and common usage. Instead, the performance of LLMs is driven by the similarity between input example tasks and queries, implicitly forcing the prompt designer to provide instance-specific examples which significantly increases the cognitive burden on the human. Our investigation shows that the perceived reasoning abilities of LLMs stem from the exemplar-query similarity and approximate retrieval rather than any inherent reasoning abilities.

[Arxiv](https://arxiv.org/abs/2405.13966)