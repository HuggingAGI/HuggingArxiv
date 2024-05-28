# 语言代理的元任务规划策略

发布时间：2024年05月26日

`Agent

这篇论文主要探讨了基于大型语言模型（LLM）的智能代理（Agent）在现实世界任务中的规划问题，并提出了一种新的规划方法——元任务规划（MTP）。这种方法专门为基于LLM的协作多代理系统设计，通过将复杂任务分解为一系列从属的元任务来简化规划过程。论文的研究重点在于如何有效地规划和执行复杂任务，特别是在涉及长链异质动作组合的情况下。因此，这篇论文应归类于Agent分类，因为它主要关注的是智能代理的设计和应用，特别是基于LLM的代理系统。` `人工智能` `多代理系统`

> Meta-Task Planning for Language Agents

# 摘要

> 神经语言模型的飞速进步，催生了智能代理研究的新浪潮。不同于传统代理，基于大型语言模型的代理（LLM代理）凭借其卓越的推理与泛化能力，成为实现人工通用智能（AGI）的希望之星。在现实世界任务中，LLM代理的成功离不开有效的规划，这一话题在社区中备受关注。目前，规划方法多将任务转化为一系列可执行动作。然而，对于复杂任务，如何在细粒度上确定可行或最优的动作序列，尤其是涉及长链异质动作组合时，仍是一大挑战。本文提出的元任务规划（MTP），是一种零-shot方法，专为基于LLM的协作多代理系统设计，通过将复杂任务分解为一系列从属的元任务，简化了规划过程。每个元任务随后被转化为可执行动作。MTP在TravelPlanner和API-Bank两个严格基准上的表现令人瞩目，其成功率分别达到约40%和超过14%，远超现有技术水平，彰显了LLM与多代理系统结合的巨大潜力。

> The rapid advancement of neural language models has sparked a new surge of intelligent agent research. Unlike traditional agents, large language model-based agents (LLM agents) have emerged as a promising paradigm for achieving artificial general intelligence (AGI) due to their superior reasoning and generalization capabilities. Effective planning is crucial for the success of LLM agents in real-world tasks, making it a highly pursued topic in the community. Current planning methods typically translate tasks into executable action sequences. However, determining a feasible or optimal sequence for complex tasks at fine granularity, which often requires compositing long chains of heterogeneous actions, remains challenging. This paper introduces Meta-Task Planning (MTP), a zero-shot methodology for collaborative LLM-based multi-agent systems that simplifies complex task planning by decomposing it into a hierarchy of subordinate tasks, or meta-tasks. Each meta-task is then mapped into executable actions. MTP was assessed on two rigorous benchmarks, TravelPlanner and API-Bank. Notably, MTP achieved an average $\sim40\%$ success rate on TravelPlanner, significantly higher than the state-of-the-art (SOTA) baseline ($2.92\%$), and outperforming $LLM_{api}$-4 with ReAct on API-Bank by $\sim14\%$, showing the immense potential of integrating LLM with multi-agent systems.

![语言代理的元任务规划策略](../../../paper_images/2405.16510/x1.png)

![语言代理的元任务规划策略](../../../paper_images/2405.16510/x2.png)

![语言代理的元任务规划策略](../../../paper_images/2405.16510/x3.png)

![语言代理的元任务规划策略](../../../paper_images/2405.16510/x4.png)

![语言代理的元任务规划策略](../../../paper_images/2405.16510/x5.png)

![语言代理的元任务规划策略](../../../paper_images/2405.16510/x6.png)

![语言代理的元任务规划策略](../../../paper_images/2405.16510/x7.png)

[Arxiv](https://arxiv.org/abs/2405.16510)