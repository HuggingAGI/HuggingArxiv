# 利用大型语言模型自动识别小组讨论中的关键里程碑

发布时间：2024年06月16日

`Agent

这篇论文主要关注的是大型语言模型GPT在处理小组口头交流任务录音中的应用，特别是在追踪小组拼图任务中的里程碑完成情况。论文通过实验探讨了GPT如何通过迭代地处理转录文本来提高性能，并分析了不同上下文窗口大小对GPT响应质量和随机性的影响。这表明论文的重点在于探讨和应用GPT作为一个智能代理（Agent）在特定任务中的表现，因此将其归类为Agent。` `语音识别`

> Large Language Models for Automatic Milestone Detection in Group Discussions

# 摘要

> 大型语言模型GPT在处理书面文本的自然语言理解任务上取得了显著成功。然而，本文聚焦于其在小组口头交流任务录音中的表现，这类录音中的话语往往不完整或不规范。为此，我们设计了一项新的小组拼图任务实验，该任务包含多个可任意顺序达成的里程碑。我们探讨了如何通过处理转录文本来追踪里程碑的完成情况，包括完成时间及责任人。实验结果显示，通过迭代地向GPT提供转录片段，其性能超越了依赖文本嵌入的语义相似性搜索方法。此外，我们还分析了在不同上下文窗口大小下，GPT响应的质量和随机性。

> Large language models like GPT have proven widely successful on natural language understanding tasks based on written text documents. In this paper, we investigate an LLM's performance on recordings of a group oral communication task in which utterances are often truncated or not well-formed. We propose a new group task experiment involving a puzzle with several milestones that can be achieved in any order. We investigate methods for processing transcripts to detect if, when, and by whom a milestone has been completed. We demonstrate that iteratively prompting GPT with transcription chunks outperforms semantic similarity search methods using text embeddings, and further discuss the quality and randomness of GPT responses under different context window sizes.

[Arxiv](https://arxiv.org/abs/2406.10842)