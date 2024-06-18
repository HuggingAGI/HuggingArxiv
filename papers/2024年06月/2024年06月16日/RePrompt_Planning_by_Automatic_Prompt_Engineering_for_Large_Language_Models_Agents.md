# RePrompt：为大型语言模型代理设计自动提示工程策略

发布时间：2024年06月16日

`Agent

这篇论文主要探讨了如何通过自动提示工程优化大型语言模型（LLMs）在特定领域内的规划能力，特别是在开发LLM代理以辅助日常生活中的各种工作时。这种方法通过分析与LLM代理交互的聊天历史，对提示中的逐步指令进行优化，从而提高代理的性能。这与Agent分类下的研究内容相符，因为其重点在于如何通过优化提示来提升LLM代理的实际应用能力。` `代码生成` `机器人控制`

> RePrompt: Planning by Automatic Prompt Engineering for Large Language Models Agents

# 摘要

> 过去一年，大型语言模型（LLMs）在非传统自然语言处理领域取得了显著成就，人们开始探索其在代码生成、旅行规划和机器人控制等更贴近实际应用的领域中的应用。结合LLMs的强大能力与外部工具，人们正在开发LLM代理，旨在辅助日常生活中的各种工作。在这些领域，对LLMs的提示显著影响了其输出内容及代理性能。因此，自动提示工程成为众多研究者和用户关注的焦点。本文提出了一种创新方法\textsc{RePrompt}，通过基于与LLM代理交互的聊天历史，对提示中的逐步指令进行“梯度下降”优化。优化后的提示使LLM能在特定领域内更好地规划。实验证明，使用更新后的提示作为初始提示，我们的方法能有效提升不同推理任务的性能。

> In this past year, large language models (LLMs) have had remarkable success in domains outside the traditional natural language processing, and people are starting to explore the usage of LLMs in more general and close to application domains like code generation, travel planning, and robot controls. Connecting these LLMs with great capacity and external tools, people are building the so-called LLM agents, which are supposed to help people do all kinds of work in everyday life. In all these domains, the prompt to the LLMs has been shown to make a big difference in what the LLM would generate and thus affect the performance of the LLM agents. Therefore, automatic prompt engineering has become an important question for many researchers and users of LLMs. In this paper, we propose a novel method, \textsc{RePrompt}, which does "gradient descent" to optimize the step-by-step instructions in the prompt of the LLM agents based on the chat history obtained from interactions with LLM agents. By optimizing the prompt, the LLM will learn how to plan in specific domains. We have used experiments in PDDL generation and travel planning to show that our method could generally improve the performance for different reasoning tasks when using the updated prompt as the initial prompt.

![RePrompt：为大型语言模型代理设计自动提示工程策略](../../../paper_images/2406.11132/reprompt_workflow.png)

[Arxiv](https://arxiv.org/abs/2406.11132)