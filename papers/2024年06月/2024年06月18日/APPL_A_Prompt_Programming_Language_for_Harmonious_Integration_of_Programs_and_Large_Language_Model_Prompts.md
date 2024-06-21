# APPL：一种促进程序与大型语言模型提示无缝融合的提示编程语言

发布时间：2024年06月18日

`Agent

理由：这篇论文介绍了一种新型提示编程语言APPL，它能够将计算机程序与大型语言模型（LLMs）结合起来，特别强调了通过思维链与自我一致性（CoT-SC）、ReAct工具使用代理及多代理聊天等应用场景。这些应用场景涉及到代理（Agent）的概念，即通过编程语言来控制和操作LLMs以完成特定任务，因此将其归类为Agent。虽然论文中也涉及到了LLM的应用，但主要焦点在于通过APPL语言来实现对LLMs的控制和优化，这与LLM应用分类中的直接应用LLMs解决特定问题有所不同。` `人工智能` `编程语言`

> APPL: A Prompt Programming Language for Harmonious Integration of Programs and Large Language Model Prompts

# 摘要

> 随着任务复杂度的提升，大型语言模型（LLMs）在处理多样化任务时，其工作流程变得复杂且难以维护。为此，我们开发了APPL，一种新型提示编程语言，它巧妙地连接了计算机程序与LLMs，使得提示能无缝融入Python函数，反之亦然。APPL不仅拥有直观且符合Python习惯的语法，还提供了一个高效的并行运行时环境，支持异步操作，并配备了故障诊断和无额外成本重放的跟踪模块。通过思维链与自我一致性（CoT-SC）、ReAct工具使用代理及多代理聊天等三个典型应用场景的展示，我们证明了APPL程序的直观性、简洁性和高效性。实验结果还显示，APPL在并行化LLM调用方面表现出色，其加速效果几乎达到了理论预期。

> Large Language Models (LLMs) have become increasingly capable of handling diverse tasks with the aid of well-crafted prompts and integration of external tools, but as task complexity rises, the workflow involving LLMs can be complicated and thus challenging to implement and maintain. To address this challenge, we propose APPL, A Prompt Programming Language that acts as a bridge between computer programs and LLMs, allowing seamless embedding of prompts into Python functions, and vice versa. APPL provides an intuitive and Python-native syntax, an efficient parallelized runtime with asynchronous semantics, and a tracing module supporting effective failure diagnosis and replaying without extra costs. We demonstrate that APPL programs are intuitive, concise, and efficient through three representative scenarios: Chain-of-Thought with self-consistency (CoT-SC), ReAct tool use agent, and multi-agent chat. Experiments on three parallelizable workflows further show that APPL can effectively parallelize independent LLM calls, with a significant speedup ratio that almost matches the estimation.

[Arxiv](https://arxiv.org/abs/2406.13161)