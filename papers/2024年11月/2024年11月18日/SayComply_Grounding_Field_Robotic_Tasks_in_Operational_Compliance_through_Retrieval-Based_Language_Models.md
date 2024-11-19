# SayComply：借助基于检索的语言模型，为现场机器人任务奠定操作合规性的基础

发布时间：2024年11月18日

`RAG` `机器人` `任务规划`

> SayComply: Grounding Field Robotic Tasks in Operational Compliance through Retrieval-Based Language Models

# 摘要

> 这篇论文探讨了在现实场景中必须遵循操作手册的机器人的任务规划难题。在这种约束条件下进行任务规划，对于在需要遵循特定领域知识的领域实现机器人自主操作意义重大。当下生成机器人目标和规划的方法，依赖于大型语言模型中编码的常识性知识。然而，这些模型存在机器人规划与特定领域知识结合不足的问题，而且在不同站点或有不同合规需求的客户之间难以迁移。在本研究中，我们推出了 SayComply，它借助基于检索的语言模型，实现了具有操作合规性的机器人任务规划。我们构建了一个包含操作、环境和机器人实体手册及程序的分层数据库，能在 LLM 有限的上下文长度内高效检索相关内容。接着，我们运用基于树的检索增强生成（RAG）技术设计了任务规划器，生成的机器人任务既能遵循用户指令，又能符合数据库中的领域知识。通过在现实场景中的模拟和硬件实验，我们证明了该方法的优越性，在需要对各类上下文进行精准检索的场景中，其表现优于标准的 RAG 方法。我们的方法填补了部署始终遵循操作协议的机器人的空白，为确保在复杂多样的现实环境中合规提供了可扩展且可边缘部署的解决方案。项目网站：saycomply.github.io。

> This paper addresses the problem of task planning for robots that must comply with operational manuals in real-world settings. Task planning under these constraints is essential for enabling autonomous robot operation in domains that require adherence to domain-specific knowledge. Current methods for generating robot goals and plans rely on common sense knowledge encoded in large language models. However, these models lack grounding of robot plans to domain-specific knowledge and are not easily transferable between multiple sites or customers with different compliance needs. In this work, we present SayComply, which enables grounding robotic task planning with operational compliance using retrieval-based language models. We design a hierarchical database of operational, environment, and robot embodiment manuals and procedures to enable efficient retrieval of the relevant context under the limited context length of the LLMs. We then design a task planner using a tree-based retrieval augmented generation (RAG) technique to generate robot tasks that follow user instructions while simultaneously complying with the domain knowledge in the database. We demonstrate the benefits of our approach through simulations and hardware experiments in real-world scenarios that require precise context retrieval across various types of context, outperforming the standard RAG method. Our approach bridges the gap in deploying robots that consistently adhere to operational protocols, offering a scalable and edge-deployable solution for ensuring compliance across varied and complex real-world environments. Project website: saycomply.github.io.

[Arxiv](https://arxiv.org/abs/2411.11323)