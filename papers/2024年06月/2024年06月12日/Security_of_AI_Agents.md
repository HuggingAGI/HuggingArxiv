# AI智能体的安全保障

发布时间：2024年06月12日

`Agent

这篇论文主要关注的是AI代理（Agent）的安全性问题，包括其工作流程中的潜在安全漏洞以及相应的防御机制。虽然AI代理的开发和应用可能涉及到大型语言模型（LLM），但论文的核心内容是关于AI代理的安全性分析和防御策略，而不是LLM的理论研究或应用。因此，将其归类为Agent是最合适的。` `人工智能安全` `系统安全`

> Security of AI Agents

# 摘要

> 大型语言模型的进步，促进了AI代理的研究与开发。这些AI代理如同智能助手，能代表用户执行任务，运用工具，并在其环境中下达指令。然而，在深入探究这些AI代理的工作流程后，我们对其安全性产生了担忧。这些潜在的安全漏洞，既未在构建代理的框架中得到解决，也未在提升代理性能的研究中被关注。本文从系统安全的角度，详细剖析了这些漏洞，揭示了它们的成因及其严重后果。同时，我们精心设计并实验了针对每个漏洞的防御机制，以验证其有效性。本文不仅揭示了AI代理当前开发中的安全挑战，更为构建更安全、更可靠的AI代理提供了策略。

> The study and development of AI agents have been boosted by large language models. AI agents can function as intelligent assistants and complete tasks on behalf of their users with access to tools and the ability to execute commands in their environments, Through studying and experiencing the workflow of typical AI agents, we have raised several concerns regarding their security. These potential vulnerabilities are not addressed by the frameworks used to build the agents, nor by research aimed at improving the agents. In this paper, we identify and describe these vulnerabilities in detail from a system security perspective, emphasizing their causes and severe effects. Furthermore, we introduce defense mechanisms corresponding to each vulnerability with meticulous design and experiments to evaluate their viability. Altogether, this paper contextualizes the security issues in the current development of AI agents and delineates methods to make AI agents safer and more reliable.

[Arxiv](https://arxiv.org/abs/2406.08689)