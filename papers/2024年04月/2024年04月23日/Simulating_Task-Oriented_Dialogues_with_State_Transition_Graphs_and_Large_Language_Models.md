# 通过状态转移图结合大型语言模型，我们能够模拟出面向特定任务的对话流程。

发布时间：2024年04月23日

`分类：LLM应用` `对话系统` `数据生成`

> Simulating Task-Oriented Dialogues with State Transition Graphs and Large Language Models

# 摘要

> 本研究介绍了 SynTOD，这是一种创新的合成数据生成技术，旨在构建能够执行复杂任务（如意图识别、字段填充、会话式问答和检索增强型回应生成）的全链条面向任务对话（TOD）系统，且无需依赖众包或现实世界数据。该方法通过状态转移图明确 TOD 系统的目标行为，并通过随机漫步及大型语言模型（LLMs）辅助的响应模拟，产生多样化且结构化的对话。实验结果显示，相较于传统的单一提示模拟对话，采用图引导的响应模拟在意图分类、字段填充和回应相关性上实现了显著提升。此外，我们还评估了不同基础型和指令调优型 LLMs 在 TOD 系统中的表现，探讨了有无合成对话数据集时的差异。最终，我们分析了多种 LLMs 在 TOD 系统中评估回应的能力及其与人类评价的相关性。这些发现为快速构建和评估特定领域的 TOD 系统提供了新思路。为了促进研究，我们公开了相关数据集、模型和代码。

> This paper explores SynTOD, a new synthetic data generation approach for developing end-to-end Task-Oriented Dialogue (TOD) Systems capable of handling complex tasks such as intent classification, slot filling, conversational question-answering, and retrieval-augmented response generation, without relying on crowdsourcing or real-world data. SynTOD utilizes a state transition graph to define the desired behavior of a TOD system and generates diverse, structured conversations through random walks and response simulation using large language models (LLMs). In our experiments, using graph-guided response simulations leads to significant improvements in intent classification, slot filling and response relevance compared to naive single-prompt simulated conversations. We also investigate the end-to-end TOD effectiveness of different base and instruction-tuned LLMs, with and without the constructed synthetic conversations. Finally, we explore how various LLMs can evaluate responses in a TOD system and how well they are correlated with human judgments. Our findings pave the path towards quick development and evaluation of domain-specific TOD systems. We release our datasets, models, and code for research purposes.

[Arxiv](https://arxiv.org/abs/2404.14772)