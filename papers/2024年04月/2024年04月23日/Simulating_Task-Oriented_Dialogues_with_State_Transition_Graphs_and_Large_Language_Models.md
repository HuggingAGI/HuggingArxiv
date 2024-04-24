# 通过状态转移图和先进的大型语言模型，我们能够模拟出面向特定任务的对话场景。

发布时间：2024年04月23日

`分类：LLM应用` `对话系统` `数据生成`

> Simulating Task-Oriented Dialogues with State Transition Graphs and Large Language Models

# 摘要

> 本文介绍了 SynTOD，这是一种创新的合成数据生成技术，旨在培育能够应对复杂任务（如意图识别、信息填充、对话式问答和检索增强型回应生成）的全链路面向任务对话（TOD）系统，且无需依赖于众包或现实世界数据。该方法通过构建状态转移图来明确 TOD 系统的目标行为，并借助大型语言模型（LLMs）进行随机游走和响应模拟，以生成多样化且结构化的对话。实验结果显示，相较于传统的单一提示模拟对话，采用图引导的响应模拟在意图识别、信息填充和回应相关性方面取得了显著提升。此外，本研究还评估了不同基础型和指令调优型 LLMs 在全链路 TOD 系统中的应用效果，无论是否整合了合成对话。研究进一步探讨了各类 LLMs 在 TOD 系统中评估回应的方式及其与人类判断的一致性。这些发现为快速构建和评估特定领域的 TOD 系统提供了新思路。为了促进研究，我们公开了相关数据集、模型和代码。

> This paper explores SynTOD, a new synthetic data generation approach for developing end-to-end Task-Oriented Dialogue (TOD) Systems capable of handling complex tasks such as intent classification, slot filling, conversational question-answering, and retrieval-augmented response generation, without relying on crowdsourcing or real-world data. SynTOD utilizes a state transition graph to define the desired behavior of a TOD system and generates diverse, structured conversations through random walks and response simulation using large language models (LLMs). In our experiments, using graph-guided response simulations leads to significant improvements in intent classification, slot filling and response relevance compared to naive single-prompt simulated conversations. We also investigate the end-to-end TOD effectiveness of different base and instruction-tuned LLMs, with and without the constructed synthetic conversations. Finally, we explore how various LLMs can evaluate responses in a TOD system and how well they are correlated with human judgments. Our findings pave the path towards quick development and evaluation of domain-specific TOD systems. We release our datasets, models, and code for research purposes.

[Arxiv](https://arxiv.org/abs/2404.14772)