# AgentCoord：探索基于大型语言模型的多智能体协作的视觉协调策略

发布时间：2024年04月18日

`Agent` `人工智能` `自动化`

> AgentCoord: Visually Exploring Coordination Strategy for LLM-based Multi-Agent Collaboration

# 摘要

> 近期，利用大型语言模型（LLM）驱动的多智能体协作来自动化解决问题的潜力，受到了学术界和产业界的广泛关注。尽管利用自然语言协调多个智能体的操作为普及智能体技术开辟了新途径，但在现有框架下设计有效的协调策略却充满挑战。这一难题主要源于自然语言在明确指定协作流程时的模糊性，以及在探索过程中从大量文本内容中抽取关键信息（如智能体间关系、任务依赖、结果对应）所需的巨大认知负荷。为此，本研究提出了一个可视化的探索框架，旨在简化多智能体协作中的协调策略设计。我们首先为基于LLM的多智能体协调策略创建了一个结构化表示，以减少自然语言的歧义。在此基础上，我们开发了一种三阶段生成方法，该方法利用LLM将用户的总体目标转换为可执行的初始协调策略。用户可以在生成过程的任何阶段进行干预，通过LLM和一系列交互来探索不同的策略。一旦找到满意的策略，用户即可启动协作并查看其视觉增强的执行结果。我们构建了一个名为AgentCoord的原型互动系统，并通过正式的用户研究验证了我们方法的可行性和有效性。

> The potential of automatic task-solving through Large Language Model (LLM)-based multi-agent collaboration has recently garnered widespread attention from both the research community and industry. While utilizing natural language to coordinate multiple agents presents a promising avenue for democratizing agent technology for general users, designing coordination strategies remains challenging with existing coordination frameworks. This difficulty stems from the inherent ambiguity of natural language for specifying the collaboration process and the significant cognitive effort required to extract crucial information (e.g. agent relationship, task dependency, result correspondence) from a vast amount of text-form content during exploration. In this work, we present a visual exploration framework to facilitate the design of coordination strategies in multi-agent collaboration. We first establish a structured representation for LLM-based multi-agent coordination strategy to regularize the ambiguity of natural language. Based on this structure, we devise a three-stage generation method that leverages LLMs to convert a user's general goal into an executable initial coordination strategy. Users can further intervene at any stage of the generation process, utilizing LLMs and a set of interactions to explore alternative strategies. Whenever a satisfactory strategy is identified, users can commence the collaboration and examine the visually enhanced execution result. We develop AgentCoord, a prototype interactive system, and conduct a formal user study to demonstrate the feasibility and effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2404.11943)