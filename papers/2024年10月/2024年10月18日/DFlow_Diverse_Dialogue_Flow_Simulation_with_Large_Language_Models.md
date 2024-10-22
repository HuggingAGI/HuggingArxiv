# DFlow：借助大型语言模型，模拟丰富多彩的对话流程

发布时间：2024年10月18日

`Agent` `人工智能` `对话系统`

> DFlow: Diverse Dialogue Flow Simulation with Large Language Models

# 摘要

> 构建基于语言模型的对话代理，需要能够遵循特定任务逻辑的训练数据。然而，现有数据增强方法多聚焦于话语层面的语言、主题或对话行为多样性，却忽视了对话层面任务逻辑多样性的关键。本文提出一种创新的数据增强方法，专注于任务执行逻辑，以提升合成对话的多样性。我们利用LLM生成决策树结构的任务计划，为特定任务推导出多样化的对话轨迹，即“对话流程”，指导生成多轮对话。该方法已应用于生成包含15个领域、3,886个对话流程的任务导向对话数据集。通过下一个动作预测任务验证，我们数据集上微调的模型表现超越了包括GPT-4在内的强基线。本文被接受后，我们将公开发布代码和数据。

> Developing language model-based dialogue agents requires effective data to train models that can follow specific task logic. However, most existing data augmentation methods focus on increasing diversity in language, topics, or dialogue acts at the utterance level, largely neglecting a critical aspect of task logic diversity at the dialogue level. This paper proposes a novel data augmentation method designed to enhance the diversity of synthetic dialogues by focusing on task execution logic. Our method uses LLMs to generate decision tree-structured task plans, which enables the derivation of diverse dialogue trajectories for a given task. Each trajectory, referred to as a "dialog flow", guides the generation of a multi-turn dialogue that follows a unique trajectory. We apply this method to generate a task-oriented dialogue dataset comprising 3,886 dialogue flows across 15 different domains. We validate the effectiveness of this dataset using the next action prediction task, where models fine-tuned on our dataset outperform strong baselines, including GPT-4. Upon acceptance of this paper, we plan to release the code and data publicly.

[Arxiv](https://arxiv.org/abs/2410.14853)