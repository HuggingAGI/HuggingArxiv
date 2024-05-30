# 规范学习架构：一种生成代理框架，旨在促进多代理间的合作与规范学习

发布时间：2024年05月29日

`Agent

这篇论文主要探讨了生成代理（Agent）在社会结构影响下的合作问题，并提出了一种名为“规范模块”的架构来提升代理的合作效率。该研究关注代理如何识别和适应环境规范，以及如何通过互动学习识别权威机构，从而协调制裁行为，塑造社会环境中的主要行为，提升整体福利。因此，这篇论文更符合Agent分类，因为它主要关注的是代理的设计和其在特定环境中的行为。` `社会科学` `人工智能`

> Normative Modules: A Generative Agent Architecture for Learning Norms that Supports Multi-Agent Cooperation

# 摘要

> 生成代理利用 LLM 解析环境并执行任务，已在多个领域展现解决复杂问题的能力。但在社会结构（如规范）影响下，代理间及代理与人类间的合作仍面临挑战。本文提出“规范模块”架构，旨在通过代理识别并适应环境规范，提升合作效率。我们聚焦合作中的均衡选择问题，并依据实施相关均衡的分类机构，优化代理设计。规范模块赋予代理通过互动学习识别权威机构的能力，进而协调制裁行为，塑造社会环境中的主要行为，提升整体福利。我们构建了支持机构的新环境，并基于代理与同伴及机构的互动，评估了框架的两个关键指标：识别非权威机构和权威机构的能力。结果显示，具备规范模块的代理能实现更稳定的合作，为考虑规范基础设施的环境和代理设计研究开辟了新方向。

> Generative agents, which implement behaviors using a large language model (LLM) to interpret and evaluate an environment, has demonstrated the capacity to solve complex tasks across many social and technological domains. However, when these agents interact with other agents and humans in presence of social structures such as existing norms, fostering cooperation between them is a fundamental challenge. In this paper, we develop the framework of a 'Normative Module': an architecture designed to enhance cooperation by enabling agents to recognize and adapt to the normative infrastructure of a given environment. We focus on the equilibrium selection aspect of the cooperation problem and inform our agent design based on the existence of classification institutions that implement correlated equilibrium to provide effective resolution of the equilibrium selection problem. Specifically, the normative module enables agents to learn through peer interactions which of multiple candidate institutions in the environment, does a group treat as authoritative. By enabling normative competence in this sense, agents gain ability to coordinate their sanctioning behaviour; coordinated sanctioning behaviour in turn shapes primary behaviour within a social environment, leading to higher average welfare. We design a new environment that supports institutions and evaluate the proposed framework based on two key criteria derived from agent interactions with peers and institutions: (i) the agent's ability to disregard non-authoritative institutions and (ii) the agent's ability to identify authoritative institutions among several options. We show that these capabilities allow the agent to achieve more stable cooperative outcomes compared to baseline agents without the normative module, paving the way for research in a new avenue of designing environments and agents that account for normative infrastructure.

![规范学习架构：一种生成代理框架，旨在促进多代理间的合作与规范学习](../../../paper_images/2405.19328/x1.png)

![规范学习架构：一种生成代理框架，旨在促进多代理间的合作与规范学习](../../../paper_images/2405.19328/non_authoritative_inst.png)

![规范学习架构：一种生成代理框架，旨在促进多代理间的合作与规范学习](../../../paper_images/2405.19328/authoritative_inst.png)

[Arxiv](https://arxiv.org/abs/2405.19328)