# ChatDev：软件开发的沟通专家

发布时间：2024年06月05日

`Agent

这篇论文介绍了一个名为 ChatDev 的框架，该框架利用大型语言模型（LLMs）驱动的专业代理，通过聊天链指导交流内容与方式，实现统一语言沟通，有效推进软件开发的各个阶段。这个框架强调了语言在多代理协作中的桥梁作用，并为LLM代理间的自主任务解决提供了一个统一的路径。因此，这篇论文属于Agent分类，因为它主要关注的是如何使用LLM驱动的代理来优化软件开发过程。` `软件开发` `人工智能`

> ChatDev: Communicative Agents for Software Development

# 摘要

> 软件开发复杂，需多技能成员协作。深度学习虽优化了瀑布模型的设计、编码和测试阶段，但各阶段模型设计独特，导致技术不统一，开发效率低下。本文推出的 ChatDev 框架，利用大型语言模型（LLMs）驱动的专业代理，通过聊天链指导交流内容与方式，实现统一语言沟通，有效推进开发各阶段。自然语言优化系统设计，编程语言助力调试。此模式凸显语言在多代理协作中的桥梁作用，为LLM代理间的自主任务解决提供统一路径。相关代码和数据已公开于 https://github.com/OpenBMB/ChatDev。

> Software development is a complex task that necessitates cooperation among multiple members with diverse skills. Numerous studies used deep learning to improve specific phases in a waterfall model, such as design, coding, and testing. However, the deep learning model in each phase requires unique designs, leading to technical inconsistencies across various phases, which results in a fragmented and ineffective development process. In this paper, we introduce ChatDev, a chat-powered software development framework in which specialized agents driven by large language models (LLMs) are guided in what to communicate (via chat chain) and how to communicate (via communicative dehallucination). These agents actively contribute to the design, coding, and testing phases through unified language-based communication, with solutions derived from their multi-turn dialogues. We found their utilization of natural language is advantageous for system design, and communicating in programming language proves helpful in debugging. This paradigm demonstrates how linguistic communication facilitates multi-agent collaboration, establishing language as a unifying bridge for autonomous task-solving among LLM agents. The code and data are available at https://github.com/OpenBMB/ChatDev.

[Arxiv](https://arxiv.org/abs/2307.07924)