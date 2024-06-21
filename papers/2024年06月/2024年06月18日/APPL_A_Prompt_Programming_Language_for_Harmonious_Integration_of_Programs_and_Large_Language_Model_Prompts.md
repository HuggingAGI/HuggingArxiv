# APPL：一种促进程序与大型语言模型提示无缝融合的提示编程语言

发布时间：2024年06月18日

`Agent

理由：这篇论文介绍了一种新型提示编程语言APPL，它连接了计算机程序与大型语言模型（LLMs），并特别强调了其在多代理聊天和代理工具使用（如ReAct）中的应用。这些特性表明APPL主要关注于构建和优化代理（Agent）系统，特别是在处理复杂任务和提高工作流程效率方面。因此，将其归类为Agent是合适的。` `人工智能` `编程语言`

> APPL: A Prompt Programming Language for Harmonious Integration of Programs and Large Language Model Prompts

# 摘要

> 随着任务复杂度的提升，大型语言模型（LLMs）在处理多样化任务时，其工作流程可能变得复杂且难以维护。为此，我们开发了APPL，一种新型提示编程语言，它巧妙地连接了计算机程序与LLMs，使得提示与Python函数间的融合变得无缝。APPL不仅拥有直观且符合Python习惯的语法，还提供了一个高效的并行运行时环境，支持异步操作，并配备了故障诊断和重放功能，无需额外成本。通过思维链与自我一致性（CoT-SC）、ReAct工具使用代理和多代理聊天这三个典型案例，我们展示了APPL程序的直观性、简洁性和高效性。实验结果进一步证实，APPL能有效并行化LLM的独立调用，其加速效果几乎达到了预期。

> Large Language Models (LLMs) have become increasingly capable of handling diverse tasks with the aid of well-crafted prompts and integration of external tools, but as task complexity rises, the workflow involving LLMs can be complicated and thus challenging to implement and maintain. To address this challenge, we propose APPL, A Prompt Programming Language that acts as a bridge between computer programs and LLMs, allowing seamless embedding of prompts into Python functions, and vice versa. APPL provides an intuitive and Python-native syntax, an efficient parallelized runtime with asynchronous semantics, and a tracing module supporting effective failure diagnosis and replaying without extra costs. We demonstrate that APPL programs are intuitive, concise, and efficient through three representative scenarios: Chain-of-Thought with self-consistency (CoT-SC), ReAct tool use agent, and multi-agent chat. Experiments on three parallelizable workflows further show that APPL can effectively parallelize independent LLM calls, with a significant speedup ratio that almost matches the estimation.

[Arxiv](https://arxiv.org/abs/2406.13161)