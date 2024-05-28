# SWE-agent：通过代理-计算机接口，软件工程自动化得以实现

发布时间：2024年05月06日

`Agent

这篇论文介绍了一个名为SWE-agent的自主系统，它利用语言模型与计算机进行交互，以解决软件工程中的问题。特别强调了其代理-计算机接口（ACI）的设计，以及该接口如何提升代理在编码、仓库导航及程序执行上的能力。论文还提到了SWE-agent在SWE-bench测试中的表现，显示其在解决问题上的效率远超先前的RAG方法。因此，这篇论文更符合Agent分类，因为它主要关注的是一个特定的代理系统及其在软件工程中的应用。` `软件工程` `人工智能`

> SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering

# 摘要

> 软件工程既需代码创作之巧，亦需计算机交互之能。本文推出的SWE-agent，乃一自主系统，凭借语言模型之力，与计算机对话，攻克软件工程难题。其特制的代理-计算机接口（ACI），显著提升了代理在编码、仓库导航及程序执行上的能力。在SWE-bench测试中，SWE-agent解决问题的比例高达12.5%，远超先前RAG方法的3.8%。本文深入分析了ACI设计对代理行为与性能的影响，并分享了设计高效接口的洞见。

> Software engineering is a challenging task requiring proficiency in both code generation and interacting with computers. In this paper, we introduce SWE-agent, an autonomous system that uses a language model to interact with a computer to solve software engineering tasks. We show that a custom-built agent-computer interface (ACI) greatly enhances the ability of an agent to create and edit code files, navigate entire repositories and execute programs. On SWE-bench, SWE-agent is able to solve 12.5% of issues, compared to the previous best of 3.8% achieved with retrieval-augmented generation (RAG). We explore how ACI design impacts an agent's behavior and performance, and provide insights on effective design.

[Arxiv](https://arxiv.org/abs/2405.15793)