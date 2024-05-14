# 借助大型语言模型的自我对齐，我们探索了如何为机器人技能学习赋予奖励，这一创新方法旨在提升机器人在复杂任务中的自主学习能力。

发布时间：2024年05月12日

`Agent

这篇论文探讨了如何利用大型语言模型（LLM）来辅助机器人学习奖励函数，这是一个涉及智能体（Agent）在环境中学习和执行任务的问题。论文提出了一种新的方法，通过LLM来构思奖励特征和参数，并通过迭代自校准过程来精炼这些参数，以提高机器人在不同任务上的表现。这种方法涉及到了智能体的自主学习和适应，因此属于Agent分类。` `机器人技术` `人工智能`

> Learning Reward for Robot Skills Using Large Language Models via Self-Alignment

# 摘要

> 赋予机器人多才多艺的技能，学习奖励函数仍是关键挑战。大型语言模型（LLM）蕴藏的任务知识，或能助其一臂之力。然而，奖励函数若不精准，便难奏效，需与环境信息相融合。我们提出一种无需人类介入的奖励学习新途径。此法分两步：先由LLM构思奖励特征与参数，再经由迭代自校准过程精炼参数。这一过程旨在弥合LLM与奖励函数间的排序差异，依据执行反馈不断优化。在两个模拟环境中的九项任务上，此法已见成效，不仅提升了训练的效能与效率，且GPT代币消耗远低于基于变异的传统方法。

> Learning reward functions remains the bottleneck to equip a robot with a broad repertoire of skills. Large Language Models (LLM) contain valuable task-related knowledge that can potentially aid in the learning of reward functions. However, the proposed reward function can be imprecise, thus ineffective which requires to be further grounded with environment information. We proposed a method to learn rewards more efficiently in the absence of humans. Our approach consists of two components: We first use the LLM to propose features and parameterization of the reward, then update the parameters through an iterative self-alignment process. In particular, the process minimizes the ranking inconsistency between the LLM and the learnt reward functions based on the execution feedback. The method was validated on 9 tasks across 2 simulation environments. It demonstrates a consistent improvement over training efficacy and efficiency, meanwhile consuming significantly fewer GPT tokens compared to the alternative mutation-based method.

[Arxiv](https://arxiv.org/abs/2405.07162)