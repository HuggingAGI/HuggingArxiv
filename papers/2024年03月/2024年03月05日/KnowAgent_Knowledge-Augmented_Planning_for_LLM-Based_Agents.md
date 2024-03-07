# [KnowAgent是一种为基于大型语言模型（LLM）的智能体设计的知识增强规划方案，旨在通过融合知识与LLM能力来提升其决策与规划效能。](https://arxiv.org/abs/2403.03101)

> KnowAgent: Knowledge-Augmented Planning for LLM-Based Agents

发布时间：2024年03月05日

> 尽管LLMs在应对复杂推理任务上表现出强大的实力，但在面对需要生成可执行动作与环境互动的高级挑战时却显得力不从心，根源在于语言模型中内嵌的动作知识不足，难以有效引导任务解决过程中的规划走向，引发“规划臆想”现象。为此，我们提出了一项名为KnowAgent的新颖方案，通过融入显式动作知识来增强LLMs的规划能力。KnowAgent巧妙运用动作知识库和智能自我学习策略，在规划阶段限制动作路径，促进更加合理的轨迹合成，由此提升了语言模型在规划任务上的表现。实验证明，无论是在HotpotQA还是ALFWorld上，使用不同基础模型构建的KnowAgent均可达到甚至超越现有基准的效果。深入分析揭示了KnowAgent在减少规划臆想方面的显著优势。相关代码已公开在GitHub平台，地址为https://github.com/zjunlp/KnowAgent。

> Large Language Models (LLMs) have demonstrated great potential in complex reasoning tasks, yet they fall short when tackling more sophisticated challenges, especially when interacting with environments through generating executable actions. This inadequacy primarily stems from the lack of built-in action knowledge in language agents, which fails to effectively guide the planning trajectories during task solving and results in planning hallucination. To address this issue, we introduce KnowAgent, a novel approach designed to enhance the planning capabilities of LLMs by incorporating explicit action knowledge. Specifically, KnowAgent employs an action knowledge base and a knowledgeable self-learning strategy to constrain the action path during planning, enabling more reasonable trajectory synthesis, and thereby enhancing the planning performance of language agents. Experimental results on HotpotQA and ALFWorld based on various backbone models demonstrate that KnowAgent can achieve comparable or superior performance to existing baselines. Further analysis indicates the effectiveness of KnowAgent in terms of planning hallucinations mitigation. Code is available in https://github.com/zjunlp/KnowAgent.

`Agent`