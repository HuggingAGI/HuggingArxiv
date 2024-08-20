# HiAgent：通过分层工作记忆管理，助力大型语言模型解决长周期代理任务

发布时间：2024年08月18日

`Agent` `人工智能` `智能代理`

> HiAgent: Hierarchical Working Memory Management for Solving Long-Horizon Agent Tasks with Large Language Model

# 摘要

> 基于大型语言模型的智能代理在多领域表现出色，通过处理环境信息生成任务动作。这些代理的效率关键在于其记忆系统，记录经验为动作与观察的序列。记忆分为跨尝试累积的长期记忆和单次尝试内的工作记忆。虽有研究优化长期记忆，但工作记忆的改进尚待探索。现有方法常将所有历史信息输入模型，造成长期任务的冗余。借鉴人类问题解决方式，我们提出 HiAgent 框架，利用子目标管理工作记忆，提升代理性能。HiAgent 让模型先设定子目标再行动，并智能更新相关信息。实验显示，HiAgent 在五项长期任务中成功率翻倍，步骤减少3.8，且性能稳定提升。项目详情见：https://github.com/HiAgent2024/HiAgent。

> Large Language Model (LLM)-based agents exhibit significant potential across various domains, operating as interactive systems that process environmental observations to generate executable actions for target tasks. The effectiveness of these agents is significantly influenced by their memory mechanism, which records historical experiences as sequences of action-observation pairs. We categorize memory into two types: cross-trial memory, accumulated across multiple attempts, and in-trial memory (working memory), accumulated within a single attempt. While considerable research has optimized performance through cross-trial memory, the enhancement of agent performance through improved working memory utilization remains underexplored. Instead, existing approaches often involve directly inputting entire historical action-observation pairs into LLMs, leading to redundancy in long-horizon tasks. Inspired by human problem-solving strategies, this paper introduces HiAgent, a framework that leverages subgoals as memory chunks to manage the working memory of LLM-based agents hierarchically. Specifically, HiAgent prompts LLMs to formulate subgoals before generating executable actions and enables LLMs to decide proactively to replace previous subgoals with summarized observations, retaining only the action-observation pairs relevant to the current subgoal. Experimental results across five long-horizon tasks demonstrate that HiAgent achieves a twofold increase in success rate and reduces the average number of steps required by 3.8. Additionally, our analysis shows that HiAgent consistently improves performance across various steps, highlighting its robustness and generalizability. Project Page: https://github.com/HiAgent2024/HiAgent .

[Arxiv](https://arxiv.org/abs/2408.09559)