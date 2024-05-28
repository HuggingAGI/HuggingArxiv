# 智能车间中的大型语言模型多代理制造系统

发布时间：2024年05月27日

`Agent

这篇论文介绍了一种基于大型语言模型（LLM-based）的多代理智能车间制造系统，该系统通过明确各种代理及其协作方式来实现对车间状况的智能分析和最优机器选择。系统中的代理角色包括机器服务器代理（MSA）、招标邀请代理（BIA）、投标代理（BA）、思考代理（TA）和决策代理（DA）。这些代理通过协作来高效地分配和传输工件，与传统调度方法形成对比。因此，这篇论文更符合Agent分类，因为它主要关注的是代理系统的设计和应用。` `智能制造` `生产调度`

> A Large Language Model-based multi-agent manufacturing system for intelligent shopfloor

# 摘要

> 随着生产力的提升，客户对多品种、小批量生产的需求日益增长，传统制造系统难以迅速适应这种频繁变化的生产任务。为此，本研究提出了一种基于大型语言模型（LLM-based）的多代理智能车间制造系统，该系统通过明确各种代理及其协作方式，实现了对车间状况的智能分析和最优机器选择。系统中的代理角色包括机器服务器代理（MSA）、招标邀请代理（BIA）、投标代理（BA）、思考代理（TA）和决策代理（DA）。在TA和DA的辅助下，BIA能够根据BA提供的机器信息，智能分配订单。MSA则负责将代理与实际车间有效连接。通过这些代理的协作，系统能够高效地分配和传输工件，与传统调度方法形成鲜明对比。此外，通过对比实验，该系统的性能得到了验证。

> As productivity advances, the demand of customers for multi-variety and small-batch production is increasing, thereby putting forward higher requirements for manufacturing systems. When production tasks frequent changes due to this demand, traditional manufacturing systems often cannot response promptly. The multi-agent manufacturing system is proposed to address this problem. However, because of technical limitations, the negotiation among agents in this kind of system is realized through predefined heuristic rules, which is not intelligent enough to deal with the multi-variety and small batch production. To this end, a Large Language Model-based (LLM-based) multi-agent manufacturing system for intelligent shopfloor is proposed in the present study. This system delineates the diverse agents and defines their collaborative methods. The roles of the agents encompass Machine Server Agent (MSA), Bid Inviter Agent (BIA), Bidder Agent (BA), Thinking Agent (TA), and Decision Agent (DA). Due to the support of LLMs, TA and DA acquire the ability of analyzing the shopfloor condition and choosing the most suitable machine, as opposed to executing a predefined program artificially. The negotiation between BAs and BIA is the most crucial step in connecting manufacturing resources. With the support of TA and DA, BIA will finalize the distribution of orders, relying on the information of each machine returned by BA. MSAs bears the responsibility for connecting the agents with the physical shopfloor. This system aims to distribute and transmit workpieces through the collaboration of the agents with these distinct roles, distinguishing it from other scheduling approaches. Comparative experiments were also conducted to validate the performance of this system.

[Arxiv](https://arxiv.org/abs/2405.16887)