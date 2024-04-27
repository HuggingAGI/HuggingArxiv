# 通过状态转移图和大型语言模型来模拟以任务为导向的对话流程。

发布时间：2024年04月23日

`分类：RAG

这篇论文介绍了一种名为SynTOD的合成数据生成技术，用于培育能够执行复杂任务的全链条面向任务对话（TOD）系统。这项技术涉及到意图识别、槽位填充、对话式问答以及增强检索的响应生成。论文中提到了大型语言模型（LLMs）在生成多样化且结构化的对话中的作用，以及对不同基础型和指令调优型LLMs在TOD系统中的应用效果的探讨。这些内容表明，这篇论文主要关注的是利用合成数据和大型语言模型来生成和评估对话系统，因此它属于RAG（Retrieval-Augmented Generation）的范畴。` `对话系统` `数据生成`

> Simulating Task-Oriented Dialogues with State Transition Graphs and Large Language Models

# 摘要

> 本研究介绍了 SynTOD，这是一种创新的合成数据生成技术，旨在培育能够执行复杂任务的全链条面向任务对话（TOD）系统。这些任务包括意图识别、槽位填充、对话式问答以及增强检索的响应生成，且整个过程无需依赖众包或现实世界数据。SynTOD 通过状态转移图明确 TOD 系统的目标行为，并通过随机游走结合大型语言模型（LLMs）的响应模拟，创造出多样化且结构化的对话。实验结果显示，采用图引导的响应模拟方法，在意图识别、槽位填充和响应相关性方面，相较于传统的单一提示模拟对话，有显著的性能提升。此外，我们还深入探讨了不同基础型和指令调优型 LLMs 在 TOD 系统中的应用效果，无论是否结合了合成对话数据。最终，我们评估了各种 LLMs 在 TOD 系统中的响应评估能力，并分析了它们与人类评判的一致性。这些发现为快速开发和评估特定领域的 TOD 系统提供了新思路。为了促进研究，我们公开了数据集、模型和代码。

> This paper explores SynTOD, a new synthetic data generation approach for developing end-to-end Task-Oriented Dialogue (TOD) Systems capable of handling complex tasks such as intent classification, slot filling, conversational question-answering, and retrieval-augmented response generation, without relying on crowdsourcing or real-world data. SynTOD utilizes a state transition graph to define the desired behavior of a TOD system and generates diverse, structured conversations through random walks and response simulation using large language models (LLMs). In our experiments, using graph-guided response simulations leads to significant improvements in intent classification, slot filling and response relevance compared to naive single-prompt simulated conversations. We also investigate the end-to-end TOD effectiveness of different base and instruction-tuned LLMs, with and without the constructed synthetic conversations. Finally, we explore how various LLMs can evaluate responses in a TOD system and how well they are correlated with human judgments. Our findings pave the path towards quick development and evaluation of domain-specific TOD systems. We release our datasets, models, and code for research purposes.

[Arxiv](https://arxiv.org/abs/2404.14772)