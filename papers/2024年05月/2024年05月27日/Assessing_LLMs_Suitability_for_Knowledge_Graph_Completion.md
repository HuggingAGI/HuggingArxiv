# 探究大型语言模型在知识图谱补全任务中的适用性

发布时间：2024年05月27日

`Agent

理由：这篇论文主要探讨了大型语言模型（LLMs）在零样本或少样本学习模式下处理知识图谱补全任务的能力，特别是在面向任务的对话系统中的应用。论文通过实验评估了特定LLMs在知识图谱补全任务中的表现，并强调了提示设计的重要性。这表明论文关注的是如何利用LLMs作为智能代理（Agent）来执行特定任务，即在对话系统中进行知识图谱补全，因此属于Agent分类。` `对话系统` `知识图谱`

> Assessing LLMs Suitability for Knowledge Graph Completion

# 摘要

> 最新研究表明，大型语言模型（LLMs）在零样本或少样本学习模式下，已能有效处理知识图谱补全等任务。但这些模型有时会生成不切实际的答案，或以不确定的方式输出结果，导致推理错误，尽管它们满足了用户需求。为了探索知识图谱任务的潜力与挑战，我们选取了Mixtral-8x7B-Instruct-v0.1和gpt-3.5-turbo-0125两款特色LLMs，在面向任务的对话系统中，针对静态知识图谱进行知识图谱补全实验。实验采用TELeR分类法构建的提示，在零样本和一样本情境下进行。评估结果显示，若提示设计得当，包含充足信息和相关示例，LLMs完全有能力应对这类任务。

> Recent work shown the capability of Large Language Models (LLMs) to solve tasks related to Knowledge Graphs, such as Knowledge Graph Completion, even in Zero- or Few-Shot paradigms. However, they are known to hallucinate answers, or output results in a non-deterministic manner, thus leading to wrongly reasoned responses, even if they satisfy the user's demands. To highlight opportunities and challenges in knowledge graphs-related tasks, we experiment with two distinguished LLMs, namely Mixtral-8x7B-Instruct-v0.1, and gpt-3.5-turbo-0125, on Knowledge Graph Completion for static knowledge graphs, using prompts constructed following the TELeR taxonomy, in Zero- and One-Shot contexts, on a Task-Oriented Dialogue system use case. When evaluated using both strict and flexible metrics measurement manners, our results show that LLMs could be fit for such a task if prompts encapsulate sufficient information and relevant examples.

![探究大型语言模型在知识图谱补全任务中的适用性](../../../paper_images/2405.17249/ontology.png)

[Arxiv](https://arxiv.org/abs/2405.17249)