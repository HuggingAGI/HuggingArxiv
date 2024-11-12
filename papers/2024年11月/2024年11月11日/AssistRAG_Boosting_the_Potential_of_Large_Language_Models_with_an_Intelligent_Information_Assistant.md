# AssistRAG：通过智能信息助手提升大型语言模型的潜力

发布时间：2024年11月11日

`RAG` `信息检索`

> AssistRAG: Boosting the Potential of Large Language Models with an Intelligent Information Assistant

# 摘要

> 大型语言模型（LLMs）的出现极大地推进了自然语言处理，但这些模型经常生成事实上不正确的信息，被称为“幻觉”。像“检索-读取”框架这样的初始检索增强生成（RAG）方法对于复杂的推理任务是不够的。随后的基于提示的 RAG 策略和有监督微调（SFT）方法提高了性能，但需要频繁的重新训练，并有可能改变基础的 LLM 能力。为了应对这些挑战，我们提出了基于助手的检索增强生成（AssistRAG），在 LLMs 中集成了一个智能信息助手。这个助手通过工具使用、动作执行、记忆构建和计划规范来管理内存和知识。使用两阶段训练方法，课程助手学习和强化偏好优化。AssistRAG 增强了信息检索和决策能力。实验表明，AssistRAG 显著优于基准，特别是为不太先进的 LLMs 提供了卓越的推理能力和准确的响应。

> The emergence of Large Language Models (LLMs) has significantly advanced natural language processing, but these models often generate factually incorrect information, known as "hallucination". Initial retrieval-augmented generation (RAG) methods like the "Retrieve-Read" framework was inadequate for complex reasoning tasks. Subsequent prompt-based RAG strategies and Supervised Fine-Tuning (SFT) methods improved performance but required frequent retraining and risked altering foundational LLM capabilities. To cope with these challenges, we propose Assistant-based Retrieval-Augmented Generation (AssistRAG), integrating an intelligent information assistant within LLMs. This assistant manages memory and knowledge through tool usage, action execution, memory building, and plan specification. Using a two-phase training approach, Curriculum Assistant Learning and Reinforced Preference Optimization. AssistRAG enhances information retrieval and decision-making. Experiments show AssistRAG significantly outperforms benchmarks, especially benefiting less advanced LLMs, by providing superior reasoning capabilities and accurate responses.

[Arxiv](https://arxiv.org/abs/2411.06805)