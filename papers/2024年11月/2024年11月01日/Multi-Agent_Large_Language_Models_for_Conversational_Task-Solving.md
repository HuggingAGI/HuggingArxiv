# 用于会话任务解决的多智能体大型语言模型

发布时间：2024年11月01日

`Agent` `人工智能` `多智能体系统`

> Multi-Agent Large Language Models for Conversational Task-Solving

# 摘要

> 在单个大型语言模型多年来主宰人工智能领域的时代，多智能体系统在对话任务解决中崭露头角。此前的研究虽已展现出其在推理任务和创新尝试方面的潜力，但对于其在对话范式方面的局限以及个体智能体的影响，却缺乏分析。多智能体讨论在不同复杂程度任务中的表现怎样，以及这些对话的结构如何影响进程，都尚不明确。为填补这一空缺，本工作对各种讨论范式下的多智能体系统进行了系统评估，衡量了它们在生成任务和问答任务中的优劣。除实验外，我提出了 2022 至 2024 年 20 项多智能体研究的分类法，接着介绍了在对话任务解决中部署多智能体 LLM 的框架。我证实，尽管多智能体系统在复杂推理任务中表现卓越，凭借专家角色胜过单个模型，但在基础任务上却不尽人意。具体而言，我指出了三个出现的挑战：1）虽然更长的讨论能增强推理能力，但智能体无法始终符合严格的任务要求，从而导致问题偏移，使得较短的对话对基础任务更有效。2）长时间的讨论存在对齐崩溃的风险，给这些系统带来新的安全隐患。3）我展示了通过长时间生成造成的讨论垄断，给诸如总结之类的任务带来了决策公平性的问题。此项工作揭示了多智能体交互和不同对话范式所带来的潜力与挑战，为未来研究如何提升多智能体 LLM 的效率、性能和安全性提供了思路。

> In an era where single large language models have dominated the landscape of artificial intelligence for years, multi-agent systems arise as new protagonists in conversational task-solving. While previous studies have showcased their potential in reasoning tasks and creative endeavors, an analysis of their limitations concerning the conversational paradigms and the impact of individual agents is missing. It remains unascertained how multi-agent discussions perform across tasks of varying complexity and how the structure of these conversations influences the process. To fill that gap, this work systematically evaluates multi-agent systems across various discussion paradigms, assessing their strengths and weaknesses in both generative tasks and question-answering tasks. Alongside the experiments, I propose a taxonomy of 20 multi-agent research studies from 2022 to 2024, followed by the introduction of a framework for deploying multi-agent LLMs in conversational task-solving. I demonstrate that while multi-agent systems excel in complex reasoning tasks, outperforming a single model by leveraging expert personas, they fail on basic tasks. Concretely, I identify three challenges that arise: 1) While longer discussions enhance reasoning, agents fail to maintain conformity to strict task requirements, which leads to problem drift, making shorter conversations more effective for basic tasks. 2) Prolonged discussions risk alignment collapse, raising new safety concerns for these systems. 3) I showcase discussion monopolization through long generations, posing the problem of fairness in decision-making for tasks like summarization. This work uncovers both the potential and challenges that arise with multi-agent interaction and varying conversational paradigms, providing insights into how future research could improve the efficiency, performance, and safety of multi-agent LLMs.

[Arxiv](https://arxiv.org/abs/2410.22932)