# 探索通过逐步增强检索行为的提示，提升大型语言模型在相关性建模中的表现

发布时间：2024年08月18日

`LLM应用` `搜索引擎` `用户体验`

> Towards Boosting LLMs-driven Relevance Modeling with Progressive Retrieved Behavior-augmented Prompting

# 摘要

> 相关性建模对于提升搜索引擎的用户体验至关重要，旨在精准匹配用户查询与搜索结果。传统方法仅基于语义一致性，但这一视角过于单一。即便是最先进的LLM，也难以仅凭语义准确判断相关性。本研究创新性地引入用户交互数据，以揭示用户隐含的搜索意图，并提出ProRBP框架，通过渐进式提示技术，有效整合领域知识与LLM，实现更精准的相关性建模。我们在真实数据和在线测试中验证了这一方法的有效性，为LLM在相关性建模中的应用提供了新的工业级解决方案。

> Relevance modeling is a critical component for enhancing user experience in search engines, with the primary objective of identifying items that align with users' queries. Traditional models only rely on the semantic congruence between queries and items to ascertain relevance. However, this approach represents merely one aspect of the relevance judgement, and is insufficient in isolation. Even powerful Large Language Models (LLMs) still cannot accurately judge the relevance of a query and an item from a semantic perspective. To augment LLMs-driven relevance modeling, this study proposes leveraging user interactions recorded in search logs to yield insights into users' implicit search intentions. The challenge lies in the effective prompting of LLMs to capture dynamic search intentions, which poses several obstacles in real-world relevance scenarios, i.e., the absence of domain-specific knowledge, the inadequacy of an isolated prompt, and the prohibitive costs associated with deploying LLMs. In response, we propose ProRBP, a novel Progressive Retrieved Behavior-augmented Prompting framework for integrating search scenario-oriented knowledge with LLMs effectively. Specifically, we perform the user-driven behavior neighbors retrieval from the daily search logs to obtain domain-specific knowledge in time, retrieving candidates that users consider to meet their expectations. Then, we guide LLMs for relevance modeling by employing advanced prompting techniques that progressively improve the outputs of the LLMs, followed by a progressive aggregation with comprehensive consideration of diverse aspects. For online serving, we have developed an industrial application framework tailored for the deployment of LLMs in relevance modeling. Experiments on real-world industry data and online A/B testing demonstrate our proposal achieves promising performance.

[Arxiv](https://arxiv.org/abs/2408.09439)