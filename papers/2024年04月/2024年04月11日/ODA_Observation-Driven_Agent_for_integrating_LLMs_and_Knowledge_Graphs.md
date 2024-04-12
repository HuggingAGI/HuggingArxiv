# ODA，即观察驱动代理，旨在融合大型语言模型与知识图谱，提升智能代理的性能。

发布时间：2024年04月11日

`Agent` `知识图谱`

> ODA: Observation-Driven Agent for integrating LLMs and Knowledge Graphs

# 摘要

> 结合大型语言模型和知识图谱在自然语言处理领域取得了突破性成果。但目前的方法往往只依赖模型对问题的解析，未能充分发挥知识图谱内蕴含的深层认知价值。为此，我们提出了观察驱动代理（ODA），一种专为处理知识图谱任务而设计的AI框架。该框架通过全局观察引入知识图谱的推理能力，并通过循环往复的观察、行动和反思过程提升推理效能。面对知识量爆炸性增长的挑战，我们创新设计了递归式观察机制，并将观察成果融入行动与反思环节。经过大量实验验证，ODA在多个数据集上达到了顶尖的性能，特别是在准确率上分别实现了12.87%和8.9%的显著提升。

> The integration of Large Language Models (LLMs) and knowledge graphs (KGs) has achieved remarkable success in various natural language processing tasks. However, existing methodologies that integrate LLMs and KGs often navigate the task-solving process solely based on the LLM's analysis of the question, overlooking the rich cognitive potential inherent in the vast knowledge encapsulated in KGs. To address this, we introduce Observation-Driven Agent (ODA), a novel AI agent framework tailored for tasks involving KGs. ODA incorporates KG reasoning abilities via global observation that enhances reasoning capabilities through a cyclical paradigm of observation, action, and reflection. Confronting the exponential explosion of knowledge during observation, we innovatively design a recursive observation mechanism. Subsequently, we integrate the observed knowledge into the action and reflection modules. Through extensive experiments, ODA demonstrates state-of-the-art performance on several datasets, notably achieving accuracy improvements of 12.87% and 8.9%.

![ODA，即观察驱动代理，旨在融合大型语言模型与知识图谱，提升智能代理的性能。](../../../paper_images/2404.07677/intropic2.png)

![ODA，即观察驱动代理，旨在融合大型语言模型与知识图谱，提升智能代理的性能。](../../../paper_images/2404.07677/workflow5.png)

![ODA，即观察驱动代理，旨在融合大型语言模型与知识图谱，提升智能代理的性能。](../../../paper_images/2404.07677/caseflow3.png)

[Arxiv](https://arxiv.org/abs/2404.07677)