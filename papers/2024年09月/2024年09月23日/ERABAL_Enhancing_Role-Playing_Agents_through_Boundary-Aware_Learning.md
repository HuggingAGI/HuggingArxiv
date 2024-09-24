# ERABAL：利用边界感知学习提升角色扮演代理的能力

发布时间：2024年09月23日

`Agent` `人机交互` `角色扮演`

> ERABAL: Enhancing Role-Playing Agents through Boundary-Aware Learning

# 摘要

> 角色扮演在人机交互领域崭露头角，主要通过大型语言模型与角色的对齐训练实现。然而，角色扮演代理在保持对话一致性方面仍显不足，尤其是在处理与角色属性相关的微妙边界问题时。本文介绍的 ERABAL 框架，通过边界感知学习提升角色扮演能力，包括角色对话生成与对齐训练方法。评估显示，ERABAL 高效且有效，使用较少对话训练即可在多个评估中超越通用基线模型。我们还将公开代码和数据集，助力后续研究。

> Role-playing is an emerging application in the field of Human-Computer Interaction (HCI), primarily implemented through the alignment training of a large language model (LLM) with assigned characters. Despite significant progress, role-playing agents (RPLAs) still struggle with maintaining role-consistency across conversations, particularly when confronted with boundary queries subtly related to character attributes. In this paper, we present ERABAL, a framework aimed at enhancing RPLAs' role-playing capabilities through boundary-aware learning. ERABAL encompasses a generation pipeline for role-specific dialogues and a concomitant methodology for alignment training. Through comprehensive evaluations, we demonstrate that ERABAL is both efficient and effective. By training with significantly fewer dialogues than those used in leading approaches, ERABAL achieves notable improvements across WikiRoleEval, CharacterEval, and the role-playing subset of MT-Bench compared to the generalist baseline models. Our code and datasets will be made publicly available to support further research.

[Arxiv](https://arxiv.org/abs/2409.14710)