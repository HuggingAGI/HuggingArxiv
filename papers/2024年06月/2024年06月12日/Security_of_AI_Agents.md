# AI智能体的安全保障

发布时间：2024年06月12日

`Agent

这篇论文主要关注的是AI代理（Agent）的安全性问题，特别是在其工作流程中存在的潜在安全漏洞。论文详细分析了这些漏洞的成因和可能导致的严重后果，并提出了一系列防御措施来增强AI代理的安全性和可靠性。因此，这篇论文应归类于Agent分类，因为它专注于AI代理的设计、安全性和改进，而不是直接涉及大型语言模型（LLM）的理论研究或应用开发。` `人工智能` `系统安全`

> Security of AI Agents

# 摘要

> 大型语言模型的进步将AI代理的研究与开发推向新高度。这些智能助手能够利用工具，在特定环境中执行命令，代表用户完成任务。然而，在深入分析典型AI代理的工作流程后，我们对其安全性产生了担忧。这些潜在的安全漏洞并未在构建代理的框架中得到解决，也未在提升代理性能的研究中被重视。本文从系统安全的角度深入探讨了这些漏洞，详细阐述了其成因及严重后果，并针对每一漏洞提出了精心设计的防御措施，通过实验验证了其有效性。本文不仅揭示了AI代理发展中的安全挑战，更为提升其安全性和可靠性提供了切实可行的解决方案。

> The study and development of AI agents have been boosted by large language models. AI agents can function as intelligent assistants and complete tasks on behalf of their users with access to tools and the ability to execute commands in their environments, Through studying and experiencing the workflow of typical AI agents, we have raised several concerns regarding their security. These potential vulnerabilities are not addressed by the frameworks used to build the agents, nor by research aimed at improving the agents. In this paper, we identify and describe these vulnerabilities in detail from a system security perspective, emphasizing their causes and severe effects. Furthermore, we introduce defense mechanisms corresponding to each vulnerability with meticulous design and experiments to evaluate their viability. Altogether, this paper contextualizes the security issues in the current development of AI agents and delineates methods to make AI agents safer and more reliable.

[Arxiv](https://arxiv.org/abs/2406.08689)