# 通过状态转移图和大型语言模型来模拟以任务为导向的对话。

发布时间：2024年04月23日

`分类：LLM应用

这篇论文介绍了一种名为SynTOD的合成数据生成技术，用于构建全链条面向任务对话（TOD）系统。该技术通过构建状态转移图和使用大型语言模型（LLMs）生成多样化且结构化的对话流程，以实现复杂的任务执行。论文还探讨了不同基础和指令调优的LLMs在全链条TOD中的有效性，并分析了各种LLMs在TOD系统中评估响应的方式及其与人类评价的相关性。这些研究内容和成果都与LLM的应用紧密相关，因此将其归类为LLM应用。` `对话系统` `数据生成`

> Simulating Task-Oriented Dialogues with State Transition Graphs and Large Language Models

# 摘要

> 本研究介绍了 SynTOD，这是一种创新的合成数据生成技术，旨在构建能够执行复杂任务的全链条面向任务对话（TOD）系统，这些任务包括意图识别、槽位填充、会话式问答以及增强检索的响应生成，整个过程无需依赖众包或现实世界数据。通过构建状态转移图来明确 TOD 系统的目标行为，并通过随机漫步和大型语言模型（LLMs）的响应模拟，生成多样化且结构化的对话流程。实验结果表明，与简单的单一提示模拟对话相比，采用图引导的响应模拟在意图分类、槽位填充和响应相关性上实现了显著提升。此外，我们还深入探讨了不同基础和指令调优的 LLMs 在全链条 TOD 中的有效性，无论是否结合了合成对话数据。最终，我们分析了各种 LLMs 在 TOD 系统中评估响应的方式及其与人类评价的相关性。这些发现为快速开发和评估特定领域的 TOD 系统提供了新思路。为了促进研究，我们公开了相关数据集、模型和代码。

> This paper explores SynTOD, a new synthetic data generation approach for developing end-to-end Task-Oriented Dialogue (TOD) Systems capable of handling complex tasks such as intent classification, slot filling, conversational question-answering, and retrieval-augmented response generation, without relying on crowdsourcing or real-world data. SynTOD utilizes a state transition graph to define the desired behavior of a TOD system and generates diverse, structured conversations through random walks and response simulation using large language models (LLMs). In our experiments, using graph-guided response simulations leads to significant improvements in intent classification, slot filling and response relevance compared to naive single-prompt simulated conversations. We also investigate the end-to-end TOD effectiveness of different base and instruction-tuned LLMs, with and without the constructed synthetic conversations. Finally, we explore how various LLMs can evaluate responses in a TOD system and how well they are correlated with human judgments. Our findings pave the path towards quick development and evaluation of domain-specific TOD systems. We release our datasets, models, and code for research purposes.

[Arxiv](https://arxiv.org/abs/2404.14772)