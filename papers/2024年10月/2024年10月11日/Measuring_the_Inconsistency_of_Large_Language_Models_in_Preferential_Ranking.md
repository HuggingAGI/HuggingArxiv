# 探究大型语言模型在优先排序中的不一致表现

发布时间：2024年10月11日

`LLM理论` `人工智能` `决策支持`

> Measuring the Inconsistency of Large Language Models in Preferential Ranking

# 摘要

> 尽管 LLM 技术日新月异，但其偏见与幻觉问题依旧，而它们在提供一致优先排序方面的能力仍待深入探究。本研究聚焦于 LLM 在复杂决策环境或缺乏明确答案场景中，能否提供一致的序数偏好。我们基于序理论，定义了包括传递性、不对称性、可逆性及无关选项独立性在内的一致性标准。实验结果显示，当前最先进的 LLM 难以满足这些标准，偏好易受无关选项影响，传递性表现不佳，凸显了强烈的地位偏见。这些发现揭示了 LLM 在优先排序上的显著不一致性，呼吁更多研究以弥补这些不足。

> Despite large language models' (LLMs) recent advancements, their bias and hallucination issues persist, and their ability to offer consistent preferential rankings remains underexplored. This study investigates the capacity of LLMs to provide consistent ordinal preferences, a crucial aspect in scenarios with dense decision space or lacking absolute answers. We introduce a formalization of consistency based on order theory, outlining criteria such as transitivity, asymmetry, reversibility, and independence from irrelevant alternatives. Our diagnostic experiments on selected state-of-the-art LLMs reveal their inability to meet these criteria, indicating a strong positional bias and poor transitivity, with preferences easily swayed by irrelevant alternatives. These findings highlight a significant inconsistency in LLM-generated preferential rankings, underscoring the need for further research to address these limitations.

[Arxiv](https://arxiv.org/abs/2410.08851)