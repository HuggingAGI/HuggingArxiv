# KwaiAgents：结合大型语言模型的全能信息搜寻代理系统

发布时间：2024年01月10日

`Agent` `信息检索` `人工智能`

> KwaiAgents: Generalized Information-seeking Agent System with Large Language Models

# 摘要

> 人类因好奇心的驱使，不懈地探索和理解周遭世界，发明了众多工具以满足这份求知欲。尽管人脑无法处理和记忆海量信息，人类却在批判性思维、规划、反思和利用工具与世界互动方面表现出色，有效地寻找解答。大型语言模型（LLMs）的进展预示着机器可能也能展现出类似的人类特质，即便参数受限，也能发挥强大功能。本文介绍了KwaiAgents，这是一个基于LLMs构建的通用信息搜寻代理系统。该系统中的代理利用LLMs作为认知核心，不仅能够理解用户查询和行为准则，还能查阅外部文档。代理能够更新和检索内部信息，运用时间感知的搜索浏览工具规划和执行动作，最终提供全面回答。我们还探讨了该系统在搭载低于GPT-4水平的LLMs时的表现，并提出了元代理调整（MAT）框架，旨在让开源的7B或13B模型在众多代理系统中也能表现出色。通过基准测试和人类评估，我们系统地验证了这些能力。广泛的实验显示，我们的代理系统相较于其他自主代理具有优势，并突显了我们精细调整后的LLMs在通用代理能力上的提升。

> Driven by curiosity, humans have continually sought to explore and understand the world around them, leading to the invention of various tools to satiate this inquisitiveness. Despite not having the capacity to process and memorize vast amounts of information in their brains, humans excel in critical thinking, planning, reflection, and harnessing available tools to interact with and interpret the world, enabling them to find answers efficiently. The recent advancements in large language models (LLMs) suggest that machines might also possess the aforementioned human-like capabilities, allowing them to exhibit powerful abilities even with a constrained parameter count. In this paper, we introduce KwaiAgents, a generalized information-seeking agent system based on LLMs. Within KwaiAgents, we propose an agent system that employs LLMs as its cognitive core, which is capable of understanding a user's query, behavior guidelines, and referencing external documents. The agent can also update and retrieve information from its internal memory, plan and execute actions using a time-aware search-browse toolkit, and ultimately provide a comprehensive response. We further investigate the system's performance when powered by LLMs less advanced than GPT-4, and introduce the Meta-Agent Tuning (MAT) framework, designed to ensure even an open-sourced 7B or 13B model performs well among many agent systems. We exploit both benchmark and human evaluations to systematically validate these capabilities. Extensive experiments show the superiority of our agent system compared to other autonomous agents and highlight the enhanced generalized agent-abilities of our fine-tuned LLMs.

[Arxiv](https://arxiv.org/abs/2312.04889)