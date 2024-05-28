# SWE-agent：通过代理-计算机接口，自动化软件工程得以实现

发布时间：2024年05月06日

`Agent

理由：该论文介绍了一个名为SWE-agent的自主系统，该系统利用语言模型与计算机协作解决软件工程问题。它通过特制的代理-计算机接口（ACI）在代码编写、仓库管理及程序执行上展现出显著的提升。这个系统是一个Agent，因为它是一个自主的实体，能够与环境（计算机）互动并执行任务。此外，论文中提到的SWE-bench测试结果和ACI设计分析进一步强调了该系统作为Agent的特性。` `软件工程` `自动化工具`

> SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering

# 摘要

> 软件工程既需精通代码编写，亦需熟练与计算机互动。本文推出的SWE-agent，是一款利用语言模型与计算机协作，专攻软件工程难题的自主系统。通过特制的代理-计算机接口（ACI），SWE-agent在代码编写、仓库管理及程序执行上展现出显著的提升。在SWE-bench测试中，SWE-agent成功解决了12.5%的问题，远超之前基于检索增强生成（RAG）的3.8%最佳记录。本文深入分析了ACI设计对代理行为及性能的影响，并分享了高效设计的关键见解。

> Software engineering is a challenging task requiring proficiency in both code generation and interacting with computers. In this paper, we introduce SWE-agent, an autonomous system that uses a language model to interact with a computer to solve software engineering tasks. We show that a custom-built agent-computer interface (ACI) greatly enhances the ability of an agent to create and edit code files, navigate entire repositories and execute programs. On SWE-bench, SWE-agent is able to solve 12.5% of issues, compared to the previous best of 3.8% achieved with retrieval-augmented generation (RAG). We explore how ACI design impacts an agent's behavior and performance, and provide insights on effective design.

[Arxiv](https://arxiv.org/abs/2405.15793)