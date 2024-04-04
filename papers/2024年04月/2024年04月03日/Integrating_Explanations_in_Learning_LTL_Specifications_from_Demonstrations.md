# 在学习LTL规范的过程中融合解释

发布时间：2024年04月03日

`LLM应用` `人工智能` `形式化验证`

> Integrating Explanations in Learning LTL Specifications from Demonstrations

# 摘要

> 本文探讨了最新的大型语言模型（LLMs）是否能助力将人类的阐释转化为有力支持从示范中学习线性时序逻辑（LTL）的格式。LLMs与优化方法都能从示范中提炼出LTL规范，但各有不足。LLMs能迅速提出解决方案并整合人类阐释，但其缺乏稳定性和可靠性，限制了其在关键安全领域的应用。而优化方法虽能提供正式保证，却难以处理自然语言阐释，且面临扩展性问题。我们提出了一种结合LLMs与优化方法的原则性途径，以准确转换人类阐释与示范为LTL规范。基于此，我们开发了名为Janaka的工具，并透过一系列案例研究，验证了结合阐释与示范学习LTL规范的有效性。

> This paper investigates whether recent advances in Large Language Models (LLMs) can assist in translating human explanations into a format that can robustly support learning Linear Temporal Logic (LTL) from demonstrations. Both LLMs and optimization-based methods can extract LTL specifications from demonstrations; however, they have distinct limitations. LLMs can quickly generate solutions and incorporate human explanations, but their lack of consistency and reliability hampers their applicability in safety-critical domains. On the other hand, optimization-based methods do provide formal guarantees but cannot process natural language explanations and face scalability challenges. We present a principled approach to combining LLMs and optimization-based methods to faithfully translate human explanations and demonstrations into LTL specifications. We have implemented a tool called Janaka based on our approach. Our experiments demonstrate the effectiveness of combining explanations with demonstrations in learning LTL specifications through several case studies.

![在学习LTL规范的过程中融合解释](../../../paper_images/2404.02872/CAVfig.drawio.png)

[Arxiv](https://arxiv.org/abs/2404.02872)