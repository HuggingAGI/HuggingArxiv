# 利用大型语言模型自动捕捉小组讨论中的关键里程碑

发布时间：2024年06月16日

`Agent

这篇论文探讨了大型语言模型（如GPT）在处理群体口头交流录音任务中的应用，特别是在识别任务里程碑的完成时间和责任人方面的表现。研究通过实验设计，使用迭代提供转录片段的方式来测试模型的性能，并分析了不同上下文窗口大小对模型响应质量和随机性的影响。这种应用场景涉及到模型的实时交互和决策，更符合Agent的定义，即一个能够感知环境并采取行动以达到目标的系统。因此，将这篇论文分类为Agent。` `语音识别` `群体交流分析`

> Large Language Models for Automatic Milestone Detection in Group Discussions

# 摘要

> GPT等大型语言模型在书面文本的自然语言理解任务上取得了显著成功。本文探讨了LLM在处理群体口头交流录音任务中的表现，这些录音中的话语往往不完整或语法不规范。我们设计了一项涉及谜题的群体任务实验，该谜题的多个里程碑可任意顺序达成。我们研究了如何通过处理转录文本来识别里程碑的完成时间及责任人。实验表明，通过迭代向GPT提供转录片段的方式，其性能超越了依赖文本嵌入的语义相似性搜索。此外，我们还分析了在不同上下文窗口大小下，GPT响应的质量和随机性。

> Large language models like GPT have proven widely successful on natural language understanding tasks based on written text documents. In this paper, we investigate an LLM's performance on recordings of a group oral communication task in which utterances are often truncated or not well-formed. We propose a new group task experiment involving a puzzle with several milestones that can be achieved in any order. We investigate methods for processing transcripts to detect if, when, and by whom a milestone has been completed. We demonstrate that iteratively prompting GPT with transcription chunks outperforms semantic similarity search methods using text embeddings, and further discuss the quality and randomness of GPT responses under different context window sizes.

[Arxiv](https://arxiv.org/abs/2406.10842)