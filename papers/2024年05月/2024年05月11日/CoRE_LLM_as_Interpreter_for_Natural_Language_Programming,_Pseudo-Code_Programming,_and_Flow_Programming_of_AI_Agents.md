# CoRE：大型语言模型——AI代理自然语言编程、伪代码编程与流程编程的智慧之钥

发布时间：2024年05月11日

`Agent

这篇论文介绍了一个创新的系统，即代码表示和执行（CoRE）系统，它利用大型语言模型（LLMs）作为解释器来处理自然语言指令，并构建语言代理。这个系统不仅涉及LLM的应用，还涉及创建一个能够理解和执行自然语言指令的Agent。因此，它更符合Agent分类，而不是RAG（检索增强生成）或LLM理论。虽然它确实涉及LLM的应用，但重点在于创建一个能够执行任务的Agent，而不仅仅是应用LLM技术。` `编程语言` `人工智能辅助开发`

> CoRE: LLM as Interpreter for Natural Language Programming, Pseudo-Code Programming, and Flow Programming of AI Agents

# 摘要

> 编程语言自诞生以来，便朝着提高可读性和降低门槛的方向发展，自然语言编程因此成为一种充满潜力的编程方式，它赋予了编程极大的灵活性和易用性，并推动了编程的普及。然而，自然语言的模糊、歧义和冗长特性给开发能够准确理解并执行自然语言指令的解释器带来了挑战。幸运的是，大型语言模型（LLMs）的最新进展在解释复杂自然语言方面表现出色。基于此，我们开发了创新的代码表示和执行（CoRE）系统，利用LLM作为解释器来处理自然语言指令。该系统将自然语言、伪代码和流程编程统一起来，构建语言代理，LLM则作为解释器执行这些代理程序。本文首先定义了自然语言指令的逻辑结构编程语法，并在执行过程中引入外部记忆以减少冗余。此外，我们还赋予了解释器调用外部工具的能力，以弥补LLM在特定领域或实时信息访问方面的不足。这项工作已在https://github.com/agiresearch/CoRE 开源。

> Since their inception, programming languages have trended towards greater readability and lower barriers for programmers. Following this trend, natural language can be a promising type of programming language that provides great flexibility and usability and helps towards the democracy of programming. However, the inherent vagueness, ambiguity, and verbosity of natural language pose significant challenges in developing an interpreter that can accurately understand the programming logic and execute instructions written in natural language. Fortunately, recent advancements in Large Language Models (LLMs) have demonstrated remarkable proficiency in interpreting complex natural language. Inspired by this, we develop a novel system for Code Representation and Execution (CoRE), which employs LLM as interpreter to interpret and execute natural language instructions. The proposed system unifies natural language programming, pseudo-code programming, and flow programming under the same representation for constructing language agents, while LLM serves as the interpreter to interpret and execute the agent programs. In this paper, we begin with defining the programming syntax that structures natural language instructions logically. During the execution, we incorporate external memory to minimize redundancy. Furthermore, we equip the designed interpreter with the capability to invoke external tools, compensating for the limitations of LLM in specialized domains or when accessing real-time information. This work is open-source at https://github.com/agiresearch/CoRE.

[Arxiv](https://arxiv.org/abs/2405.06907)