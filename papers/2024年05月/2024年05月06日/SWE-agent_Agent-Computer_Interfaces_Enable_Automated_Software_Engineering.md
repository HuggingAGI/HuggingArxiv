# SWE-agent：通过代理-计算机接口，自动化软件工程得以实现在

发布时间：2024年05月06日

`Agent

这篇论文介绍了一个名为SWE-agent的自主系统，它利用语言模型与计算机互动，专门解决软件工程中的问题。SWE-agent通过特制的代理-计算机接口（ACI）在代码编写、仓库管理及程序执行上展现出更强的能力，并在SWE-bench测试中取得了显著的成果。因此，这篇论文应归类为Agent，因为它主要关注的是一个特定领域的自主代理系统及其性能。` `软件工程` `自动化工具`

> SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering

# 摘要

> 软件工程既需精通代码编写，亦需熟练与计算机沟通。本文推出的SWE-agent，是一款利用语言模型与计算机互动，专攻软件工程难题的自主系统。通过特制的代理-计算机接口（ACI），SWE-agent在代码编写、仓库管理及程序执行上展现出更强的能力。在SWE-bench测试中，SWE-agent解决了12.5%的问题，远超之前基于检索增强生成（RAG）的3.8%最佳记录。本文深入分析了ACI设计对代理行为及性能的影响，并分享了高效设计的心得。

> Software engineering is a challenging task requiring proficiency in both code generation and interacting with computers. In this paper, we introduce SWE-agent, an autonomous system that uses a language model to interact with a computer to solve software engineering tasks. We show that a custom-built agent-computer interface (ACI) greatly enhances the ability of an agent to create and edit code files, navigate entire repositories and execute programs. On SWE-bench, SWE-agent is able to solve 12.5% of issues, compared to the previous best of 3.8% achieved with retrieval-augmented generation (RAG). We explore how ACI design impacts an agent's behavior and performance, and provide insights on effective design.

[Arxiv](https://arxiv.org/abs/2405.15793)