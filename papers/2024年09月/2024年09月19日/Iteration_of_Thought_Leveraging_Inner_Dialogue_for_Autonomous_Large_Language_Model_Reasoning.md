# 思维迭代：通过内部对话实现自主大型语言模型推理

发布时间：2024年09月19日

`LLM应用` `人工智能`

> Iteration of Thought: Leveraging Inner Dialogue for Autonomous Large Language Model Reasoning

# 摘要

> 迭代的人类参与是利用大型语言模型 (LLM) 高级语言处理能力的常见且有效手段。通过对话中结构良好的提示，人类用户能有效引导 LLM 生成更具深度和准确性的回答。基于此，我们提出“思想迭代”(IoT) 框架，通过生成引发思考的提示来增强 LLM 响应。与静态或半静态方法（如思维链 (CoT) 或思维树 (ToT)）不同，IoT 根据动态上下文调整推理路径，避免生成最终被丢弃的探索性思维。IoT 框架包括：(1) 生成指导性、上下文特定提示的内部对话代理 (IDA)；(2) 处理提示以改进响应的 LLM 代理 (LLMA)；(3) 实现两者对话的迭代提示循环。我们提出两种变体：自主思想迭代 (AIoT) 和引导思想迭代 (GIoT)。通过在多种数据集上的测试，IoT 展示了相对于 CoT 的显著改进，实现了更具适应性和效率的推理系统，减少了人类干预。

> Iterative human engagement is a common and effective means of leveraging the advanced language processing power of large language models (LLMs). Using well-structured prompts in a conversational manner, human users can effectively influence an LLM to develop more thoughtful and accurate responses. Motivated by this insight, we propose the Iteration of Thought (IoT) framework for enhancing LLM responses by generating "thought"-provoking prompts vis a vis an input query and the current iteration of an LLM's response. Unlike static or semi-static approaches, e.g. Chain of Thought (CoT) or Tree of Thoughts (ToT), IoT adapts its reasoning path dynamically, based on evolving context, and without generating alternate explorative thoughts which are ultimately discarded. The three components of the IoT framework are (1) an Inner Dialogue Agent (IDA) responsible for generating instructive, context-specific prompts; (2) an LLM Agent (LLMA) that processes these prompts to refine its responses; and (3) an iterative prompting loop that implements a conversation between the former two components. We introduce two variants of our framework: Autonomous Iteration of Thought (AIoT), where an LLM decides when to stop iterating, and Guided Iteration of Thought (GIoT), which always forces a fixed number iterations. We investigate the performance of IoT across various datasets, spanning complex reasoning tasks from the GPQA dataset, explorative problem-solving in Game of 24, puzzle solving in Mini Crosswords, and multi-hop question answering from the HotpotQA dataset. Our results show that IoT represents a viable paradigm for autonomous response refinement in LLMs, showcasing significant improvements over CoT and thereby enabling more adaptive and efficient reasoning systems that minimize human intervention.

[Arxiv](https://arxiv.org/abs/2409.12618)